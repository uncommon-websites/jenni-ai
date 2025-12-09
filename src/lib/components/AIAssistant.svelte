<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="py-20 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-xs font-semibold text-[#4355FF] uppercase tracking-wider mb-2">AI Assistant</h2>
    <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Never write alone</h3>
    <p class="text-lg text-gray-600 max-w-2xl mx-auto mb-8">Get suggestions whenever you are stuck or expand your notes into full paragraphs</p>
    
    <div class="flex justify-center mb-12">
        <Button size="lg">Start writing — it's free</Button>
    </div>

    <!-- Interface Screenshot -->
    <div class="relative max-w-5xl mx-auto rounded-xl shadow-2xl border border-gray-200 bg-white overflow-hidden text-left">
        <!-- Mockup Header -->
        <div class="bg-white border-b border-gray-100 p-2 flex items-center gap-2">
            <div class="flex gap-1.5 ml-2">
                <div class="w-3 h-3 rounded-full bg-red-400"></div>
                <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                <div class="w-3 h-3 rounded-full bg-green-400"></div>
            </div>
        </div>
        
        <div class="flex h-[400px]">
            <!-- Sidebar -->
            <div class="w-64 border-r border-gray-100 bg-gray-50 p-4 hidden md:block">
                 <div class="space-y-4">
                    <div class="h-4 bg-gray-200 rounded w-3/4"></div>
                    <div class="h-4 bg-gray-200 rounded w-1/2"></div>
                </div>
            </div>
            
            <!-- Main Content -->
            <div class="flex-1 p-8 md:p-12 relative">
                <h2 class="text-3xl font-bold mb-6">Carbon emission – causes, Impacts, and Potential Solutions</h2>
                <h3 class="text-xl font-semibold mb-3">Carbon Dioxide (CO2)</h3>
                <p class="text-gray-800 leading-relaxed mb-4">
                    Carbon dioxide is the most well-known greenhouse gas. It is primarily released into the atmosphere through the burning of fossil fuels, <span class="text-[#4355FF]">such as coal, oil, and natural gas. Deforestation and land use changes also contribute to increased levels of CO2 in the atmosphere. (Plass, 2023)</span>
                </p>
                <div class="flex items-center gap-2 mb-8">
                     <button class="bg-[#4355FF] text-white text-xs px-3 py-1 rounded-full">Accept →</button>
                     <button class="text-gray-500 text-xs">Try Again</button>
                </div>

                <h3 class="text-xl font-semibold mb-3">Sources and Emissions</h3>
            </div>
        </div>
    </div>
  </div>
</section>
