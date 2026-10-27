# Guneet Singh

**Founder of [Sparkonomy](https://www.sparkonomy.com) · Building AI products for Creators · Singapore**

*Creators are gaining rights over their identity in the age of AI. I’m designing the plumbing that makes those rights usable.*

After 20+ years across Google/YouTube, Microsoft and Samsung, I’m bringing together my experience in consumer technology, product growth and the Creator economy to build Sparkonomy.

## What we’re building

### Open Creator Graph (OCG)
A free, public identity and consent layer for Creators. It brings their social identities into one structured record, helps Search and AI understand who they are, and lets them declare how AI may use their identity.

### Creator Genome
Multimodal AI that turns a Creator’s content into deep context about their style, voice and work. This gives our agents a starting point for personalised help.

### AI business team
We’re building agents to help Creators with the work around their content: partnerships, planning, contracts, invoices and payments. Our earlier invoicing product was used by more than 2,500 Creators.

## My work on the Open Creator Graph (OCG)

AI needs to know two things about a Creator: **which information it can trust, and what it has permission to do.** I’ve focused my work on the Open Creator Graph on both.

### Give AI a reason to trust each fact
A Creator’s identity is scattered across platforms, with conflicting details and no clear way for AI to judge which source to trust. Bringing those details together is only the first step. Every data point also needs a confidence level and a source.

I designed OCG’s data trust model to make that confidence explicit at the level of each fact. **Verified, Sourced and Stated** distinguish platform-confirmed information from public-source evidence and a Creator’s own statements. The aim is to give AI engines the context to resolve conflicting information and describe a Creator accurately, rather than treat every claim as equally reliable.

[How OCG represents identity, sources and confidence](https://creatorgraph.sparkonomy.com/for-ai-and-search/)

### Make identity rights usable
A right only helps if you can exercise it. The [EU AI Act requires general-purpose model providers to identify and respect copyright reservations](https://digital-strategy.ec.europa.eu/en/faqs/guidelines-obligations-general-purpose-ai-providers). Separately, lawmakers are strengthening protections over voice and likeness: the proposed [NO FAKES Act advanced unanimously out of the US Senate Judiciary Committee in June 2026](https://www.blackburn.senate.gov/2026/6/blackburn-coons-bipartisan-bill-to-protect-individuals-and-creators-from-deepfakes-passes-senate-judiciary-committee).

Those protections need a practical way for people to express their choices and for machines to interpret them. That is the infrastructure I’m designing through OCG, available to Creators whether they have two thousand followers or two million.

I designed the consent model around a distinction: **being discoverable should not require agreeing to AI training or a synthetic version of yourself.** Creators can declare choices for their name, image, likeness, voice, movement and signature. Unclaimed records express no consent on their behalf. Silence is not permission.

My research into consent standards informs how those choices become machine-readable declarations. The implementation uses HCS within the RSL family, with supporting discovery and policy signals so systems can locate and interpret the terms.

[Consent model, declarations and worked examples](https://creatorgraph.sparkonomy.com/for-ai-and-search/)

### Make the declaration independently verifiable
The next question is evidence: can a Creator show what they declared, and when? OCG’s consent records are signed, logged and independently timestamped through an EU eIDAS qualified service. The purpose is to make later alteration detectable and provide evidence beyond Sparkonomy’s own account of events.

Under eIDAS, a qualified timestamp carries a presumption of accuracy of its date and time and integrity of the data it binds. It does not, by itself, establish ownership of every claimed right or guarantee a legal outcome.

[How qualified timestamps support evidence](https://ec.europa.eu/digital-building-blocks/sites/spaces/DIGITAL/pages/880312429/eSignature+FAQ)

### Test the problem, not just the idea
I also worked on **AMISS, our AI Misrepresentation Study**: 10,000 Creator profiles, 50,000 queries and five AI models. We checked answers against recorded social-platform data to examine factual accuracy, conflicting descriptions and whether web search helped.

The study grounds the identity problem in measured behaviour. It does not yet establish that OCG improves AI answers. Equally, publishing a consent declaration does not guarantee every AI provider will honour it. What we can offer today is a structured identity, an explicit statement of choices and a verifiable record of those choices over time.

[Explore AMISS](https://creatorgraph.sparkonomy.com/amiss/) · [Methodology and findings](https://creatorgraph.sparkonomy.com/amiss/study-summary.html)

**The goal is to make Creator identity reliable, consent readable and choices verifiable.**

## Before Sparkonomy

At Google/YouTube, I led growth in APAC and founded Google Ignition Labs. Earlier chapters included Microsoft and Samsung.

## Connect

[Try Sparkonomy](https://www.sparkonomy.com) · [LinkedIn](https://www.linkedin.com/in/guneets/) · [Sparkonomy on GitHub](https://github.com/sparkonomy)


**[Main Sparkonomy repository (private)](https://github.com/sparkonomy/sparkonomy)** · Access restricted to authorised collaborators.
