<script>
    import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-[#F9F7F2] py-24 overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mb-8">
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowLeft size={16} />
            </button>
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowRight size={16} />
            </button>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Quote Content -->
            <div class="pr-8">
                <div class="mb-8">
                    <span class="text-sm font-bold tracking-widest uppercase">ACQUISITIONS DIRECTOR</span>
                </div>
                <blockquote class="text-2xl md:text-3xl font-light text-gray-900 leading-relaxed mb-12">
                    "Before Planisphere, we were drowning in broker emails and missing deals because we couldn't process them fast enough. Now we capture 100% of inbound opportunities, and our team focuses only on the deals that actually fit our criteria. We've saved 25+ hours per week."
                </blockquote>
                <div>
                    <div class="font-medium text-gray-900">Sarah Chen</div>
                    <div class="text-[10px] uppercase tracking-widest text-gray-500 mt-1">VP of Acquisitions, Multifamily Investment Fund</div>
                </div>
            </div>

            <!-- Image -->
            <div class="relative h-[600px] w-full overflow-hidden">
                <img 
                    src="/generated/image-professional-woman-in-business-attire-re-1765516796131-1.webp" 
                    alt="Real estate professional" 
                    class="absolute inset-0 h-full w-full object-cover grayscale contrast-125"
                />
            </div>
        </div>
    </div>
</section>
