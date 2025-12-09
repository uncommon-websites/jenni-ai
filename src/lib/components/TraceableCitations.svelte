<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="py-20 bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    
    <!-- Testimonial -->
    <div class="max-w-3xl mx-auto text-center mb-24">
      <div class="flex justify-center mb-6">
        <div class="w-px h-12 bg-gray-200"></div>
      </div>
      <blockquote class="text-xl md:text-2xl font-medium text-gray-900 mb-6">
        "Jenni has been a game-changer for my research writing. Its intuitive design and powerful AI make it incredibly easy to get a grip on all of the papers I'm reading."
      </blockquote>
      <div class="flex items-center justify-center gap-3">
        <img src="https://i.pravatar.cc/100?img=12" alt="Vito" class="w-10 h-10 rounded-full" />
        <div class="text-left">
          <div class="text-sm font-semibold text-gray-900">Vito, PhD Candidate</div>
        </div>
      </div>
    </div>

    <!-- Traceable Citations -->
    <div class="text-center mb-16">
      <h2 class="text-xs font-semibold text-[#4355FF] uppercase tracking-wider mb-2">Easy Verification</h2>
      <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Traceable citations, every time</h3>
      <p class="text-lg text-gray-600 max-w-2xl mx-auto">Every citation links directly to the exact page and paragraph in your source PDFs. Verify sources in one click.</p>
    </div>

    <div class="bg-gray-50 rounded-2xl p-4 md:p-12 mb-12">
        <div class="bg-white rounded-xl shadow-lg border border-gray-200 overflow-hidden flex flex-col md:flex-row h-[500px]">
            <!-- Left Side: PDF Viewer -->
            <div class="flex-1 border-r border-gray-200 p-6 overflow-y-auto">
                <div class="flex items-center gap-2 mb-4">
                    <div class="w-2 h-2 rounded-full bg-red-400"></div>
                    <div class="w-2 h-2 rounded-full bg-yellow-400"></div>
                    <div class="w-2 h-2 rounded-full bg-green-400"></div>
                    <span class="ml-2 font-semibold text-gray-700">Neural Networks</span>
                    <span class="ml-auto text-xs bg-gray-100 px-2 py-1 rounded">PAGE 1</span>
                </div>
                <div class="space-y-4 text-sm text-gray-600">
                    <p>Neural networks have demonstrated remarkable capabilities in processing natural language, enabling machines to understand context, sentiment, and semantic relationships.</p>
                    <p class="bg-orange-100 p-1 rounded">Recent advancements in transformer architectures have revolutionized the field, allowing for more efficient training and better performance on downstream tasks.</p>
                    <p>Applications span from machine translation to question answering systems, each benefiting from the robust feature extraction capabilities of deep neural architectures.</p>
                    <p>Future research should focus on improving interpretability and reducing computational costs, making these systems more accessible to a wider range of applications.</p>
                </div>
            </div>
            
            <!-- Right Side: Chat/Analysis -->
            <div class="w-full md:w-96 bg-gray-50 p-6 flex flex-col">
                <div class="flex items-center gap-2 mb-6">
                    <div class="w-6 h-6 rounded-full bg-[#4355FF] flex items-center justify-center">
                        <svg class="w-3 h-3 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <span class="font-bold text-gray-900">AI Chat</span>
                </div>
                
                <div class="space-y-4 flex-1">
                    <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 text-sm">
                        <p class="text-gray-700 mb-3">Based on your papers, neural networks have shown remarkable capabilities in natural language processing. Their feasibility has been proven through peer-reviewed research, and future work should prioritize interpretability improvements</p>
                        
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 p-2 hover:bg-gray-50 rounded cursor-pointer transition-colors border border-transparent hover:border-gray-200">
                                <span class="bg-blue-100 text-blue-700 w-5 h-5 flex items-center justify-center rounded text-xs font-bold">1</span>
                                <span class="text-xs text-gray-600 truncate">Neural networks have demonstrated remarkable capabilities in processing natural...</span>
                            </div>
                             <div class="flex items-center gap-2 p-2 bg-orange-50 border border-orange-200 rounded cursor-pointer transition-colors">
                                <span class="bg-orange-100 text-orange-700 w-5 h-5 flex items-center justify-center rounded text-xs font-bold">2</span>
                                <span class="text-xs text-gray-800 truncate">Recent advancements in transformer architectures have revolutionized...</span>
                            </div>
                             <div class="flex items-center gap-2 p-2 hover:bg-gray-50 rounded cursor-pointer transition-colors border border-transparent hover:border-gray-200">
                                <span class="bg-blue-100 text-blue-700 w-5 h-5 flex items-center justify-center rounded text-xs font-bold">3</span>
                                <span class="text-xs text-gray-600 truncate">Future research should focus on improving interpretability...</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="flex justify-center">
        <Button size="lg">Get started — it's free</Button>
    </div>

  </div>
</section>
