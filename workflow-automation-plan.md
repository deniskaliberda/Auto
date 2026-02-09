# Workflow Automation Plan
### Two Businesses: Dance Studio (Pro-Am) + SEO Company (Germany)

---

## Task Inventory & Priority Ranking

| Rank | Task | Time Cost (1-10) | Energy Drain (1-10) | Feasibility | Automation Score |
|------|------|-------------------|---------------------|-------------|-----------------|
| 1 | SEO client prospecting & outreach | 5 | 7 | 0.7 | 8.4 |
| 2 | Instagram content creation (dance studio) | 4 | 7 | 0.7 | 7.7 |
| 3 | SEO client reports (monthly) | 3 | 6 | 0.7 | 6.3 |
| 4 | Meta ad copy & creative improvement | 3 | 5 | 0.7 | 5.6 |
| 5 | Lead nurture sequences (Supercharge) | 2 | 3 | 0.7 | 3.5 |
| 6 | Growth strategy & ideas (dance studio) | 2 | 8 | 0.3 | 3.0 |
| 7 | Email responses (both businesses) | 1 | 3 | 0.7 | 2.8 |
| 8 | SEO audits & keyword analysis | 4 | 4 | 0.3 | 2.4 |

**Formula:** Automation Score = (Time Cost + Energy Drain) x Feasibility Rating

---

## WEEK 1: SEO Client Prospecting & Outreach System

**Why this first:** Highest automation score (8.4) AND directly generates revenue. Every week without this system is potential clients you're not reaching.

**Expected time saved:** 4-5 hours/week once the system is running

### The System

**Trigger:** Every Monday morning, spend 30 minutes running this process.

**Step 1: Build your prospect list (one-time setup, then weekly refresh)**

Use Claude with this prompt to identify prospects:

> I run an SEO company targeting small businesses in Germany. Help me identify types of local businesses that:
> - Depend heavily on local search (people Google them)
> - Typically have poor websites and SEO
> - Have enough revenue to afford SEO services (budget range: [your price]/month)
> - Are in [your target city/region]
>
> Give me 10 specific business categories and explain why each one is a good target.

Then use Google Maps + Google Search to find specific businesses:
- Search "[business type] + [city]" in Google
- Look at page 2 and 3 results — these businesses KNOW they exist but can't rank
- Check their websites for obvious SEO issues (no meta descriptions, slow load, no Google Business profile optimization)

**Step 2: Quick SEO audit for each prospect (your sales weapon)**

Use SE Ranking to run a quick audit on their website. Note the top 3-5 problems. This becomes your personalized hook in outreach.

**Step 3: Outreach email template**

Use Claude to generate personalized outreach. Use this prompt for each prospect:

> Write a cold outreach email in German for my SEO company. Here are the details:
>
> - Prospect business: [name, type, city]
> - Their website: [URL]
> - Top 3 SEO problems I found: [from SE Ranking audit]
> - My service: SEO optimization for small German businesses
> - Tone: professional but human, not salesy. Show I actually looked at their site.
> - Length: under 150 words
> - Include a specific, free insight they can act on immediately (builds trust)
> - CTA: offer a free 15-minute call to walk through what I found
>
> Write in German.

**Step 4: Follow-up sequence**

Create 3 follow-up emails (Day 3, Day 7, Day 14) using Claude:
- Follow-up 1: Short, reference original email, add one more insight
- Follow-up 2: Share a quick case study or result (even from your first client)
- Follow-up 3: Final check-in, no pressure, leave the door open

**Tools:**
- Claude: prospect research, email writing, personalization
- SE Ranking: quick audits for prospects (you already have premium)
- Gmail or your email client: sending (consider Mailtrack or similar for open tracking)

**Output:** 10 personalized outreach emails per week, each with a specific SEO insight about that business.

**Weekly time commitment once set up:** ~2 hours (vs. 5+ hours doing it manually or not doing it at all)

---

## WEEK 2: Instagram Content Engine (Dance Studio)

**Why this second:** Score of 7.7, you dread it, and consistent content is the #1 thing that builds awareness for a local studio. This removes the creative bottleneck.

**Expected time saved:** 3-4 hours/week

### The System

**Trigger:** First Monday of each month, spend 1 hour generating the entire month's content.

**Step 1: Define your content pillars (one-time setup)**

Use Claude with this prompt:

> I own a pro-am dance studio. Help me create 5 content pillars for Instagram that would attract new students. Our audience is adults interested in dance (likely 30-60 age range) who may be intimidated to start. The content should:
> - Show the fun/social side of pro-am dance
> - Address fears beginners have
> - Showcase student transformations and events
> - Position us as the welcoming, professional studio in the area
>
> For each pillar, give me 4 recurring post formats I can repeat monthly.

This gives you 20 post templates that rotate every month.

**Step 2: Monthly content batch**

Use Claude to generate a full month of content:

> Based on these content pillars: [paste pillars from Step 1]
>
> Create an Instagram content calendar for [month]. I need:
> - 4 posts per week (16 total for the month)
> - For each post: caption (in the language your audience speaks), 2-3 hashtag groups, and a description of what the image/video should show
> - Mix the pillars across the month
> - Include 2 posts that directly invite people to try a class (soft CTA)
> - Include 1 post per week that features student stories or testimonials (I'll fill in real names/details)
>
> Tone: warm, encouraging, professional but not stiff.

**Step 3: Hand off to your Instagram manager**

Share the content calendar with the person managing your Instagram. They handle:
- Creating or sourcing the actual images/videos (from studio footage, events, etc.)
- Scheduling posts
- You just review and approve

**Step 4: Monthly performance check**

At month end, ask Claude:

> Here are the engagement stats for this month's Instagram posts: [paste stats]
> Which content pillars performed best? What should we do more of next month? Any patterns?

**Tools:**
- Claude: content strategy, captions, calendar generation, performance analysis
- Canva (free): if your Instagram person needs design templates
- Your Instagram manager: execution and posting

**Output:** Full month content calendar with captions, visual directions, and hashtags — delivered to your Instagram manager on the 1st of each month.

---

## WEEK 3: SEO Client Report System

**Why this third:** Score of 6.3, and building this NOW with one client means the system is ready when you land clients from your Week 1 outreach. Also doubles as a sales asset — show prospects a sample report.

**Expected time saved:** 2-3 hours per client per month (compounds as you add clients)

### The System

**Trigger:** Last week of each month, run report process for each client.

**Step 1: Define your report template (one-time setup)**

Use Claude to design a professional report structure:

> I run an SEO company for small businesses in Germany. Design a monthly SEO report template that:
>
> - Looks professional but is understandable by non-technical business owners
> - Sections: Executive Summary, Keyword Rankings, Website Health, Traffic Overview, Local SEO Performance, Opportunities & Next Steps
> - For each section, tell me exactly what data points to include and where I pull them from (I use SE Ranking and Local Dominator)
> - The Executive Summary should be a plain-language paragraph a business owner actually wants to read
> - Include a "wins this month" section (clients love seeing progress)
> - End with clear recommended actions for next month
>
> Format it as a template I can fill in monthly.

**Step 2: Monthly data collection**

Pull data from your tools on the same day each month:
- SE Ranking: keyword positions, website audit score changes, traffic data
- Local Dominator: local keyword grid screenshots/data
- Google Business Profile: views, clicks, calls (if you have access)

**Step 3: Report generation**

Paste raw data into Claude:

> Here is the raw SEO data for [client name], [month]:
>
> SE Ranking data: [paste]
> Local Dominator data: [paste]
> Google Business Profile data: [paste if available]
>
> Using my report template, generate the full monthly report. Write the Executive Summary in German, in plain language. Highlight wins. Be honest about areas that need work but frame them as opportunities.

**Step 4: Review, export, send**

- Review Claude's output for accuracy
- Format in Google Docs or a simple PDF template
- Send to client with a short personal note

**Tools:**
- SE Ranking + Local Dominator: data source
- Claude: report writing, analysis, plain-language summaries
- Google Docs or Canva: final formatting
- Consider building a Google Docs template with your branding for consistency

**Output:** Professional monthly report per client, generated in under 30 minutes instead of 2-3 hours.

**Bonus:** Use a polished version of this report as a sample in your sales outreach from Week 1. Show prospects exactly what they'll receive.

---

## WEEK 4: Meta Ad Copy & Creative Improvement

**Why this fourth:** Score of 5.6. Your ads are running but underperforming. Better copy and creative testing can improve cost-per-lead without increasing ad spend.

**Expected time saved:** 2-3 hours/week + improved ad performance

### The System

**Trigger:** Every two weeks, refresh ad variations.

**Step 1: Audit current ads (one-time)**

Use Claude to analyze what you have:

> Here are the current Meta ads we're running for our pro-am dance studio:
>
> Ad 1: [paste headline, body copy, CTA, and describe the image/video]
> Ad 2: [paste same]
> (etc.)
>
> Current results:
> - Cost per lead: [amount]
> - Click-through rate: [%]
> - Which ad performs best/worst
>
> Analyze these ads. What's working? What's weak? Give me specific improvements for copy, hooks, and CTAs. Our target audience is adults 30-60 who are curious about dance but might be intimidated.

**Step 2: Generate ad variations**

Use Claude to create test batches:

> Write 5 Meta ad variations for our pro-am dance studio. For each ad:
> - A scroll-stopping hook (first line)
> - Body copy under 90 words
> - A clear CTA
> - Description of what image or video would pair well
>
> Each ad should take a different angle:
> 1. Social/fun angle (meet people, date night)
> 2. Overcoming fear angle (never danced before? perfect)
> 3. Transformation angle (student success story framework)
> 4. Urgency angle (limited spots, upcoming event)
> 5. Aspirational angle (imagine yourself on the dance floor)
>
> Write in [your ad language]. Tone: warm, inviting, not pushy.

**Step 3: A/B testing rotation**

- Take the 2 best variations (your gut + Claude's recommendation)
- Run them against your current best performer
- Every 2 weeks: kill the loser, write a new challenger with Claude
- Track cost-per-lead as your north star metric

**Step 4: Monthly performance review**

Feed results back into Claude monthly for continuous improvement:

> Here are the Meta ad results for [month]: [paste data]
> Which angles performed best? What should we test next month?

**Tools:**
- Claude: copywriting, analysis, variation generation
- Meta Ads Manager: running and tracking ads
- A simple spreadsheet: track which angles/hooks perform best over time

**Output:** Fresh ad variations every 2 weeks, data-driven creative improvements, and a testing system that continuously improves your cost-per-lead.

---

## Summary: Expected Total Impact

| Week | Task Automated | Time Saved/Week | Revenue Impact |
|------|---------------|-----------------|----------------|
| 1 | SEO client prospecting | 4-5 hrs | Direct: new clients |
| 2 | Instagram content | 3-4 hrs | Indirect: studio awareness & leads |
| 3 | SEO reports | 2-3 hrs/client | Direct: client retention + sales tool |
| 4 | Meta ad improvement | 2-3 hrs | Direct: lower cost per lead |
| **Total** | | **11-15 hrs/week** | **Growth across both businesses** |

## What To Do Right Now

1. Open Claude and run the Week 1, Step 1 prompt (prospect research)
2. Pick 5 businesses from Google page 2-3 results in your target city
3. Run quick SE Ranking audits on them
4. Use Claude to write 5 personalized outreach emails
5. Send them today

The system compounds. Week 1 feeds Week 3. Week 2 feeds Week 4. By the end of the month, both businesses have automated engines running.
