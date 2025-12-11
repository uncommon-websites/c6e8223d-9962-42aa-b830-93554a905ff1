<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 0;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed top-0 w-full z-50 flex flex-col font-sans">
  <!-- Top Banner -->
  <div class="bg-[#F3F4F6] border-b border-gray-200 py-2 px-4 text-center text-[10px] sm:text-xs font-medium tracking-wide text-gray-900">
    <span class="mr-1">Get your free AI Search Visibility Report - See how your products appear in ChatGPT & Perplexity</span>
    <a href="#" class="inline-flex items-center hover:underline font-bold ml-1">
      GET FREE REPORT 
      <svg class="w-3 h-3 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
    </a>
  </div>

  <!-- Main Nav -->
  <nav class="bg-white/95 backdrop-blur-sm border-b border-gray-100 transition-all duration-200 {isScrolled ? 'py-3' : 'py-4'}">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="text-3xl font-serif-display font-bold tracking-tighter text-gray-900 flex items-center gap-1">
          Superpilot
        </a>
        
        <!-- Desktop Links -->
        <div class="hidden md:flex items-center ml-10 space-x-8 text-sm font-medium text-gray-600">
          <a href="#" class="hover:text-gray-900">Platform</a>
          <a href="#" class="hover:text-gray-900">For Ecommerce</a>
          <a href="#" class="hover:text-gray-900">Resources</a>
          <a href="#" class="hover:text-gray-900">Pricing</a>
        </div>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center space-x-4 sm:space-x-6">
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Log In</a>
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Start Free Trial</a>
        <a href="#" class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-gray-900 bg-brand-green hover:bg-brand-green-hover transition-colors shadow-sm">
          Book a Demo
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </a>
      </div>
    </div>
  </nav>
</div>
