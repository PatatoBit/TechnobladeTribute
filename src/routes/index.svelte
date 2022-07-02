<script lang="ts">
  import F from '../lib/components/F.svelte'
  import Modal from '$lib/components/Modal.svelte';
  import { modal } from '$lib/store';
  import { goto } from '$app/navigation';

  let clicked = 0;
</script>

<div class="grid h-screen place-items-center dark:bg-black">
  <div class="flex flex-col items-center justify-center gap-12">
    <h1 class="dark:text-white">A Tribute to Technoblade</h1>
    <F />
  </div>
</div>
