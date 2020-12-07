<script lang="ts">
  import LogArea from "../components/LogArea.svelte";
  // import faunadb, { query as q } from "faunadb";

  let logDetails: object;
  // const adminClient = new faunadb.Client({
  //   secret: process.env.SVELTE_APP_FAUNADB_SECRET_FAUNADB_DOCS,
  // });
</script>

<LogArea bind:logDetails />
