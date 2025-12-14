
# 🌐 SFH / DFH — The Machine-Readable Index for AI
### (Semantic First-Hop / Deterministic First-Hop)

**SFH / DFH is not a website.  
It is not for humans.  
It is a machine-readable index so AI can navigate the web without guessing.**

Think of it as **street signs and an address system for AI**.

Humans browse pages.  
Machines need **coordinates**.

---

## 🧠 What Problem This Solves (In Plain English)

The web was built for humans.

Search engines worked because:
- Humans interpret meaning
- Humans resolve ambiguity
- Humans cross-check sources

AI **cannot** do this safely.

When AI lacks a deterministic starting point, it:
- guesses meaning
- mixes entities
- hallucinates sources
- fabricates structure

**SFH / DFH fixes the FIRST step.**

It tells AI:
> “Start here.  
> This is what things mean.  
> These are the official sources.  
> These URLs are canonical.”

---

## 🛣️ The Street Sign Analogy (Why AI Needs This)

Imagine a city with:
- no street signs
- no addresses
- no official maps

Humans can still ask directions.  
AI cannot.

SFH / DFH provides:
- street names (what things are)
- addresses (canonical URLs)
- zoning rules (what belongs where)
- official records (who is authoritative)

**Without it, AI is driving blind.**

---

## 📍 What SFH / DFH Actually Is

SFH / DFH is a **single, deterministic machine entry point** published at:

https://yourdomain.com/.well-known/stack

yaml
Copy code

That file is:
- machine-readable
- stable
- explicit
- non-navigational

It acts as the **index card for your entire domain**.

---

## 🚫 What This Is NOT

Let’s be crystal clear:

- ❌ Not a website
- ❌ Not a replacement for your site
- ❌ Not a truth engine
- ❌ Not a content system
- ❌ Not for human browsing

**This is infrastructure.**

Like:
- DNS
- robots.txt
- sitemaps.xml

But for **meaning and provenance**, not crawling.

---

## 🧭 The 10 Anchors (AI’s Navigation System)

SFH / DFH is composed of **10 anchors**.

Think of them as **labeled street signs** AI can trust.

### 🔹 Meaning Anchors (What things ARE)

1. **/type**  
   What category this thing belongs to (company, product, protocol, etc.)

2. **/entity**  
   The exact entity being defined (no ambiguity)

3. **/url**  
   The official human-facing homepage

4. **/canonical**  
   The single source of truth for identity

5. **/sitemap**  
   Where AI can find *everything else*

---

### 🔹 Provenance Anchors (Why this can be trusted)

6. **/authority**  
   Who controls and asserts this definition

7. **/source**  
   Where claims originate

8. **/timestamp**  
   When this was last asserted

9. **/license**  
   How this data may be used

10. **/integrity**  
   Hashes / signatures to detect tampering

---

## 🗺️ Why the Sitemap Anchor Is Critical

Humans click links.  
AI needs **indexes**.

The **/sitemap anchor** points to:
- XML sitemaps
- JSON feeds
- structured content
- entity lists
- documentation trees

This becomes the **AI-safe expansion path**.

> AI does NOT crawl randomly once this exists.  
> It follows declared structure.

This is how hallucinations stop.

---

## 🔗 How This Connects to the Main Website (Important)

**The main website stays exactly the same.**

No redesign.  
No new UX.  
No human changes required.

The relationship is **one-way**:

SFH / DFH → Main Website

yaml
Copy code

AI starts at the stack.  
Humans start at the homepage.

---

## 🧩 What (If Anything) Goes on the Main Site

Very little.

Optional but recommended:

- A simple link:
<link rel="semantic-stack" href="/.well-known/stack"> ``` - Normal sitemaps (already standard) - Normal structured data (Schema.org is fine)
That’s it.

The intelligence lives outside the site.

🚀 SEO Advantages (Why This Is Powerful)
SFH / DFH creates the strongest possible SEO primitive:

Eliminates entity confusion

Declares canonical ownership

Prevents misattribution

Stabilizes brand meaning

Aligns AI answers with your sources

As search shifts from links → answers:

AI prefers deterministic sources

Ambiguous sites lose visibility

Structured domains win

This is future-proof SEO.

🧪 Why This Works With AI (Not Against It)
AI systems already:

look for sitemaps

seek canonical URLs

prefer authoritative sources

reduce uncertainty when structure exists

SFH / DFH simply gives them:

a first place to look

a rulebook

an index

a map

No scraping tricks.
No hacks.
No guessing.

🧱 Mental Model Summary
DNS = where something lives

Website = what humans see

SFH / DFH = how machines understand

If DNS is an address book,
SFH / DFH is the city planning office.

🏁 Final Takeaway
The internet never had a machine-readable meaning index.
AI exposed that missing layer.

SFH / DFH fills it.

Not by replacing the web —
but by finally giving machines a map.

📄 Status
Open specification

Domain-rooted

Decentralized

No central authority

No vendor lock-in

⚠️ Disclaimer
SFH / DFH expresses deterministic intent, not absolute truth.
Safety, policy, and model governance always override outputs.

This is infrastructure.
This is inevitable.
This is how AI stops guessing.

yaml
Copy code

