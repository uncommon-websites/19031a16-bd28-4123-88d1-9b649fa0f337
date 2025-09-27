<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
	
	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconEye from "~icons/lucide/eye";
	import IconTarget from "~icons/lucide/target";
	import IconZap from "~icons/lucide/zap";
	import IconShield from "~icons/lucide/shield";
	import IconLink from "~icons/lucide/link";
</script>

<CenteredTextOnlyHero
	title="Your eyes-up, context-aware assistant"
	subtitle="Smart glasses that deliver the right insight at the right moment—from sales prompts to cooking tips, always when you need them most."
	imageSrc="/generated/image-a-documentary-style-photograph-of-a-pers.webp"
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/meta.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/salesforce.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/twitch.tv/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We've created the first truly helpful wearable assistant that understands when to speak and when to stay quiet. Our smart glasses listen to your world and deliver perfectly timed insights—whether you're closing a deal, cooking dinner, or studying for an exam. Unlike other AI assistants that interrupt constantly, ours only speaks when it can genuinely help you succeed."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Senior Sales Executive",
			company: "CloudTech Solutions",
			quote:
				"The glasses saved me 2 hours daily by instantly providing client context and objection responses during meetings.\nMy close rate jumped 40% in the first month—ROI paid for itself in just 3 weeks.",
			image: "/generated/image-professional-headshot-of-marcus-chen-asi.webp"
		},
		{
			name: "Isabella Rodriguez",
			position: "Executive Chef",
			company: "Artisan Kitchen",
			quote:
				"No more ruined dishes from missed timing or forgotten ingredients.\nThe cooking coach mode cut my prep mistakes by 80% and helped me nail complex techniques I'd never attempted before.",
			image: "/generated/image-professional-headshot-of-isabella-rodrig.webp"
		},
		{
			name: "David Thompson",
			position: "Home Renovation Specialist",
			company: "Thompson Builds",
			quote:
				"The DIY helper mode eliminated costly measurement errors and material waste.\nSaved over $3,000 on my last project and finished 3 days ahead of schedule with perfect precision.",
			image: "/generated/image-professional-headshot-of-david-thompson-.webp"
		}
	]}
/>

<Features
	title="Always-on intelligence"
	subtitle="The right insight at the perfect moment, without the noise"
	features={[
		{
			title: "Smart abstain logic",
			description: "Only speaks when truly helpful, filtering out 95% of irrelevant moments. Your glasses stay quiet during private conversations and mundane tasks, activating precisely when you need support most.",
			icon: IconBrain
		},
		{
			title: "Context-aware assistance",
			description: "Combines what you see and hear to deliver perfectly timed insights. From sales objection responses to cooking measurements, every suggestion is tailored to your exact situation.",
			icon: IconEye
		},
		{
			title: "Personalized modes",
			description: "Switch between Sales Assist, Cooking Coach, DIY Helper, and Social Coach modes. Each mode understands your goals and delivers relevant prompts that actually help you succeed.",
			icon: IconTarget
		},
		{
			title: "Lightning-fast processing",
			description: "Text micro-loops run every 1-2 seconds for instant responses. Vision processing activates on-demand, ensuring you get real-time help without battery drain or delays.",
			icon: IconZap
		},
		{
			title: "Privacy-first design",
			description: "Speaker identification keeps conversations confidential, with red-zone policies that respect private moments. Your data stays secure while you stay informed.",
			icon: IconShield
		},
		{
			title: "Seamless integration",
			description: "Works with your existing Ray-Ban Meta or compatible smart glasses. No new hardware required—just download the app and transform your glasses into an intelligent assistant.",
			icon: IconLink
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
