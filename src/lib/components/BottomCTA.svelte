<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<section class="py-24 bg-white">
  <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">Make progress on your greatest work, today</h2>
    <p class="text-lg text-gray-600 mb-8">Write your first paper with Jenni today and never look back</p>
    
    <div class="flex flex-wrap justify-center gap-6 mb-10 text-sm text-gray-500">
        <div class="flex items-center gap-2">
            <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
            Start for free
        </div>
        <div class="flex items-center gap-2">
            <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
            No credit card required
        </div>
        <div class="flex items-center gap-2">
            <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
            Cancel anytime
        </div>
    </div>

    <div class="flex justify-center mb-16">
        <Button size="lg" className="px-10 py-4 text-lg">Start writing — it's free</Button>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 border-t border-gray-100 pt-12">
        <div>
            <div class="font-bold text-2xl text-gray-900">Over 5m</div>
            <div class="text-sm text-gray-500">Academics worldwide</div>
        </div>
        <div>
            <div class="font-bold text-2xl text-gray-900">5.2 hours saved</div>
            <div class="text-sm text-gray-500">On average per paper</div>
        </div>
        <div>
            <div class="font-bold text-2xl text-gray-900">Over 15m</div>
            <div class="text-sm text-gray-500">Papers written on Jenni</div>
        </div>
    </div>
  </div>
</section>
