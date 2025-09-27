<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Privacy-first intelligence",
			description: "Your conversations and visuals stay private with advanced speaker identification and red-zone policies that protect what matters most."
		},
		{
			title: "Utility over noise",
			description: "We speak only when helpful. Our decision engine ensures you get timely nudges, not constant chatter that disrupts your flow."
		},
		{
			title: "Eyes-up experiences",
			description: "Keep your focus on what matters. Our context-aware assistant delivers insights without forcing you to look down at screens."
		},
		{
			title: "Accessible innovation",
			description: "Premium AI assistance shouldn't cost a fortune. Our fair-use pricing and budget controls make advanced features accessible to everyone."
		}
	];
</script>

<SecondaryHero
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

 

<!-- CTA Section -->
<CallToAction
	title="Ready to stay ahead?"
	subtitle="Join the future of AI assistance"
	description="Start with our Starter plan for everyday productivity wins, or upgrade to Pro for advanced features and custom modes. Fair-use pricing means you only pay for what you need."
/>
