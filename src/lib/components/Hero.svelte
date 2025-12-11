<script>
    // Hero Component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 bg-gray-50 relative overflow-hidden font-sans">
    <!-- Grid Background Pattern -->
    <div class="absolute inset-0 z-0 opacity-[0.4]" 
         style="background-image: linear-gradient(#e5e7eb 1px, transparent 1px), linear-gradient(90deg, #e5e7eb 1px, transparent 1px); background-size: 40px 40px;">
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col items-center text-center">
        
        <!-- Headline -->
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-serif-display text-gray-900 leading-[1.1] tracking-tight mb-6 max-w-5xl mx-auto">
            Win commerce in <br class="hidden md:block" />
            AI 
            <span class="inline-flex items-center align-middle mx-1 md:mx-2 relative -top-1 md:-top-2">
                <svg width="60" height="60" viewBox="0 0 100 100" class="w-10 h-10 md:w-16 md:h-16 text-[#EA580C] animate-spin-slow" fill="currentColor">
                    <!-- Stylized Asterisk/Flower -->
                    <path d="M50 0 L60 35 L95 25 L70 50 L95 75 L60 65 L50 100 L40 65 L5 75 L30 50 L5 25 L40 35 Z" />
                </svg>
            </span>
            search engines
        </h1>

        <!-- Subheadline -->
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
            Superpilot captures commerce growth opportunities across AI search engines via automated catalog-connected content generation.
        </p>

        <!-- CTA -->
        <div class="mb-16">
            <a href="#" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-base font-medium rounded-full text-gray-900 bg-brand-green hover:bg-brand-green-hover transition-all shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
                Book a Demo
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
            </a>
        </div>

        <!-- Video Player / Error State Recreation -->
        <div class="w-full max-w-5xl mx-auto rounded-lg overflow-hidden shadow-2xl bg-black aspect-video relative group cursor-pointer">
            <!-- Volume Icon -->
            <div class="absolute top-6 right-6 z-20 text-gray-400">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z"></path></svg>
            </div>

            <!-- Content -->
            <div class="absolute inset-0 flex flex-col items-center justify-center text-center p-8">
                <!-- Play Button Circle -->
                <div class="w-16 h-16 md:w-20 md:h-20 bg-white/10 backdrop-blur-sm rounded-full flex items-center justify-center mb-6 group-hover:bg-white/20 transition-all">
                    <svg class="w-8 h-8 md:w-10 md:h-10 text-white fill-current ml-1" viewBox="0 0 24 24">
                        <path d="M8 5v14l11-7z" />
                    </svg>
                </div>

                <!-- Demo Message -->
                <h3 class="text-white text-xl md:text-2xl font-medium mb-2">See how Superpilot works</h3>
                <p class="text-gray-400 text-sm md:text-base max-w-lg">
                    Watch how leading ecommerce brands capture AI search visibility with automated content generation.
                </p>
            </div>
            
            <!-- Progress Bar (Fake) -->
            <div class="absolute bottom-0 left-0 right-0 h-1 bg-gray-800">
                <div class="h-full w-1/3 bg-brand-green"></div>
            </div>
        </div>
    </div>
</section>
