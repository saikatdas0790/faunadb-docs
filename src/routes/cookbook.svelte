<script lang="ts">
  import LogArea from "../components/LogArea.svelte";
  import { someObject } from "../keys";
  console.log(someObject);
  let logDetails: object;
</script>

<LogArea bind:logDetails />
