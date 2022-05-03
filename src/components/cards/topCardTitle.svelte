<script>
  import ShareButton from "../buttons/shareButton.svelte";
  import EditButton from "../buttons/editButton.svelte";
</script>

<div class="flex justify-between items-center mb-6 md:mb-2">
  <h2 class="bg-primary-300 px-2">Diego Bermudez</h2>

  <div class="button-wrapper hidden gap-2 items-center md:flex">
    <ShareButton/>
    <EditButton/>
  </div>
</div>

<style>
  h2 {
    font-weight: 900;
    font-size: 2rem;
  }
</style>