<script lang="ts">
  import Button from './ui/Button.svelte';
  
  let isMobileMenuOpen = false;
</script>

<header class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- Jenni Logo Placeholder -->
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-[#4355FF]">
            <path d="M12 2L2 7L12 12L22 7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M2 17L12 22L22 17" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M2 12L12 17L22 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          <span class="font-bold text-xl tracking-tight text-gray-900">Jenni</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <nav class="hidden md:flex space-x-8">
        <a href="#pricing" class="text-gray-600 hover:text-gray-900 text-sm font-medium">Pricing</a>
        <div class="relative group">
          <button class="text-gray-600 group-hover:text-gray-900 text-sm font-medium flex items-center gap-1">
            Teams
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
          </button>
        </div>
        <a href="#about" class="text-gray-600 hover:text-gray-900 text-sm font-medium">About</a>
        <a href="#blog" class="text-gray-600 hover:text-gray-900 text-sm font-medium">Blog</a>
      </nav>

      <!-- CTA Buttons -->
      <div class="hidden md:flex items-center space-x-4">
        <a href="#login" class="text-gray-600 hover:text-gray-900 text-sm font-medium">Log in</a>
        <Button href="#start" size="sm">Start writing</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button class="text-gray-600 hover:text-gray-900 p-2">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
        </button>
      </div>
    </div>
  </div>
</header>
