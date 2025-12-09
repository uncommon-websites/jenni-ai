<script lang="ts">
</script>

<section class="py-20 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16">
      <h2 class="text-xs font-semibold text-[#4355FF] uppercase tracking-wider mb-2">Powerful Features</h2>
      <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Write, cite, and edit</h3>
      <p class="text-lg text-gray-600">Features built to enhance your research and writing capabilities.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <!-- Feature 1: In-text Citations -->
      <div class="bg-gray-50 rounded-2xl p-8 overflow-hidden group hover:shadow-lg transition-shadow">
        <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-4 mb-6 h-64 relative overflow-hidden">
            <!-- Mockup for citations -->
            <div class="text-sm text-gray-500 mb-2">Exploring the Role of Neural Networks...</div>
            <div class="text-xs text-gray-400 mb-4">Bahr LS, Bock M...</div>
            <div class="bg-green-50 p-2 rounded text-xs text-green-700 mb-2">Nature Science - 2023</div>
            <p class="text-xs text-gray-600 leading-relaxed">
                Interactions between the ribosomal exit tunnel and the nascent peptide can affect translation elongation rates.
            </p>
            <div class="absolute bottom-4 left-4 flex gap-2">
                 <button class="text-xs text-[#4355FF] flex items-center gap-1 font-medium">+ Add citation</button>
                 <button class="text-xs text-gray-500 flex items-center gap-1">Open Quote</button>
            </div>
        </div>
        <h4 class="text-xl font-bold text-gray-900 mb-2">In-text Citations</h4>
        <p class="text-gray-600">Jenni consults the latest research and your PDF uploads. Cite in over 2.6k citation styles</p>
      </div>

      <!-- Feature 2: AI Autocomplete -->
      <div class="bg-gray-50 rounded-2xl p-8 overflow-hidden group hover:shadow-lg transition-shadow">
        <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-6 mb-6 h-64 flex flex-col justify-center items-center">
             <div class="w-full max-w-sm">
                <div class="text-sm font-semibold mb-2">Implications of Climate Change</div>
                <p class="text-xs text-gray-600 leading-relaxed">
                    Due to their long atmospheric lifetimes and high warming potentials, fluorinated gases contribute significantly to climate change. Efforts have been made to reduce the emissions of these gases through the implementation of international agreements and regulations.
                    <span class="bg-purple-100 text-purple-800 px-1">The Kigali Amendment to the Montreal Protocol, for example, aims to phase down the production of HFCs (Cook, 2024)...</span>
                </p>
                <div class="mt-4 flex justify-center gap-2">
                    <button class="bg-[#4355FF] text-white text-xs px-3 py-1 rounded-full">Accept →</button>
                    <button class="bg-white border border-gray-200 text-gray-600 text-xs px-3 py-1 rounded-full">Customize ⌘ + J</button>
                </div>
             </div>
        </div>
        <h4 class="text-xl font-bold text-gray-900 mb-2">AI Autocomplete</h4>
        <p class="text-gray-600">Autocomplete will write alongside you to beat writer's block whenever you need a helping hand</p>
      </div>

      <!-- Feature 3: Agentic AI Chat -->
      <div class="bg-gray-50 rounded-2xl p-8 overflow-hidden group hover:shadow-lg transition-shadow">
        <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-4 mb-6 h-64 relative">
             <div class="flex items-start gap-3 mb-4">
                <div class="w-6 h-6 rounded-full bg-orange-200 flex items-center justify-center text-xs font-bold text-orange-700">F</div>
                <div class="bg-gray-100 rounded-lg rounded-tl-none p-3 text-xs text-gray-700 max-w-[80%]">
                    Which papers here are relevant to spatial computing?
                </div>
             </div>
             <div class="flex items-start gap-3 mb-2">
                 <div class="w-6 h-6 rounded-full bg-[#4355FF] flex items-center justify-center">
                    <svg class="w-3 h-3 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                 </div>
                 <div class="space-y-2 w-full">
                    <div class="flex items-center gap-2 text-xs text-gray-500">
                        <span class="w-2 h-2 rounded-full bg-blue-400 animate-pulse"></span>
                        Jenni is thinking...
                    </div>
                    <div class="bg-white border border-gray-200 rounded p-2 flex items-center gap-2">
                        <div class="w-4 h-4 bg-gray-200 rounded"></div>
                        <div class="h-2 bg-gray-200 rounded w-24"></div>
                    </div>
                 </div>
             </div>
        </div>
        <h4 class="text-xl font-bold text-gray-900 mb-2">Agentic AI Chat</h4>
        <p class="text-gray-600">Quickly understand and summarize your research papers and search for new research with our AI chat assistant</p>
      </div>

      <!-- Feature 4: Generate From Your Files -->
      <div class="bg-gray-50 rounded-2xl p-8 overflow-hidden group hover:shadow-lg transition-shadow">
        <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-4 mb-6 h-64 flex flex-col items-center justify-center border-dashed border-2 border-gray-200">
            <svg class="w-10 h-10 text-gray-300 mb-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12"></path></svg>
            <p class="text-sm font-medium text-gray-900">Drag and drop PDFs</p>
            <p class="text-xs text-[#4355FF] mt-1 cursor-pointer">click to browse</p>
            
            <!-- Floating PDF Icon -->
            <div class="absolute bottom-8 right-8 bg-white p-2 rounded shadow-lg transform rotate-12">
                <div class="w-8 h-10 bg-red-500 rounded-sm flex items-center justify-center text-white text-[8px] font-bold">PDF</div>
            </div>
        </div>
        <h4 class="text-xl font-bold text-gray-900 mb-2">Generate From Your Files</h4>
        <p class="text-gray-600">Bring your research papers to life with source-based generation and collection-level control</p>
      </div>
    </div>
  </div>
</section>
