<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 overflow-hidden bg-white">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    
    <!-- Hero Content -->
    <h1 class="text-4xl md:text-6xl font-bold tracking-tight text-gray-900 mb-6">
      Meet Your Intelligent<br class="hidden md:block" /> Research Assistant
    </h1>
    
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-8">
      The AI-powered workspace to help you<br class="hidden md:block" /> read, write, and organize research with ease.
    </p>
    
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-10">
      <Button size="lg" className="w-full sm:w-auto px-8 py-4 text-base">Start writing — it's free</Button>
    </div>
    
    <!-- Social Proof -->
    <div class="flex items-center justify-center gap-3 mb-16">
      <div class="flex -space-x-2">
        <img class="w-8 h-8 rounded-full border-2 border-white" src="https://i.pravatar.cc/100?img=1" alt="User" />
        <img class="w-8 h-8 rounded-full border-2 border-white" src="https://i.pravatar.cc/100?img=2" alt="User" />
        <img class="w-8 h-8 rounded-full border-2 border-white" src="https://i.pravatar.cc/100?img=3" alt="User" />
        <img class="w-8 h-8 rounded-full border-2 border-white" src="https://i.pravatar.cc/100?img=4" alt="User" />
        <img class="w-8 h-8 rounded-full border-2 border-white" src="https://i.pravatar.cc/100?img=5" alt="User" />
      </div>
      <div class="flex flex-col items-start">
        <div class="flex text-yellow-400 text-xs">
          ★★★★★
        </div>
        <span class="text-xs text-gray-500">Loved by over 5 million academics</span>
      </div>
    </div>

    <!-- Hero Image -->
    <div class="relative max-w-5xl mx-auto rounded-xl shadow-2xl border border-gray-200 bg-white overflow-hidden">
        <!-- Mockup Header -->
        <div class="bg-white border-b border-gray-100 p-2 flex items-center gap-2">
            <div class="flex gap-1.5 ml-2">
                <div class="w-3 h-3 rounded-full bg-red-400"></div>
                <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                <div class="w-3 h-3 rounded-full bg-green-400"></div>
            </div>
            <div class="mx-auto text-xs text-gray-400 font-medium">Hardware Prototyping for Digital Systems</div>
        </div>
        
        <!-- Mockup Content -->
        <div class="flex text-left h-[500px] overflow-hidden">
            <!-- Sidebar -->
            <div class="w-64 border-r border-gray-100 bg-gray-50 p-4 hidden md:block">
                <div class="space-y-4">
                    <div class="h-4 bg-gray-200 rounded w-3/4"></div>
                    <div class="h-4 bg-gray-200 rounded w-1/2"></div>
                    <div class="h-4 bg-gray-200 rounded w-5/6"></div>
                    <div class="pt-4">
                        <div class="h-3 bg-gray-200 rounded w-full mb-2"></div>
                        <div class="h-3 bg-gray-200 rounded w-full mb-2"></div>
                        <div class="h-3 bg-gray-200 rounded w-full mb-2"></div>
                    </div>
                </div>
            </div>
            <!-- Main Content -->
            <div class="flex-1 p-8 bg-white relative">
                <h2 class="text-2xl font-bold mb-4 text-gray-900">Hardware Prototyping for Digital Systems: A Review</h2>
                <h3 class="text-lg font-semibold mb-2 text-gray-800">Introduction</h3>
                <p class="text-gray-600 text-sm leading-relaxed mb-4">
                    Traditional logic simulation has proven inadequate for comprehensive digital design verification due to its inability to interact with complete systems <span class="text-[#4355FF] bg-blue-50 px-1 rounded cursor-pointer">(Trost et al., 2001)</span>. As a result, hardware prototyping has gained prominence as an essential verification methodology.
                </p>
                <div class="absolute top-1/3 left-1/2 transform -translate-x-1/2 bg-white shadow-xl rounded-lg border border-gray-200 p-4 w-80 z-10">
                    <div class="text-xs text-gray-500 mb-1">Cited by 486 • 7.6.8 • Open Access</div>
                    <div class="font-semibold text-sm mb-1 text-gray-900">Prototyping Hardware and Software Environment for Teaching Digital Circuit Design</div>
                    <div class="text-xs text-gray-500 italic mb-2">Trost, Andrej; Zemva, Andrej</div>
                    <div class="text-xs text-gray-400">International Journal of Electrical Engin... - 2001</div>
                    <div class="mt-3 flex gap-2">
                        <button class="text-xs bg-gray-100 hover:bg-gray-200 px-2 py-1 rounded text-gray-700">Edit</button>
                        <button class="text-xs bg-gray-100 hover:bg-gray-200 px-2 py-1 rounded text-gray-700">View Library</button>
                    </div>
                </div>
                <p class="text-gray-600 text-sm leading-relaxed">
                    The gap between simulation and real-world deployment often leads to costly iterations. Hardware prototyping bridges this gap by allowing designers to test their architectures in real-time scenarios.
                </p>
            </div>
             <!-- Right Sidebar -->
             <div class="w-72 border-l border-gray-100 bg-white p-4 hidden lg:block">
                <div class="text-xs font-semibold text-gray-400 uppercase tracking-wider mb-4">AI Assistant</div>
                <div class="bg-gray-50 p-3 rounded-lg text-sm text-gray-600 mb-3">
                    What did <span class="bg-red-100 text-red-800 px-1 rounded">@Trost et al.</span> conclude in this paper?
                </div>
                 <div class="bg-blue-50 p-3 rounded-lg text-sm text-gray-800">
                    The paper <span class="text-[#4355FF]">(Trost et al., 2001)</span> discusses a prototyping hardware and software environment developed for teaching digital circuits.
                </div>
            </div>
        </div>
    </div>

    <!-- Logos -->
    <div class="mt-16">
        <p class="text-sm text-gray-400 mb-8">Trusted by Universities and businesses across the world</p>
        <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16 opacity-50 grayscale">
            <!-- Penn -->
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/University_of_Pennsylvania_logo.svg/2560px-University_of_Pennsylvania_logo.svg.png" class="h-8 object-contain" alt="Penn">
            <!-- Cambridge -->
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/University_of_Cambridge_logo.svg/2560px-University_of_Cambridge_logo.svg.png" class="h-8 object-contain" alt="Cambridge">
            <!-- Waterloo -->
            <img src="https://upload.wikimedia.org/wikipedia/en/thumb/6/6e/University_of_Waterloo_seal.svg/1200px-University_of_Waterloo_seal.svg.png" class="h-12 object-contain" alt="Waterloo"> <!-- Seal is usually used, let's try text logo if available or just use text -->
            <!-- Oxford -->
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Oxford-University-Circlet.svg/1024px-Oxford-University-Circlet.svg.png" class="h-10 object-contain" alt="Oxford">
            <!-- Stanford -->
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Stanford_University_logo_2003.svg/2560px-Stanford_University_logo_2003.svg.png" class="h-8 object-contain" alt="Stanford">
        </div>
    </div>
  </div>
</section>
