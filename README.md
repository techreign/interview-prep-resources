# Interview Prep Resources

A curated list of free interview prep resources organized by company. Covers coding practice, system design, behavioral prep, books, YouTube channels, and community forums.

This list is structured BY COMPANY rather than by resource type, so you can quickly find everything relevant to your target employer in one place.

---

## Table of Contents

- [How to use this list](#how-to-use-this-list)
- [Where to find leaked and reported questions](#where-to-find-leaked-and-reported-questions)
- [FAANG and Big Tech](#faang-and-big-tech)
  - [Google](#google)
  - [Amazon](#amazon)
  - [Meta](#meta)
  - [Microsoft](#microsoft)
  - [Apple](#apple)
  - [Netflix](#netflix)
- [High-Growth Tech](#high-growth-tech)
  - [Stripe](#stripe)
  - [Uber](#uber)
  - [Airbnb](#airbnb)
  - [Snowflake](#snowflake)
  - [OpenAI / Anthropic](#openai--anthropic)
  - [Databricks](#databricks)
- [Finance and Trading](#finance-and-trading)
  - [Jane Street](#jane-street)
  - [Citadel](#citadel)
  - [Two Sigma](#two-sigma)
  - [Goldman Sachs](#goldman-sachs)
  - [JPMorgan Chase](#jpmorgan-chase)
- [General Resources (All Companies)](#general-resources-all-companies)
  - [Coding practice](#coding-practice)
  - [System design](#system-design)
  - [Behavioral prep](#behavioral-prep)
  - [Books](#books)
  - [YouTube channels](#youtube-channels)
  - [Communities and forums](#communities-and-forums)
- [Contributing](#contributing)
- [License](#license)

---

## How to use this list

1. Find your target company in the table of contents.
2. Work through the company-specific resources first -- past questions and process notes from real candidates are the highest-signal prep you can do.
3. Fill gaps with the general resources at the bottom.
4. For the largest database of real reported questions across all these companies, [search on LeakCode](https://leakcode.dev) -- it aggregates 59,970 questions from 2,000+ employers across 7 sources including 1Point3Acres, Blind, and Glassdoor.

---

## Where to find leaked and reported questions

Real interview questions reported by past candidates are the most valuable prep material. Here is where to find them:

| Source | What you get | Cost |
|--------|-------------|------|
| [LeakCode interview question database](https://leakcode.dev) | 59,970 questions from 2,000+ companies, aggregated from 1Point3Acres, Blind, Glassdoor, Reddit, LeetCode Premium, and more. Translated, deduplicated, searchable. | Free preview, premium for full access |
| [1Point3Acres](https://1point3acres.com) | Large forum for Chinese-speaking engineers; heaviest coverage of FAANG and quant firms | Paywalled |
| [Blind](https://teamblind.com) | Anonymous posts from verified employees; good for process and experience reports | Free with phone verification |
| [Glassdoor](https://glassdoor.com) | Interview reviews with question snippets | Free with account |
| [Reddit r/cscareerquestions](https://reddit.com/r/cscareerquestions) | Experience threads, company-specific posts | Free |
| [Reddit r/leetcode](https://reddit.com/r/leetcode) | OA problems, specific question threads | Free |

LeakCode pulls all of the above into one searchable database, so you do not have to check each source separately.

---

## FAANG and Big Tech

### Google

**Reported questions:**
- [LeakCode: Google interview questions](https://leakcode.dev/company/google) -- 6,019 questions in the LeakCode database, spanning SWE, ML, and data roles
- [Glassdoor: Google Software Engineer interviews](https://www.glassdoor.com/Interview/Google-Software-Engineer-Interview-Questions-EI_IE9079.0,6_KO7,24.htm)
- [r/cscareerquestions: Google interview thread](https://www.reddit.com/r/cscareerquestions/search/?q=google+interview&sort=new)

**Process guides:**
- [Google's official hiring process overview](https://careers.google.com/how-we-hire/)
- [Tech Interview Handbook: Google](https://www.techinterviewhandbook.org/companies/google/)

**Topic emphasis:**
Google rounds lean heavily on algorithms (graphs, trees, dynamic programming), system design for senior roles, and Googleyness/leadership behavioral rounds. Phone screen is typically 45 min coding; onsite is 5 rounds (4 coding/design + 1 behavioral).

---

### Amazon

**Reported questions:**
- [LeakCode: Amazon interview questions](https://leakcode.dev/company/amazon) -- 8,227 questions, the largest single-company dataset in the LeakCode database
- [Glassdoor: Amazon SDE interviews](https://www.glassdoor.com/Interview/Amazon-Software-Development-Engineer-Interview-Questions-EI_IE6036.0,6_KO7,36.htm)
- [r/leetcode: Amazon OA problems](https://www.reddit.com/r/leetcode/search/?q=amazon+OA)

**Process guides:**
- [Amazon's leadership principles (LP) list](https://www.amazon.jobs/content/en/our-workplace/leadership-principles) -- every behavioral round maps to one of these
- [Tech Interview Handbook: Amazon](https://www.techinterviewhandbook.org/companies/amazon/)

**Topic emphasis:**
Amazon is behaviorally heavy. Every round includes at least one LP story. Coding skews toward arrays, trees, and graph problems. System design appears for L5+. OA is common for new grad: two coding problems under 90 minutes.

---

### Meta

**Reported questions:**
- [LeakCode: Meta interview questions](https://leakcode.dev/company/meta) -- 4,711 questions in the LeakCode database
- [Glassdoor: Meta Software Engineer interviews](https://www.glassdoor.com/Interview/Meta-Software-Engineer-Interview-Questions-EI_IE40772.0,4_KO5,22.htm)

**Process guides:**
- [Meta Engineering Blog: interviewing at Meta](https://engineering.fb.com/tag/interviews/)
- [Tech Interview Handbook: Meta](https://www.techinterviewhandbook.org/companies/meta/)

**Topic emphasis:**
Meta coding rounds focus heavily on arrays, strings, and trees. System design is expected for E5+. Behavioral round uses the "Why Meta" and core values framework. Recruiters often send a study guide with specific topic weightings.

---

### Microsoft

**Reported questions:**
- [LeakCode: Microsoft interview questions](https://leakcode.dev/company/microsoft) -- 3,116 questions in the LeakCode database
- [Glassdoor: Microsoft SDE interviews](https://www.glassdoor.com/Interview/Microsoft-Software-Design-Engineer-Interview-Questions-EI_IE1651.0,9_KO10,34.htm)

**Process guides:**
- [Tech Interview Handbook: Microsoft](https://www.techinterviewhandbook.org/companies/microsoft/)

**Topic emphasis:**
Microsoft rounds cover OOP design, coding (trees/graphs/strings), and a "As Appropriate" (AA) final round with a senior leader that is heavily behavioral. Less algorithm-competitive than Google, more practical coding and design.

---

### Apple

**Reported questions:**
- [LeakCode: Apple interview questions](https://leakcode.dev/company/apple) -- part of the LeakCode database
- [Glassdoor: Apple Software Engineer interviews](https://www.glassdoor.com/Interview/Apple-Software-Engineer-Interview-Questions-EI_IE1138.0,5_KO6,23.htm)

**Topic emphasis:**
Apple interviews vary heavily by team. Expect deep system-level questions for OS/core teams, and standard algorithms for app-layer teams. Typically 5-6 rounds onsite. Values alignment matters.

---

### Netflix

**Reported questions:**
- [LeakCode: Netflix interview questions](https://leakcode.dev/company/netflix) -- part of the LeakCode database
- [Glassdoor: Netflix Software Engineer interviews](https://www.glassdoor.com/Interview/Netflix-Software-Engineer-Interview-Questions-EI_IE11891.0,7_KO8,25.htm)

**Process guide:**
- [Netflix culture memo](https://jobs.netflix.com/culture) -- extremely important to read before interviewing; Netflix selects strongly on culture fit

**Topic emphasis:**
Netflix is known for a heavy culture/values screen. Technical bar is high but not as LeetCode-grind-focused as Google. System design for backend roles is substantial. A lot of their questions center on "what would you do if..."

---

## High-Growth Tech

### Stripe

**Reported questions:**
- [LeakCode: Stripe interview questions](https://leakcode.dev/company/stripe) -- part of the LeakCode database
- [Glassdoor: Stripe Software Engineer interviews](https://www.glassdoor.com/Interview/Stripe-Software-Engineer-Interview-Questions-EI_IE671932.0,6_KO7,24.htm)

**Topic emphasis:**
Stripe does a take-home project (a small system you build against their API or a simulated one) before the onsite. The onsite tends toward practical coding rather than whiteboard puzzles. Expect questions about payments, distributed systems, and API design. See the [LeakCode Stripe page](https://leakcode.dev/company/stripe) for reported rounds.

---

### Uber

**Reported questions:**
- [LeakCode: Uber interview questions](https://leakcode.dev/company/uber) -- part of the LeakCode database

**Topic emphasis:**
Uber rounds focus on coding (graphs and maps problems show up frequently due to the domain), system design (real-time dispatch, geospatial indexing), and behavioral. New grad track is heavy on OA.

---

### Airbnb

**Reported questions:**
- [Glassdoor: Airbnb Software Engineer interviews](https://www.glassdoor.com/Interview/Airbnb-Software-Engineer-Interview-Questions-EI_IE391850.0,6_KO7,24.htm)

**Topic emphasis:**
Airbnb includes a design exercise (design a feature or product) alongside standard coding. Core values alignment is evaluated explicitly.

---

### Snowflake

**Reported questions:**
- [LeakCode: Snowflake interview questions](https://leakcode.dev/company/snowflake) -- part of the LeakCode database

**Topic emphasis:**
Snowflake is known for a difficult coding bar, SQL/database design, and system design for distributed data systems. Behavioral rounds use Amazon-style LP stories.

---

### OpenAI / Anthropic

**Reported questions:**
- [LeakCode: OpenAI interview questions](https://leakcode.dev/company/openai) -- part of the LeakCode database

**Topic emphasis:**
Both companies look for strong fundamentals plus ML systems knowledge for most roles. Research roles have a separate track. Expect coding, system design (ML infra), and research discussions for applied scientist tracks.

---

### Databricks

**Reported questions:**
- [Glassdoor: Databricks Software Engineer interviews](https://www.glassdoor.com/Interview/Databricks-Software-Engineer-Interview-Questions-EI_IE1090376.0,10_KO11,28.htm)

**Topic emphasis:**
Databricks rounds cover distributed systems heavily, Spark/data engineering concepts for data roles, and standard algorithms. Known for thorough system design rounds.

---

## Finance and Trading

### Jane Street

**Resources:**
- [Jane Street: about the interview process](https://www.janestreet.com/join-jane-street/process-and-interviews/)
- [Jane Street puzzles archive](https://www.janestreet.com/puzzles/) -- monthly puzzles published publicly, good calibration for their reasoning style

**Topic emphasis:**
Jane Street interviews are math and probability heavy, not LeetCode-style. Expect combinatorics, probability puzzles, and market-making scenarios. Coding rounds are in OCaml for research/trading roles.

---

### Citadel

**Reported questions:**
- [LeakCode: Citadel interview questions](https://leakcode.dev/company/citadel) -- part of the LeakCode database

**Topic emphasis:**
Citadel SWE and quantitative researcher roles have separate tracks. SWE is C++ heavy and systems-focused. Quant is probability, statistics, and brainteasers. Coding OAs are common for campus recruiting.

---

### Two Sigma

**Topic emphasis:**
Two Sigma is heavy on algorithms and data structures for SWE (think competitive programming level), and probability/statistics for quant roles. Multiple technical rounds plus a culture interview.

---

### Goldman Sachs

**Reported questions:**
- [LeakCode: Goldman Sachs interview questions](https://leakcode.dev/company/goldman-sachs) -- part of the LeakCode database

**Topic emphasis:**
Goldman SWE rounds cover algorithms, OOP design, and a division-specific technical screen. Technology Division roles are closer to standard SWE interviews; IBD/strats roles are more finance-specific.

---

### JPMorgan Chase

**Reported questions:**
- [LeakCode: JPMorgan interview questions](https://leakcode.dev/company/jpmorgan) -- part of the LeakCode database

**Topic emphasis:**
JPMorgan SWE interviews include HackerRank OAs for campus roles and panel interviews for experienced hires. OOP design and SQL show up more often than at pure tech companies.

---

## General Resources (All Companies)

### Coding practice

| Resource | Notes | Cost |
|----------|-------|------|
| [LeetCode](https://leetcode.com) | Largest problem bank; company-specific problem lists | Free tier + premium |
| [NeetCode 150](https://neetcode.io/practice) | Curated 150 problems with video solutions | Free |
| [Codeforces](https://codeforces.com) | Competitive programming; calibrates upper-end algorithmic difficulty | Free |
| [HackerRank](https://hackerrank.com) | Used for many OAs; practice in the same environment | Free |
| [AlgoExpert](https://algoexpert.io) | 170 handpicked problems with quality explanations | Paid |
| [Exercism](https://exercism.org) | Language-specific problem tracks with mentorship | Free |

### System design

| Resource | Notes | Cost |
|----------|-------|------|
| [System Design Primer (GitHub)](https://github.com/donnemartin/system-design-primer) | Most-starred system design resource on GitHub | Free |
| [ByteByteGo](https://bytebytego.com) | Visual system design explanations, covers all major interview topics | Free newsletter + paid book |
| [Designing Data-Intensive Applications](https://dataintensive.net) | Best technical book for understanding distributed systems at depth | Paid book |
| [Grokking System Design](https://www.educative.io/courses/grokking-the-system-design-interview) | Structured course on common design problems | Paid |
| [High Scalability blog](http://highscalability.com) | Real architecture breakdowns from companies | Free |
| [AI Agent Run Inspector](https://frontendatlas.com/system-design/ai-agent-run-inspector) | Frontend system-design exercise covering out-of-order trace events, stream reconnection, and human-approval races | Free question + full reference answer |

### Behavioral prep

| Resource | Notes | Cost |
|----------|-------|------|
| [STAR Method guide](https://www.indeed.com/career-advice/interviewing/how-to-use-the-star-interview-response-technique) | Standard framework for structuring behavioral answers | Free |
| [Amazon LP stories workbook](https://www.amazon.jobs/content/en/our-workplace/leadership-principles) | Official LP list; write one story per principle | Free |
| [Exponent behavioral prep](https://www.tryexponent.com/courses/behavioral) | Video walkthroughs with example answers | Free samples + paid |
| [Tech Interview Handbook: behavioral](https://www.techinterviewhandbook.org/behavioral-interview/) | Free structured guide with company-specific tips | Free |

### Books

| Book | Best for |
|------|----------|
| Cracking the Coding Interview (McDowell) | Broad coding interview prep, especially for FAANG |
| Elements of Programming Interviews | Harder problems, multiple language editions |
| Designing Data-Intensive Applications (Kleppmann) | System design depth |
| A Philosophy of Software Design (Ousterhout) | Code quality, design sensibility |
| The Pragmatic Programmer | General engineering craft |

### YouTube channels

| Channel | Focus |
|---------|-------|
| [NeetCode](https://youtube.com/@NeetCode) | LeetCode walkthroughs, clear explanations |
| [Tech Dummies (Narendra L)](https://youtube.com/@TechDummiesNarendraL) | System design walkthroughs |
| [Gaurav Sen](https://youtube.com/@gkcs) | System design, distributed systems concepts |
| [TechLead](https://youtube.com/@TechLead) | FAANG interview experience, process insights |
| [Clément Mihailescu](https://youtube.com/@clem) | AlgoExpert founder, interview mindset |
| [ByteByteGo](https://youtube.com/@ByteByteGo) | Visual system design, extremely high production value |

### Communities and forums

| Community | What you get |
|-----------|-------------|
| [r/cscareerquestions](https://reddit.com/r/cscareerquestions) | Experience reports, salary data, advice threads |
| [r/leetcode](https://reddit.com/r/leetcode) | OA problems, specific question threads, weekly discussion |
| [Blind](https://teamblind.com) | Verified employee posts, comp transparency, process reports |
| [Levels.fyi](https://levels.fyi) | Compensation data by company and level |
| [LeakCode](https://leakcode.dev) | Aggregated reported questions from all sources above, searchable |

---

## Contributing

Pull requests are welcome. To add a resource:

1. Verify the link is live and the content is genuinely useful.
2. Add it to the correct company section or general category.
3. Include a one-line description of what the resource offers.
4. Keep the table format consistent.

Please do not add resources that require a paid subscription without noting the cost in the table.

---

## License

This list is licensed under [CC-BY-SA-4.0](LICENSE). You are free to share and adapt the content as long as you give attribution and share under the same license.

Data on reported questions in the LeakCode database was sourced from the [LeakCode interview question database](https://leakcode.dev) and is used here for reference counts only.
