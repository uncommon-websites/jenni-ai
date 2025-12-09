<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="py-20 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16">
      <h2 class="text-xs font-semibold text-[#4355FF] uppercase tracking-wider mb-2">Data Import</h2>
      <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Import research in seconds</h3>
      <p class="text-lg text-gray-600">Bring your existing research from Zotero, Mendeley, and more.</p>
    </div>

    <!-- Import Visual -->
    <div class="bg-gray-50 rounded-2xl p-8 md:p-16 mb-12 relative overflow-hidden">
        <div class="flex flex-col md:flex-row items-center justify-center gap-8 relative z-10">
            <!-- Left Card: Zotero -->
            <div class="bg-white rounded-xl shadow-md p-6 w-full max-w-xs border border-gray-100">
                <div class="flex items-center gap-3 mb-4">
                    <div class="w-8 h-8 bg-red-100 rounded flex items-center justify-center text-red-600 font-bold text-lg">Z</div>
                    <span class="font-bold text-gray-900">Zotero</span>
                </div>
                <div class="space-y-3">
                    <div class="flex justify-between text-xs">
                        <span class="text-gray-500">Nuclear Fusion</span>
                        <span class="text-gray-400">10 sources</span>
                    </div>
                    <div class="h-1 bg-gray-100 rounded-full w-full"></div>
                    <div class="flex justify-between text-xs">
                        <span class="text-gray-500">Machine Learning</span>
                        <span class="text-gray-400">185 sources</span>
                    </div>
                     <div class="h-1 bg-gray-100 rounded-full w-full"></div>
                    <div class="flex justify-between text-xs">
                        <span class="text-gray-500">HCI</span>
                        <span class="text-gray-400">9 sources</span>
                    </div>
                </div>
            </div>

            <!-- Connector Lines (Visual only, simplified) -->
            <div class="hidden md:block w-24 h-px bg-gray-300 relative">
                 <div class="absolute -top-1 right-0 w-2 h-2 bg-gray-300 rounded-full"></div>
            </div>

            <!-- Right Card: Jenni -->
            <div class="bg-white rounded-xl shadow-md p-6 w-full max-w-xs border border-gray-100">
                <div class="flex items-center gap-3 mb-4">
                    <div class="w-8 h-8 bg-[#4355FF] rounded flex items-center justify-center">
                        <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <span class="font-bold text-gray-900">Jenni</span>
                </div>
                <div class="space-y-3">
                    <div class="flex justify-between text-xs items-center">
                        <span class="text-gray-500">Nuclear Fusion</span>
                        <span class="text-green-500 flex items-center gap-1">✓ Imported</span>
                    </div>
                    <div class="h-1 bg-gray-100 rounded-full w-full"></div>
                    <div class="flex justify-between text-xs items-center">
                        <span class="text-gray-500">Machine Learning</span>
                        <span class="text-gray-400 flex items-center gap-1">
                            <svg class="animate-spin h-3 w-3" viewBox="0 0 24 24"><circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle><path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"></path></svg>
                            Importing...
                        </span>
                    </div>
                     <div class="h-1 bg-gray-100 rounded-full w-full"></div>
                    <div class="flex justify-between text-xs items-center">
                        <span class="text-gray-500">HCI</span>
                        <span class="text-gray-300">Importing...</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Features Icons -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center mb-12">
        <div class="flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center mb-4 text-gray-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
            </div>
            <h4 class="font-bold text-gray-900 mb-1">Lightening fast</h4>
            <p class="text-sm text-gray-500">Import collections in seconds</p>
        </div>
        <div class="flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center mb-4 text-gray-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg>
            </div>
            <h4 class="font-bold text-gray-900 mb-1">Complete Metadata</h4>
            <p class="text-sm text-gray-500">Source types are preserved</p>
        </div>
        <div class="flex flex-col items-center">
            <div class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center mb-4 text-gray-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
            </div>
            <h4 class="font-bold text-gray-900 mb-1">PDFs Included</h4>
            <p class="text-sm text-gray-500">No need to re-attach any files</p>
        </div>
    </div>

    <div class="flex justify-center">
        <Button size="lg">Get started — it's free</Button>
    </div>
  </div>
</section>
