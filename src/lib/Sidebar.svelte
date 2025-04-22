<script>
    export let currentYear = new Date().getFullYear();
  </script>
  
  <aside class="w-64 bg-white shadow-lg flex flex-col justify-between">
    <div>
      <div class="px-6 py-6 text-2xl font-bold text-blue-600">My Dashboard</div>
      <nav class="mt-4 px-4">
        <!-- <a href="/" class="block px-4 py-2 rounded hover:bg-blue-100 text-gray-700">🏠 Welcome</a> -->
        <a href="/counter" class="block px-4 py-2 rounded hover:bg-blue-100 text-gray-700">🔢 Counter</a>
        <a href="/temperature" class="block px-4 py-2 rounded hover:bg-blue-100 text-gray-700">🌡 Temperature</a>
      </nav>
    </div>
    <div class="p-4 text-sm text-gray-500 border-t">© {currentYear}</div>
  </aside>
  