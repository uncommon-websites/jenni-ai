<script lang="ts">
  let openIndex: number | null = null;
  
  const faqs = [
    { question: "Does Jenni plagiarize?", answer: "No, Jenni uses advanced AI to generate unique content and citations based on your inputs and sources." },
    { question: "Is there mobile support?", answer: "Yes, Jenni is optimized for mobile devices so you can research and write on the go." },
    { question: "Is Jenni multilingual?", answer: "Yes, Jenni supports multiple languages for both input and output." },
    { question: "Are citations up to date?", answer: "Jenni accesses a vast database of academic papers to ensure citations are accurate and up to date." },
    { question: "What are citations?", answer: "Citations are references to the sources you used in your research, giving credit to the original authors." },
    { question: "Which AI models does Jenni use?", answer: "Jenni utilizes a combination of state-of-the-art language models fine-tuned for academic writing." }
  ];

  function toggle(index: number) {
    if (openIndex === index) {
      openIndex = null;
    } else {
      openIndex = index;
    }
  }
</script>

<section class="py-20 bg-white">
  <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16">
      <h2 class="text-xs font-semibold text-[#4355FF] uppercase tracking-wider mb-2">Support</h2>
      <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Your questions, answered</h3>
    </div>

    <div class="space-y-4">
      {#each faqs as faq, i}
        <div class="border border-gray-200 rounded-lg overflow-hidden">
          <button 
            class="w-full flex justify-between items-center p-4 bg-white hover:bg-gray-50 text-left transition-colors"
            on:click={() => toggle(i)}
          >
            <span class="font-medium text-gray-900">{faq.question}</span>
            <svg 
              class="w-5 h-5 text-gray-500 transform transition-transform duration-200 {openIndex === i ? 'rotate-180' : ''}" 
              fill="none" 
              stroke="currentColor" 
              viewBox="0 0 24 24"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
            </svg>
          </button>
          {#if openIndex === i}
            <div class="p-4 bg-gray-50 text-gray-600 text-sm border-t border-gray-200">
              {faq.answer}
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</section>
