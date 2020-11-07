<script lang="ts">
  import LogArea from "../components/LogArea.svelte";
  console.log(process.env.SVELTE_APP_FAUNADB_SECRET_FAUNADB_DOCS);
  let logDetails: object;
</script>

<LogArea bind:logDetails />
