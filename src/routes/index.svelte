<script>
   import { page } from '$app/stores'
   import Modal from '$lib/Modal.svelte'
</script>

<a href="/#modal">Open Modal</a>

{#if $page.url.hash === '#modal'}
   <Modal />
{/if}
