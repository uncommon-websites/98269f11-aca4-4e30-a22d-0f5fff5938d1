<script>
  export let active = "Product";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <svg width="28" height="28" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-gray-900">
          <path
            d="M17.2235 12.5566C17.2235 15.0114 15.2335 17.0015 12.7787 17.0015C10.3239 17.0015 8.33384 15.0114 8.33384 12.5566H4.77795C4.77795 16.9753 8.36002 20.5574 12.7787 20.5574C17.1974 20.5574 20.7794 16.9753 20.7794 12.5566C20.7794 8.13797 17.1974 4.55591 12.7787 4.55591V8.11179C15.2335 8.11179 17.2235 10.1018 17.2235 12.5566Z"
            fill="currentColor"
          />
          <path
            opacity="0.5"
            d="M7.44485 2.77795C7.44485 5.23278 5.45483 7.22281 3 7.22281V10.7787C7.41869 10.7787 11.0007 7.19663 11.0007 2.77795H7.44485Z"
            fill="currentColor"
          />
        </svg>
        <span class="text-2xl font-bold tracking-tight font-sans">Planisphere</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["Product", "Security", "Company", "Careers"] as item}
          <a href="#{item.toLowerCase()}" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium text-gray-900 hover:text-gray-700">
        Log in
      </a>
      <a href="#demo" class="rounded-full bg-black px-4 py-2 text-sm font-medium text-white hover:bg-gray-800 transition-colors">
        Request Demo
      </a>
    </div>
  </div>
</header>
