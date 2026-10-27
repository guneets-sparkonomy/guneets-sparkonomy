# Guneet Singh

**Founder of [Sparkonomy](https://www.sparkonomy.com) · Building AI products for Creators · Singapore**

*I’m building the infrastructure to make Creator identity discoverable through trusted information, with explicit permissions for what AI can and cannot do with it.*

After 20+ years across Google/YouTube, Microsoft and Samsung, I’m bringing together my experience in consumer technology, product growth and the Creator economy to build Sparkonomy.

## What we’re building

### Open Creator Graph (OCG)
A free, public identity and consent layer for Creators. It brings their social identities into one structured record, helps Search and AI understand who they are, and lets them declare how AI may use their identity.

### Creator Genome
Multimodal AI that turns a Creator’s content into deep context about their style, voice and work. This gives our agents a starting point for personalised help.

### AI business team
We’re building agents to help Creators with the work around their content: partnerships, planning, contracts, invoices and payments. Our earlier invoicing product was used by more than 2,500 Creators.

## My work on the Open Creator Graph (OCG)

**Creator identity should be discoverable through information AI can trust, with exact permissions for what AI can and cannot do with that identity.** My work on the Open Creator Graph brings those two needs together: trusted identity and explicit consent.

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

Under eIDAS, a qualified timestamp carries a presumption of the accuracy of its date and time and the integrity of the data it binds, providing evidence of what was declared and when.

[How qualified timestamps support evidence](https://ec.europa.eu/digital-building-blocks/sites/spaces/DIGITAL/pages/880312429/eSignature+FAQ)

### Measure how accurately AI represents Creators
I also worked on **AMISS, our AI Misrepresentation Study**, to examine how accurately Creators are represented by AI. The research starts from a gap: Creator information is scattered across platforms, without a consistent, structured identity record for AI to learn from or retrieve.

The main study tested **10,000 Creator profiles through 50,000 queries across five AI models**, comparing their answers with recorded social-platform data. A separate test used the same 1,000 Creators with and without web search across three models, examining whether grounding answers in search improved accuracy.

The purpose was to measure how reliably AI describes Creators from its existing knowledge and when grounded with search, including factual errors, conflicting descriptions and inaccurate audience figures.

[Explore AMISS](https://creatorgraph.sparkonomy.com/amiss/) · [Methodology and findings](https://creatorgraph.sparkonomy.com/amiss/study-summary.html)

**The goal: make Creator identity discoverable through trusted information, and give AI explicit permissions for what it can and cannot do with that identity.**

## Before Sparkonomy

At Google/YouTube, I led growth in APAC and founded Google Ignition Labs. Earlier chapters included Microsoft and Samsung.

## Connect

[Try Sparkonomy](https://www.sparkonomy.com) · [LinkedIn](https://www.linkedin.com/in/guneets/) · [Sparkonomy on GitHub](https://github.com/sparkonomy)


**[Main Sparkonomy repository (private)](https://github.com/sparkonomy/sparkonomy)** · Access restricted to authorised collaborators.
