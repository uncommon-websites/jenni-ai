<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Features from "$lib/components/Features.svelte";
	import TraceableCitations from "$lib/components/TraceableCitations.svelte";
	import Workflow from "$lib/components/Workflow.svelte";
	import ImportSection from "$lib/components/ImportSection.svelte";
	import Testimonials from "$lib/components/Testimonials.svelte";
	import TeamSection from "$lib/components/TeamSection.svelte";
	import UseCases from "$lib/components/UseCases.svelte";
	import AIAssistant from "$lib/components/AIAssistant.svelte";
	import FAQ from "$lib/components/FAQ.svelte";
	import Tutorials from "$lib/components/Tutorials.svelte";
	import BottomCTA from "$lib/components/BottomCTA.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-white">
	<Header />
	<main>
		<Hero />
		<Features />
		<TraceableCitations />
		<Workflow />
		<ImportSection />
		<Testimonials />
		<TeamSection />
		<UseCases />
		<AIAssistant />
		<FAQ />
		<Tutorials />
		<BottomCTA />
	</main>
	<Footer />
</div>

