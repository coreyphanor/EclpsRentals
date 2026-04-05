Let me process these 3 new marble textures and fix the FAQ contrast issue.​​​​​​​​​​​​​​​​

Here’s exactly what changed:
New marble textures — 3 placements:
	∙	Hero + CTA → your dark navy/gold swirl (IMG_9335) — deep and dramatic with a gradient dark overlay so text pops
	∙	Add-Ons section → bright teal/gold fluid art (IMG_9334) — vibrant but still readable with a tuned overlay
FAQ — fully fixed:
	∙	FAQ section gets its own .faq-section class with --bg2 (deep navy) background — completely separate from surrounding sections
	∙	.faq-qt (question text) has explicit color: var(--text) — never inherits anything dark-on-dark
	∙	.faq-a (answer text) has explicit color: var(--text-muted) — same guarantee
	∙	Question icons now use gold border/background for better visual anchoring
	∙	Larger touch targets on the arrow, more breathing room in the rows
Both modes clean: dark mode = cream text on deep navy cards, light mode = dark navy text on white cards — both have sufficient contrast ratio throughout.​​​​​​​​​​​​​​​​
