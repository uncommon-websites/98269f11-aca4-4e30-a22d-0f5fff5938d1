<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                From Inbox to Underwriting<br />In Minutes, Not Hours
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Auto-Ingest Deals -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Processing Broker Emails</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-primary-700">
                                <Check size={12} /> <span class="text-gray-600">Auto-ingesting deals...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Extracting property details</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Parsing attachments</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Creating deal record</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Auto-Ingest from Inbox</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Connect to your email and automatically capture 100% of inbound broker deals. Extract property details, pricing, and attachments without manual data entry.
                </p>
            </div>

            <!-- Card 2: Buy Box Triage -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Buy Box Match Analysis</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-700 rounded flex items-center justify-center text-white text-[8px]">AI</div>
                            <span class="text-[10px] text-gray-400">Scored 47 deals this week</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Property</div>
                                <div class="text-center">Match</div>
                                <div class="text-right">Cap Rate</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-green-500 rounded-sm"></div> Austin MF</div>
                                <div class="text-center text-green-600 font-medium">95%</div>
                                <div class="text-right">5.2%</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-yellow-500 rounded-sm"></div> Dallas Retail</div>
                                <div class="text-center text-yellow-600 font-medium">68%</div>
                                <div class="text-right">6.1%</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-300 rounded-sm"></div> Phoenix Office</div>
                                <div class="text-center text-gray-400 font-medium">42%</div>
                                <div class="text-right">7.8%</div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Smart Buy Box Triage</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    AI scores every deal against your investment criteria. Focus only on the ~5% that truly fit while maintaining a complete record of all opportunities.
                </p>
            </div>

            <!-- Card 3: Data Enrichment & Export -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-700 rounded flex items-center justify-center text-white text-[8px]">E</div>
                            <span class="text-[10px] text-gray-500">Exporting to underwriting...</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Deal enriched with market data and comps. Exporting structured data to your Excel template.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Austin_MF_Underwriting.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-blue-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Market_Comps_Report.pdf</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Data Enrichment & Export</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Automatically enrich deals with third-party market data, comps, and property details. Export structured data directly into your existing underwriting templates.
                </p>
            </div>
        </div>
    </div>
</section>
