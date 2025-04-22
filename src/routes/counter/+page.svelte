<script>
    let count = 0;
  </script>
  
  <h1 class="text-2xl font-semibold">🔢 Counter</h1>
  <div class="mt-4 space-x-4">
    <button on:click={() => count--} class="px-4 py-2 bg-red-500 text-white rounded">-</button>
    <span class="text-xl">{count}</span>
    <button on:click={() => count++} class="px-4 py-2 bg-green-500 text-white rounded">+</button>
  </div>
  