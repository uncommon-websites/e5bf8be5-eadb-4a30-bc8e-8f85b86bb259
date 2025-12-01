<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconSmartphone from "~icons/lucide/smartphone";
	import IconMessageSquare from "~icons/lucide/message-square";
	import IconHeart from "~icons/lucide/heart";
	import IconBarChart from "~icons/lucide/bar-chart";
	import IconTrendingUp from "~icons/lucide/trending-up";
</script>

<Hero
	title="Get paid faster, without the awkward chase"
	subtitle="AI-powered collections that automate follow-ups, so you can focus on the work you love while invoices get paid on time."
	imageSrc="/generated/image-a-friendly-hvac-contractor-with-a-warm-s.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by service professionals"
	logoUrls={[
		'https://cdn.brandfetch.io/servicetitan.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/getjobber.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/housecallpro.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/buildops.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We automate invoice collections for service businesses so you get paid faster without the awkward follow-up calls. Our AI-powered system sends smart, multi-channel reminders that feel personal and professional, helping home service contractors like HVAC owners turn their $50 billion accounts receivable into cash flow they can count on."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Rodriguez",
			position: "Owner",
			company: "Rodriguez HVAC Services",
			quote:
				"We cut our average payment time from 45 days to 18 days. The automated reminders handle the awkward conversations, and I get to focus on keeping my customers comfortable instead of chasing invoices.",
			image: "/generated/image-confident-hispanic-male-hvac-contractor-.webp"
		},
		{
			name: "Jennifer Chen",
			position: "Owner",
			company: "Chen Plumbing & Heating",
			quote:
				"Our cash flow improved by 60% in the first quarter. The AI knows exactly when to escalate, so we never lose money to forgotten invoices. It's like having a full-time collections specialist without the overhead.",
			image: "/generated/image-professional-headshot-of-an-asian-female.webp"
		},
		{
			name: "David Okonkwo",
			position: "Owner",
			company: "Okonkwo Electric",
			quote:
				"I was spending 8 hours a week on payment follow-ups. Now it's automated, and my team saved over $12,000 in admin costs last year alone. The white-labeled texts keep it professional and maintain our customer relationships.",
			image: "/generated/image-confident-black-male-electrical-contract.webp"
		}
	]}
/>

<Features
	title="Powerful automation that works for you"
	subtitle="Everything you need to get invoices paid faster, without lifting a finger"
	features={[
		{
			title: "Smart AI reminders",
			description:
				"Our AI learns each customer's payment patterns and automatically sends perfectly timed follow-ups. No more guessing when to reach out or what to say.",
			icon: IconBrain
		},
		{
			title: "Your number, your brand",
			description:
				"All messages come from your business phone number, keeping your customer relationships strong while we handle the awkward collections work.",
			icon: IconSmartphone
		},
		{
			title: "Multi-channel escalation",
			description:
				"Start with friendly text reminders, escalate to email, then phone calls automatically. The system adjusts based on what gets results.",
			icon: IconMessageSquare
		},
		{
			title: "Relationship-aware approach",
			description:
				"Never damage a customer relationship again. Our tone adapts to each situation, maintaining professionalism while getting you paid.",
			icon: IconHeart
		},
		{
			title: "Real-time payment tracking",
			description:
				"See exactly which invoices are overdue, who's been contacted, and what's working. Simple dashboard that shows you everything at a glance.",
			icon: IconBarChart
		},
		{
			title: "Faster cash flow",
			description:
				"Service businesses using our platform get paid 40% faster on average. That's money back in your pocket to grow your business.",
			icon: IconTrendingUp
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop chasing invoices"
	subtitle="Start getting paid on time"
	description="Join hundreds of service businesses that have cut their payment cycles by 40%. Set up automated collections in minutes, no credit card required to start your free trial."
	imageSrc="/generated/image-a-cheerful-hvac-contractor-sitting-in-th.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start free trial",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Book a demo",
			variant: "secondary"
		}
	]}
/>
