---
title: Saying "Not Now" Without Losing Friends — Prioritization for the Solo Nonprofit PM
topic: Prioritization with scarce resources and saying no
audience: Sole product manager at a small nonprofit
last_verified: 2026-11-20
evidence_strength: Moderate — the research on fair process and on optimistic estimates is strong and peer-reviewed, but the scoring frameworks (RICE, cost of delay, Kano) rest mostly on practitioner experience, not controlled studies
---

# Saying "Not Now" Without Losing Friends — Prioritization for the Solo Nonprofit PM

> **In one paragraph:** When you are the only product person, almost every request is a good idea from someone you depend on: the Executive Director, a program lead, a funder, a board member. You cannot build them all, and pretending you can is how goodwill is actually lost, through missed promises. The way through is to make the choice visible: agree a few mission-tied criteria with your ED, score requests lightly (RICE, cost of delay, impact/effort), show the result on a Now / Next / Later roadmap, and explain every "not now" with the criteria. Research on fair process shows people accept decisions they dislike much better when the process was open and explained. The frameworks themselves are aids to conversation, not proofs, so treat the numbers as rough.

## Why this matters when you're the only PM

In a larger company, a PM team, a roadmap council, and a head of product absorb the pressure of saying no. In a small nonprofit, it's you. And the pressure is unusually personal: the person asking for a feature may be a volunteer who gives up Saturdays, or a funder whose grant pays part of your salary.

Your capacity is also thinner than it looks. Gregory and Howard's widely cited *Stanford Social Innovation Review* article describes a "nonprofit starvation cycle": funders expect low overhead, nonprofits underspend on systems, staff and technology, and then underreport what overhead really costs, which keeps expectations low [13]. Product and technology work usually sits in exactly that underfunded overhead. So the question is rarely "what should we build?" It is "which two or three things will we do well, and how do we keep everyone on side about the rest?"

There is also a real cost to saying yes too often. Melissa Perri calls it the "build trap": an organization measures success by outputs (features shipped) instead of outcomes (lives changed, hours saved) [7]. Vendor data points the same way: Pendo's analysis of 615 software products found that 80% of features were rarely or never used [8]. Treat that number as indicative, not exact (see "Where this advice breaks down"), but the direction is clear. Every feature you add has to be maintained by the same one person.

## Practical advice

**1. Write down three to five mission-tied criteria with your ED, before the next request arrives.**
Criteria agreed in advance turn "I don't like your idea" into "here is how it scores against what we agreed." Marty Cagan argues that teams should be given prioritized objectives and the problem to solve, not a list of features, because "it is all about outcome rather than output" [5]. Perri makes the same case [7]. For a nonprofit, criteria might be: (a) direct benefit to clients, (b) staff hours saved, (c) funder or legal obligation, (d) risk if we don't do it, (e) effort. Get your ED to sign off on them and share them with the board. Now when a request comes in, it's being judged by rules that were set before anyone knew whose idea it was.

**2. Score requests with a light framework, and say out loud that it's rough.**
RICE, from Sean McBride at Intercom, scores an idea as (Reach × Impact × Confidence) ÷ Effort [1]. In nonprofit terms: Reach = how many clients or staff are affected per quarter; Impact = a 0.25–3 scale; Confidence = how sure you are (50–100%); Effort = person-months, including volunteer developer time. McBride himself says the scores "shouldn't be used as a hard and fast rule" [1]; their value is that they make trade-offs explicit. A simpler impact/effort 2×2 on a whiteboard is often enough for a team of eight.

**3. Ask "what does waiting cost?" for anything time-sensitive.**
Cost of delay asks how much value is lost for each week something is not done; dividing it by duration (CD3) helps you put short, urgent work first [2]. Black Swan Farming quotes Don Reinertsen calling cost of delay a "golden key that unlocks many doors" [2]. This is the right lens for funder deadlines, compliance dates, and seasonal programs (a tax-clinic intake form is worth far more in January than in May). It is also a kind way to say no to a pet project: "this is valuable, but nothing is lost by doing it in spring, whereas the intake form loses value every week."

**4. Use Kano thinking to separate "must work" from "would delight."**
Kano and colleagues showed in 1984 that features don't affect satisfaction in a straight line: some are "must-be" (people are only unhappy when they're missing, like a donation receipt that works), while others are "attractive" (delightful, but nobody complains when they're absent) [3]. For you this means: fix the broken must-bes (the volunteer sign-up that drops entries) before building delighters (a gamified volunteer leaderboard). Use the categories as a way of thinking. The formal Kano questionnaire is more than most small teams need, and researchers disagree about how reliably its classification methods work [4].

**5. Make your roadmap a communication tool: Now / Next / Later.**
Janna Bastow (ProdPad) created the Now-Next-Later format because dated roadmaps create false precision and endless renegotiation [6]. "Now" is committed and detailed; "Next" is likely but flexible; "Later" holds problems you know about but haven't solved. This is ideal for saying no gently: most requests go into "Later" with a one-line reason, rather than disappearing. Put the roadmap on one page and share it at staff meetings and in the board packet. Cagan adds a useful rule: when someone genuinely needs a date (a grant report), make a specific, deliberate commitment for that item only [5].

**6. Explain every "no" with the criteria, and invite challenge.**
This is the core of keeping goodwill. Kim and Mauborgne's *Harvard Business Review* research on "fair process" found that people commit to decisions they disagree with if they believe the process was fair, built on three things: engagement (asking for input), explanation (saying why), and clear expectations (what happens next) [9]. Brockner and Wiesenfeld's review of 45 samples in *Psychological Bulletin* (cited over 1,300 times) found that a fair process matters most precisely when the outcome is unfavorable to the person [10]. In practice, a good "not now" message has four parts: thanks plus the problem as you heard it; how it scored and what beat it; where it now sits (Next or Later) and what would move it up; and an invitation to tell you what you've missed.

**7. Treat funder-driven feature requests as a scope conversation, not an order.**
Funding sources pull on an organization in different ways. Froelich's much-cited review in *Nonprofit and Voluntary Sector Quarterly* compares revenue strategies on, among other things, "goal displacement" [14], and the starvation-cycle research shows how funder expectations shape what nonprofits can afford to build [13]. When a funder asks for a dashboard or a new data field, run it through the same criteria. Then talk to your ED and development lead about the options: build it and fund it in the grant budget, meet the need more simply (a quarterly spreadsheet export), or negotiate it out. Never quietly absorb unfunded work. Show what it would push off the roadmap.

**8. Handle the ED's pet project with the same process, privately first.**
Your ED holds both the authority and the relationship with the board, so don't surprise them in public. Score the idea with them one-on-one, show what it would displace on the Now column, and offer a small, cheap test ("let's try it with five families for a month"). Sometimes it should win: the ED may know about a funder shift or board priority you don't. The point is that the trade-off is visible and decided on purpose.

**9. Pad your effort estimates, because everyone underestimates.**
The planning fallacy is one of the most robust findings in psychology. Buehler, Griffin and Ross showed that people consistently underestimate how long their own tasks will take [11], and Buehler's later summary recommends the "outside view": compare against how long similar past work actually took [11]. Since effort is the denominator in RICE and CD3, optimistic estimates quietly inflate every score. Keep a simple log of estimated against actual time and use it.

## Try this in the next two weeks

- [ ] Draft three to five prioritization criteria and agree them with your ED in a 30-minute meeting.
- [ ] Put every open request into a single list (one spreadsheet is fine) with requester, problem, and date.
- [ ] Score the top 10–15 with RICE or impact/effort; mark confidence honestly.
- [ ] Ask "what does waiting cost?" for anything with a deadline.
- [ ] Publish a one-page Now / Next / Later roadmap and share it at the next staff meeting.
- [ ] Send two "not now" replies using the four-part structure in point 6.
- [ ] Start an estimated-against-actual time log for your next three pieces of work.

## Where this advice breaks down

- **Scores look more precise than they are.** No controlled study shows RICE beats judgment. Jason Cohen argues that "confidence" can't be defined or checked and tends to bias teams toward small, safe projects [12]. Use scores to structure discussion, not to settle it.
- **Some decisions aren't yours to score.** Legal requirements, safeguarding, and restricted-grant deliverables often go straight to "Now." Say so openly instead of pretending they were scored.
- **Kano methods are contested.** Mikulić and Prebežac's review found the classification techniques vary in validity and reliability [4]. The broad must-be / delighter idea is useful; precise survey-based Kano classification is probably overkill for a tiny team.
- **The feature-waste figure is vendor data.** Pendo's 80% comes from its own customers' tagged features over three months [8]. It supports "build less, measure use" but shouldn't be quoted as a universal fact.
- **Fair process isn't a guarantee.** Brockner and Wiesenfeld report that fair process softens reactions to unfavorable outcomes; it doesn't eliminate them [10]. Some funders and board members will still be unhappy, and your ED may still overrule you. That is legitimate, and your job then is to record the trade-off and make it work.
- **Most of these frameworks come from software companies.** Cagan, Bastow, Intercom and Perri write mainly for commercial tech teams with engineers on staff [1][5][6][7]. In a nonprofit with volunteer developers or off-the-shelf tools, "effort" may mean vendor cost or staff training time, and "reach" should count clients served, not users.

## Evidence check

| Claim | Supporting sources | Qualifying / contrary evidence | Verdict |
|---|---|---|---|
| Explaining decisions through a fair, open process preserves commitment even when the answer is no | Kim & Mauborgne, HBR [9]; Brockner & Wiesenfeld, *Psych. Bulletin* meta-review [10] | Softens but doesn't remove negative reactions [10] | Strong — keep |
| Agree outcome-based criteria and prioritize problems, not features | Cagan [5]; Perri [7]; Bastow [6] | Practitioner sources from commercial tech, not controlled research | Moderate — keep, adapt to nonprofit outcomes |
| RICE / impact-effort scoring helps make trade-offs visible | McBride/Intercom [1]; Black Swan Farming on CD3 [2] | Cohen: confidence scores are ill-defined and bias toward safe bets [12]; McBride: not a hard rule [1] | Qualified — use as a conversation aid only |
| Cost of delay helps sequence time-sensitive work | Black Swan Farming/Reinertsen [2]; Bastow's horizon thinking [6] | Estimating value per week is guesswork in mission work | Moderate — keep for deadline-driven items |
| Separate must-be features from delighters (Kano) | Kano et al. 1984 [3] | Classification techniques vary in validity/reliability [4] | Qualified — use the concept, skip the formal survey |
| Many built features go unused, so say no more often | Pendo 2019 report [8]; Perri's build trap [7] | Vendor sample of 615 SaaS products, tagged features only [8] | Qualified — directional only |
| Effort estimates are systematically optimistic | Buehler et al. 1994 (1,100+ citations) and Buehler's 2019 summary [11]; Cohen on unreliable estimates [12] | Remedies (outside view) reduce but don't remove bias [11] | Strong — keep |
| Nonprofit product capacity is structurally thin and funder-shaped | Gregory & Howard, SSIR [13]; Froelich, NVSQ [14] | Froelich's full text not accessed; claim limited to its abstract (revenue sources differ in goal-displacement effects) | Moderate — keep, stated cautiously |

## Sources

1. McBride, Sean. *RICE: Simple prioritization for product managers*. Intercom blog, 2018. https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/ — **Why trusted:** The original description of RICE by the person who developed it at Intercom; the framework is now standard in PM tooling and courses. Verified content and the "hard and fast rule" caveat.
2. Black Swan Farming. *Cost of Delay*. https://blackswanfarming.com/cost-of-delay/ — **Why trusted:** Widely referenced practitioner resource on cost of delay and CD3; quotes Don Reinertsen, whose *Principles of Product Development Flow* popularized the idea. Verified the definition of CD3 and the Reinertsen quote; the page does not name an individual author.
3. Kano, Noriaki; Seraku, Nobuhiko; Takahashi, Fumio; Tsuji, Shin-ichi. *Attractive Quality and Must-Be Quality*. Journal of the Japanese Society for Quality Control (Hinshitsu), 14(2), 147–156, 1984. https://www.jstage.jst.go.jp/article/quality/14/2/14_KJ00002952366/_article/-char/en — **Why trusted:** The original peer-reviewed Kano model paper. Verified the abstract (two-dimensional quality, attractive vs. must-be) on J-STAGE; full text is restricted.
4. Mikulić, Josip; Prebežac, Darko. *A critical review of techniques for classifying quality attributes in the Kano model*. Managing Service Quality, 21(1), 46–66, 2011. https://doi.org/10.1108/09604521111100243 — **Why trusted:** Peer-reviewed; about 363 citations (Semantic Scholar). Verified bibliographic details and abstract findings via search; full text paywalled.
5. Cagan, Marty. *The Alternative to Roadmaps*. Silicon Valley Product Group, 2015. https://www.svpg.com/the-alternative-to-roadmaps/ — **Why trusted:** Cagan is the author of *Inspired* and one of the most widely read voices in product management. Verified the outcome-over-output argument and "high-integrity commitments."
6. ProdPad (Janna Bastow). *Why I invented the Now-Next-Later roadmap*. ProdPad blog. https://www.prodpad.com/blog/invented-now-next-later-roadmap/ — **Why trusted:** First-hand account from the format's creator; Now-Next-Later is widely adopted. Verified the three horizons and the rationale against timeline roadmaps.
7. Perri, Melissa. *Escaping the Build Trap: How Effective Product Management Creates Real Value*. O'Reilly, 2018. https://www.goodreads.com/work/quotes/66322411 — **Why trusted:** Widely recommended PM book; Goodreads showed about 5,100 ratings, 4.27 average, when checked. Verified the outputs-vs-outcomes definition of the build trap.
8. Pendo. *The 2019 Feature Adoption Report*. Pendo, 2019. https://www.pendo.io/resources/the-2019-feature-adoption-report/ — **Why trusted:** Large usage dataset (615 subscriptions, three months), widely cited in PM writing (e.g. Mind the Product). Vendor-produced, so used only directionally. Verified the 80% figure and methodology.
9. Kim, W. Chan; Mauborgne, Renée. *Fair Process: Managing in the Knowledge Economy*. Harvard Business Review (originally 1997; reprinted 2003 and in a 2023 HBR special issue). https://www.insead.edu/faculty-research/publications/journal-articles/fair-process-managing-knowledge-economy-reprint — **Why trusted:** HBR article by INSEAD professors (authors of *Blue Ocean Strategy*), included in HBR's "10 Must Reads." Verified the core finding on the INSEAD page; the hbr.org original returned 404.
10. Brockner, Joel; Wiesenfeld, Batia M. *An integrative framework for explaining reactions to decisions: Interactive effects of outcomes and procedures*. Psychological Bulletin, 120(2), 189–208, 1996. https://doi.org/10.1037/0033-2909.120.2.189 — **Why trusted:** Peer-reviewed review of 45 samples; about 1,376 citations (Semantic Scholar). Verified citation and citation count; abstract findings confirmed via search summaries (full text was a scanned PDF I could not read).
11. Buehler, Roger; Griffin, Dale; Ross, Michael. *Exploring the "planning fallacy": Why people underestimate their task completion times*. Journal of Personality and Social Psychology, 67(3), 366–381, 1994. https://doi.org/10.1037/0022-3514.67.3.366 ; with Buehler, R. *The Planning Fallacy*, SPSP Character & Context blog, 2019. https://spsp.org/news-center/blog/buehler-planning-fallacy — **Why trusted:** Peer-reviewed; about 1,181 citations (Semantic Scholar). The author's own 2019 summary (verified) describes the bias as robust and recommends the outside view.
12. Cohen, Jason. *Lost confidence*. A Smart Bear, 2026. https://longform.asmartbear.com/confidence/ — **Why trusted:** Long-running, widely read founder and product blog. Used as counter-evidence on RICE confidence scores. Verified.
13. Gregory, Ann Goggins; Howard, Don. *The Nonprofit Starvation Cycle*. Stanford Social Innovation Review, Fall 2009. https://ssir.org/articles/entry/the_nonprofit_starvation_cycle — **Why trusted:** Widely cited article on nonprofit overhead in SSIR, a leading practitioner journal for the social sector. Verified the cycle and its consequences for technology and staff.
14. Froelich, Karen A. *Diversification of revenue strategies: Evolving resource dependence in nonprofit organizations*. Nonprofit and Voluntary Sector Quarterly, 28(3), 246–268, 1999. https://doi.org/10.1177/0899764099283002 — **Why trusted:** Peer-reviewed in the leading nonprofit studies journal; about 915 citations (Semantic Scholar). Only the abstract was verifiable (via search); used narrowly.

## AI study prompt

Copy this into your AI assistant to test and deepen what you've learned.

```text
I just read an article on prioritization with scarce resources and saying "no" or "not now" without losing goodwill. I am the only product manager at a small nonprofit (few staff, limited budget, I report to an Executive Director, we have a board, we serve clients, and we depend on donors and funders).

Key ideas from the article:
1. Agree three to five mission-tied prioritization criteria with the ED in advance (e.g. client benefit, staff hours saved, funder/legal obligation, risk of not doing it, effort), so requests are judged by rules set before anyone knows whose idea it is.
2. Use light scoring frameworks as conversation aids, not proofs: RICE = (Reach x Impact x Confidence) / Effort; impact/effort 2x2; its creator says it is not a hard and fast rule, and critics say confidence scores are ill-defined and favor safe bets.
3. Cost of delay: ask what value is lost per week of waiting; dividing by duration (CD3) puts short, urgent work first. Good for funder deadlines and seasonal programs.
4. Kano thinking: fix "must-be" features (whose absence causes complaints) before "attractive" delighters; formal Kano classification methods are contested.
5. Now / Next / Later roadmaps (Janna Bastow) avoid false date precision; most requests go into Next or Later with a reason rather than vanishing. Make specific commitments only where a date is truly needed.
6. Fair process (Kim & Mauborgne; Brockner & Wiesenfeld): people accept unfavorable decisions better when there is engagement, explanation, and clear expectations. A good "not now" = thanks and the problem as heard; how it scored and what beat it; where it sits now and what would move it up; an invitation to challenge.
7. Funder-driven requests are a scope conversation: fund it, meet the need more simply, or negotiate it out; never absorb unfunded work silently. Nonprofit capacity is thin because of the "nonprofit starvation cycle."
8. ED pet projects: discuss privately first, show what they would displace, offer a small test; sometimes the ED should win, and the trade-off should be visible.
9. The planning fallacy: people underestimate their own task times, so use the "outside view" (past actuals) and keep an estimated-vs-actual log.
10. Avoid the "build trap" (measuring outputs, not outcomes); vendor data suggests many features go unused, but treat that figure as directional.

Please quiz me:
- Ask ONE question at a time and wait for my answer before continuing.
- Mix three types: recall (what does a concept mean), application (apply a framework to a short scenario you describe), and "what would you do" judgment calls.
- After each answer, give me feedback, then a model answer with your reasoning.
- Adapt difficulty: harder if I'm doing well, simpler and more scaffolded if I'm struggling.
- Include at least one scenario involving all three of: the Executive Director, a board member, and a program staff member with competing requests.
- Include at least one scenario with a funder asking for a new feature or report.
- After about 8 to 10 questions, end with a summary of my strengths, my gaps, and 3 concrete follow-up actions I can take at work in the next two weeks.
- If you are unsure about a fact, a source, or what a framework's author said, say so plainly rather than inventing details, statistics, or quotes.
```
