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
	import IconHeart from "~icons/lucide/heart";
	import IconClock from "~icons/lucide/clock";
	import IconWind from "~icons/lucide/wind";
	import IconUsers from "~icons/lucide/users";
	import IconSparkles from "~icons/lucide/sparkles";
	import IconMapPin from "~icons/lucide/map-pin";
</script>

<Hero
	centered={false}
	title="Build strength and find inner peace"
	subtitle="Inclusive, breath-centered yoga classes in Boonton for all abilities. Whether you're stressed, busy, or new to yoga, you belong here."
	imageSrc="/generated/image-documentary-style-editorial-photograph-o.webp"
/>
<LogoScroller
	label="Inspired by wellness leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/lululemon.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/headspace.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/calm.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/whoop.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Your wellness journey starts here"
	text="Zenden Wellness brings inclusive, breath-centered yoga to busy professionals in Boonton who need stress relief but feel intimidated by traditional studios. Led by our team of 12+ certified instructors, we create a warm, welcoming space where all abilities belong—from complete beginners to experienced practitioners. Whether you join us for gentle restorative sessions or energizing vinyasa flows, you'll discover how yoga's transformative power builds both physical strength and inner peace."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Patel",
			position: "Marketing Director",
			company: "Boonton",
			quote:
				"I used to spend $180 monthly on private sessions trying to manage stress. Zen Den's 10-class package saved me over $1,200 this year while giving me the same relief in a supportive group setting.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Financial Advisor",
			company: "Boonton",
			quote:
				"As someone with a bad back, I was worried yoga would make things worse. Emily's modifications and injury-conscious approach let me build strength safely. No physical therapy bills in 8 months.",
			image: "/generated/image-editorial-headshot-of-a-black-man-in-bus.webp"
		},
		{
			name: "Carmen Rodriguez",
			position: "Elementary Teacher",
			company: "Boonton",
			quote:
				"The 7:15 AM classes fit perfectly before work. I get my stress relief done in 60 minutes instead of driving 40 minutes each way to the next closest studio. That's 6 hours back in my week.",
			image: "/generated/image-editorial-environmental-portrait-of-a-hi.webp"
		}
	]}
/>

<Features
	title="Why choose Zenden Wellness"
	subtitle="Discover what makes our studio different and why Boonton professionals trust us for their wellness journey"
	features={[
		{
			title: "Yoga for every body",
			description:
				"No intimidation, no pressure to be flexible or perfect. Our classes welcome all abilities with modifications for every pose, because you know your body best.",
			icon: IconHeart
		},
		{
			title: "Classes that fit your schedule",
			description:
				"From 7:15 AM energizing flows to 10 PM restorative unwind sessions, find the perfect class time that works with your busy professional life.",
			icon: IconClock
		},
		{
			title: "Breath-centered practice",
			description:
				"Experience our unique approach combining breathwork, meditation, and Emotional Freedom Techniques to release stress and cultivate lasting inner peace.",
			icon: IconWind
		},
		{
			title: "Expert, specialized instructors",
			description:
				"Learn from 12+ certified teachers with diverse backgrounds in Vinyasa, Hatha, prenatal yoga, sound healing, Reiki, and more.",
			icon: IconUsers
		},
		{
			title: "Holistic wellness integration",
			description:
				"Beyond traditional yoga, we weave Ayurvedic wisdom, qigong, sound healing, and art therapy into practices that nurture your whole self.",
			icon: IconSparkles
		},
		{
			title: "Welcoming Boonton community",
			description:
				"Join a warm, supportive local community at 502 Main St where connection and authenticity matter as much as the practice itself.",
			icon: IconMapPin
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Your first class is waiting"
	subtitle="Join us this week"
	description="Stop letting stress control your schedule. With classes from 7:15 AM to 10 PM, we make it easy to start your yoga journey right here in Boonton. Drop in for just $18, or save with our 5-class package at $85. No flexibility required, no judgment, no intimidation—just a warm welcome and expert guidance. Your mat is ready."
	imageSrc="/generated/image-a-woman-sits-peacefully-on-a-yoga-mat-in.webp"
	callsToAction={[
		{
			href: "https://zenden-wellness.taramala.co/",
			label: "Book your first class",
			variant: "primary"
		},
		{
			href: "mailto:namaste@zendenwellness.com",
			label: "Ask us anything",
			variant: "secondary"
		}
	]}
/>
