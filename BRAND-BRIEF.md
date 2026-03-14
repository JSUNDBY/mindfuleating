# Superthoughts: Mindful Eating Program – Brand Brief

## The Promise

Your mind already knows how to eat well. Superthoughts helps you tune back in. This is not a diet, not a meal plan, not another set of rules. It is a practice. Short, guided recordings that train your awareness around food so you naturally choose differently. No restriction. No guilt. Just clarity.

This practice works alongside any approach to food – it supports a healthier lifestyle no matter what else someone is doing.

## Core Belief

The mind is extraordinarily powerful with practice. We do not fight the mind or override it with willpower. We work with it. When you notice what your mind is doing around food – the habits, the autopilot, the emotional shortcuts – you naturally begin to shift. Awareness is the change.

## Tone

- **Warm and sincere** – Josh has a gentle, soothing voice. The tone is like a trusted friend, not a guru or authority figure.
- **Hopeful and positive** – We lead with possibility, not fear. We never shame. We never use the language of failure.
- **Grounded and practical** – No jargon, no woo. Simple language. Real results.
- **Confident but not pushy** – We know this works. We invite, we don't pressure.
- **Honest** – We acknowledge the struggle without dwelling in it. We meet people where they are.

## What We Do NOT Say

- No em dashes (use en dashes or restructure the sentence)
- Never call the complimentary session "free" – use "complimentary"
- Never use the word "rewire" – use "realign" or "shift"
- Never use the word "failure" in reference to diets or the listener
- Never mention Insight Timer by name
- Never use guilt, shame, or fear-based language
- Avoid the word "SuperThoughts" (capital T) – it is always "Superthoughts"

## The Sessions (7 total, ~95 minutes)

### 01 – Arriving at the Table (12 min)
**Focus:** Foundation
Learning to be fully present before you eat. Putting down the phone, the scroll, the mental to-do list. Being there with your food. Most people are shocked by how rarely they actually taste what they are eating.

### 02 – Hunger vs. Habit (14 min)
**Focus:** Awareness
Recognizing the difference between true physical hunger and autopilot cravings. Tuning back into the body's signals. Understanding when "I'm hungry" really means "I'm bored" or "I'm anxious" or "it's 12:30 and that's when I eat."

### 03 – The Pause (11 min)
**Focus:** Core practice
The single most transformative skill in the program. Between every impulse to eat and the act of eating, there is a gap. This session trains you to find it and widen it. Not to stop yourself from eating, but to make eating a choice instead of a reflex.

### 04 – Eating With Your Senses (15 min)
**Focus:** Sensory
Eating with full sensory attention: texture, temperature, flavor, aroma. When you eat quickly or distractedly, you need more food to feel satisfied because you never fully registered what you ate. The result: more satisfaction from less food, not from restriction, but from actually tasting.

### 05 – The Stories We Tell (13 min)
**Focus:** Mental patterns
Guilt after eating. Shame about your body. The constant scoring of "good" and "bad" foods. These are stories the mind rehearses until they feel like facts. This session helps you see these patterns as mental habits, not truths. Stories you can notice without believing.

### 06 – Emotional Weather (16 min)
**Focus:** Emotional awareness
Emotional eating exists because eating works. It genuinely soothes, numbs, comforts. This session does not shame you for emotional eating. Instead, it teaches you to meet the emotion directly, to sit with it for even a few breaths before reaching for food. Not every time. Just sometimes. That is enough to start.

### 07 – Your Own Way Forward (14 min)
**Focus:** Integration
Tying everything together. You do not need a program forever. You need a practice you can carry into any meal, any day, for the rest of your life. Which practices resonated most, how to use them daily, and how to be patient and compassionate with yourself when you fall back into old patterns.

## The Funnel

1. **Landing page** (index.html) – Email capture offering a complimentary 6:30 guided mindful eating session. Posts to Kit form 9204882.
2. **Session delivery page** (free-session.html) – Delivers the audio recording via built-in player, then bridges to the full $49 program offer.
3. **Checkout** (checkout.html) – Purchase page with Stripe payment link (placeholder – needs real Stripe link).
4. **My Program** (my-program.html) – Post-purchase dashboard where customers stream/download all 7 sessions.

## Email / Kit Integration

- **Kit form ID:** 9204882 (inline form called "Mills form")
- **Automation:** "Mindful Eating – Free Session Delivery" (ID: 1911494) – active
- **Sequence:** "Mindful Eating Welcome"
  - Email 1: Immediate – session delivery link
  - Email 2: 2 days later – check-in nudge + checkout link
- **Sender:** hello@superthoughts.com (verified, SPF/DKIM/DMARC configured)
- **Incentive email:** Enabled with auto-confirm (double opt-in for spam protection)
- **Live URLs in Kit emails:**
  - Free session: https://jsundby.github.io/mindfuleating/free-session.html
  - Checkout: https://jsundby.github.io/mindfuleating/checkout.html

## The Offer

- $49 one-time payment
- 7 guided recordings, lifetime access
- No subscription, no upsells
- Future recordings included at no additional cost
- Stream or download on any device
- 14-day satisfaction guarantee ("reach out and we'll make it right")

## Audience

People who have tried diets, calorie counting, restriction, and willpower. They are tired of fighting themselves around food. They are open to a different approach. They want something that feels kind, not punishing. Many are already familiar with mindfulness or meditation. Some are completely new to it. This practice complements any existing approach to food.

## Brand Identity

- **Name:** Superthoughts (one word, lowercase t)
- **Positioning:** Superthoughts is the overall brand. Mindful Eating is the first program under that umbrella.
- **Visual tone:** Deep, dark, warm but not brown. Premium and grounded – not the typical soft-pastel wellness aesthetic.
- **Colors:** Deep dark backgrounds (#0a0c10), warm amber/gold accent (#d4a853), sage green secondary (#7d9b8a), dusty rose tertiary (#b8929a)
- **Typography:** Libre Baskerville (display), Source Sans 3 (body), DM Mono (tags/meta)
- **Logo:** Gradient mark (amber to sage) + "SUPERTHOUGHTS" monospace wordmark
- **Film grain texture:** Subtle SVG noise overlay across the entire site

## Key Proof Points

- 40,000+ total plays across guided sessions
- 4.9 out of 5 rating
- 25+ years of mindfulness practice (Josh Sundby)
- Listeners in 20+ countries
- Real testimonials from real practitioners

## Research Backing

- Mindful eating leads to greater psychological wellbeing, increased pleasure when eating, and body satisfaction. It addresses shame and guilt by promoting a non-judgmental attitude. (The Nutrition Source)
- A review of 68 studies found mindfulness-based approaches most effective at addressing binge eating, emotional eating, and eating in response to external cues. (PubMed)
- Associated with reduced anxiety, depression, social dysfunction, and loss of confidence. (Springer)
- Greater mindfulness practice leads to increased behavioral flexibility, helping break compulsive eating patterns. (Nature)

## Key Headlines

- **Hero:** "The hunger you feel isn't always hunger."
- **Experience section:** "Awareness changes everything. Here's how."

## Infrastructure

- **Domain:** superthoughts.com (GoDaddy)
- **Email:** hello@superthoughts.com → forwards to j.sundby@gmail.com
- **DNS:** SPF, DKIM, DMARC configured for Kit sending
- **Hosting:** GitHub Pages – https://mindful-eating.superthoughts.com/
- **Custom domain:** mindful-eating.superthoughts.com (CNAME in GoDaddy → jsundby.github.io, HTTPS enforced)
- **Repo:** https://github.com/JSUNDBY/mindfuleating
- **Auto-deploy:** GitHub Actions workflow on push to main
- **Payments:** Stripe (payment link placeholder – needs real link in checkout.html)

## Live URLs in Kit Emails

- Free session: https://mindful-eating.superthoughts.com/free-session.html
- Checkout: https://mindful-eating.superthoughts.com/checkout.html

## Still TODO

- [ ] Connect real Stripe payment link in checkout.html
- [x] Point custom domain mindful-eating.superthoughts.com to GitHub Pages (done – HTTPS enforced, cert expires 2026-06-12)
- [ ] Set up Gmail "Send as" for hello@superthoughts.com so Josh can reply from that address
- [ ] Update Kit sequence email links to use mindful-eating.superthoughts.com instead of jsundby.github.io/mindfuleating
