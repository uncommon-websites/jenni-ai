<script lang="ts">
  import Button from './ui/Button.svelte';
</script>

<footer class="bg-[#0B1120] text-gray-400 py-16 text-sm">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-12 mb-16">
        <!-- Brand Column -->
        <div class="lg:col-span-1">
            <a href="/" class="flex items-center gap-2 mb-4 text-white">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-white">
                    <path d="M12 2L2 7L12 12L22 7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M2 17L12 22L22 17" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M2 12L12 17L22 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="font-bold text-xl tracking-tight">Jenni</span>
            </a>
            <p class="mb-6">Meet your intelligent research assistant</p>
            <Button size="sm" className="bg-[#4355FF] text-white border-none">Start writing</Button>
        </div>

        <!-- Links Columns -->
        <div>
            <h4 class="font-bold text-white mb-4">Use Cases</h4>
            <ul class="space-y-2">
                <li><a href="#" class="hover:text-white">Teams & Institutions</a></li>
                <li><a href="#" class="hover:text-white">For Researchers</a></li>
                <li><a href="#" class="hover:text-white">Literature Review Generator</a></li>
            </ul>
        </div>

        <div>
            <h4 class="font-bold text-white mb-4">Mini Tools</h4>
            <ul class="space-y-2">
                <li><a href="#" class="hover:text-white">Browser Extension</a></li>
                <li><a href="#" class="hover:text-white">Thesis Statement Generator</a></li>
                <li><a href="#" class="hover:text-white">Paraphrasing Tool</a></li>
                <li><a href="#" class="hover:text-white">AI Essay Outline Generation</a></li>
                <li><a href="#" class="hover:text-white">Essay Expander</a></li>
                <li><a href="#" class="hover:text-white">Sentence & Paragraph Expansion</a></li>
                <li><a href="#" class="hover:text-white">AI Essay Writer</a></li>
                <li><a href="#" class="hover:text-white">AI Summarizer</a></li>
                <li><a href="#" class="hover:text-white">Paragraph Generator</a></li>
                <li><a href="#" class="hover:text-white">TinyWow</a></li>
            </ul>
        </div>

        <div>
            <h4 class="font-bold text-white mb-4">Updates</h4>
            <ul class="space-y-2">
                <li><a href="#" class="hover:text-white">Changelog</a></li>
            </ul>
            <h4 class="font-bold text-white mt-6 mb-4">Company</h4>
            <ul class="space-y-2">
                <li><a href="#" class="hover:text-white">Careers</a></li>
                <li><a href="#" class="hover:text-white">Influencer program</a></li>
            </ul>
        </div>

        <div>
            <h4 class="font-bold text-white mb-4">Legal</h4>
            <ul class="space-y-2">
                <li><a href="#" class="hover:text-white">Terms of Service</a></li>
                <li><a href="#" class="hover:text-white">Privacy Policy</a></li>
                <li><a href="#" class="hover:text-white">Refund Policy</a></li>
            </ul>
        </div>
    </div>

    <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center gap-4">
        <div class="text-xs">
            Copyright © 2025 Jenni, Inc.<br>
            All rights reserved.
        </div>
        <div class="flex gap-4">
            <a href="#" class="hover:text-white"><svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/></svg></a>
            <a href="#" class="hover:text-white"><svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg></a>
            <a href="#" class="hover:text-white"><svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg></a>
            <a href="#" class="hover:text-white"><svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"/></svg></a>
        </div>
    </div>
  </div>
</footer>
