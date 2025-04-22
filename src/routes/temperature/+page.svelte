<script>
    let celsius = 0;
    $: fahrenheit = (celsius * 9/5) + 32;
  </script>
  
  <h1 class="text-2xl font-semibold">🌡 Temperature Converter</h1>
  
  <div class="mt-4">
    <label for="celsius" class="block mb-2">Celsius</label>
    <input
      id="celsius"
      type="number"
      bind:value={celsius}
      class="border p-2 rounded w-40"
    />
    <p class="mt-2">
      Fahrenheit: <strong>{fahrenheit.toFixed(2)}</strong>
    </p>
  </div>
  