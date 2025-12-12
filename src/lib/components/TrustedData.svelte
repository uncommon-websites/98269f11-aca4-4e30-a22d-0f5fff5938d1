<script>
    const partners = [
        { name: "Your Deal Pipeline", icon: "🏢" },
        { name: "CoStar", icon: "C", color: "bg-orange-600" },
        { name: "Yardi Matrix", icon: "Y", color: "bg-blue-600" },
        { name: "RCA (MSCI)", icon: "R", color: "bg-red-600" },
        { name: "Reis", icon: "R", color: "bg-blue-800" },
        { name: "Reonomy", icon: "R", color: "bg-purple-600" },
        { name: "PropertyShark", icon: "P", color: "bg-blue-500" },
        { name: "Public Records", icon: "📋" },
        { name: "Market Reports", icon: "📊" },
        { name: "Broker Networks", icon: "🤝" },
        { name: "Property Listings", icon: "🏘️" },
        { name: "Transaction Data", icon: "💰" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Enriched with Market Intelligence</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                We integrate with leading real estate data providers to enrich every deal with market comps, property details, and transaction history. Planisphere's AI combines your internal pipeline with external intelligence to surface the insights that matter.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
