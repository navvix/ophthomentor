# Freemium vs Free Trial vs No-Free, and Three-Tier (Good/Better/Best) Pricing: Scientific and Industry Evidence (as of Oct 2026)

Scope note: notes compiled for a reader launching an educational question bank with Free / Core / Infinite tiers. Evidence is drawn from peer-reviewed journals (Management Science, Marketing Science, Journal of Marketing, ISR, JMIS, MISQ, JMR, SMJ, SEJ, IJIM, P&M), SEC filings, and large-sample industry benchmark studies. Where a source is an aggregator or a working-paper version rather than the published article, this is flagged. Where I could not find a figure, it is listed under Gaps rather than invented.

---

## Key Question 1: What do peer-reviewed studies say about freemium? (design, sample, key quantitative finding per study)

### Takeaway
The academic literature does not say "freemium good" or "freemium bad": it says freemium is optimal under specific conditions (network effects/word of mouth, low marginal cost, heterogeneous willingness to pay, consumer uncertainty about quality) and that its central design problem is a tension between the value of the free tier (which drives acquisition and referral) and premium conversion (which the free tier's value directly suppresses). The best-identified causal studies (field experiments and natural experiments) find that a free version typically *increases* paid demand in app and publishing settings, but that freemium products in competitive markets without network effects earn less than premium-only products.

### Cited Findings

**Kumar (2014), "Making 'Freemium' Work", Harvard Business Review, May 2014** — conceptual/practitioner article based on HBS research.
- Typical freemium conversion rates are 2–5%; "a free user is typically worth 15% to 25% as much as a premium subscriber, with significant value stemming from referrals" (HBS ongoing research cited in the article). Full article body is paywalled; figures are relayed via a secondary summary — [DBS summary of Kumar/HBR](https://www.dbs.com.sg/sme/businessclass/articles/strategy-and-outlook/conversion-rate.page); article landing page — [HBR](https://hbr.org/2014/05/making-freemium-work)
- Kumar's argument on conversion rate as a diagnostic: a high conversion rate can signal that the free tier is too limited and is hampering acquisition; "a company would be better off monetizing 5% of 1,000,000 users than 20% of 100,000 subscribers" — [DBS summary of Kumar/HBR](https://www.dbs.com/in/sme/businessclass/articles/business-strategy/conversion-rate.page)

**Lee, Kumar & Gupta (HBS working paper, 2013 onward), "Designing Freemium: A Model of Consumer Usage, Upgrade, and Referral Dynamics"** — structural (Bayesian) model estimated on a panel from "a leading cloud-based storage service" (widely understood to be Dropbox).
- Research questions: how much value the free product should provide relative to premium given cannibalization; the right referral bonus; how sharing affects upgrade probability — [Wharton colloquium abstract](https://marketing.wharton.upenn.edu/wp-content/uploads/2016/10/Title-and-Abstract-Lee-Clarence-10-10-2013.pdf)
- Key quantitative result: "the value of free consumers is approximately $24 per year, and ... the existence of the referral program contributes to 65% of this value." Also: an asymmetry in upgrade-rate response to price increases vs decreases, and "contrary to the belief that more is better, we find the existence of an optimal incentive point for referrals" — [Wharton colloquium abstract](https://marketing.wharton.upenn.edu/wp-content/uploads/2016/10/Title-and-Abstract-Lee-Clarence-10-10-2013.pdf)
- Context: Dropbox's S-1 reportedly showed only about 4% of free users converted to paid — [Wall Street Prep (secondary)](https://wallstreetprep.com/knowledge/freemium)

**Gu, Kannan & Ma (2018), "Selling the Premium in Freemium: The Impact of Product Line Extensions", Journal of Marketing, 82(6)** — randomized field experiment with the National Academies Press (NAP), which gives away PDFs free and sells paperbacks. Finalist for the 2018 MSI/H. Paul Root Award.
- Design: three conditions for book titles — control (free PDF + paperback), e-book added (priced below paperback), hardcover added (priced above paperback) — [Maryland Smith news](https://www.rhsmith.umd.edu/news/maryland-smith-researchers-receive-journal-marketing-award); [IIM Bangalore seminar summary](https://blog.iimb.ac.in/?p=1083)
- Findings: "Paperback titles accompanied by an additional premium format, either an e-book or a hardcover format, had higher sales than those in the control condition. The positive impact on paperback sales was stronger for titles that were more popular and/or lower in price, and the effect of introducing the e-book format was higher when the e-book price was closer to the paperback price." Individual-level analysis "confirmed the existence of compromise effect and attraction effect in the extended product line setting" — [IIM Bangalore seminar summary](https://blog.iimb.ac.in/?p=1083)
- Implication: adding a third paid option next to the existing premium can lift demand for the existing premium even when the free version remains available — this is direct experimental evidence linking tiering/decoy psychology to freemium conversion.

**Boudreau, Jeppesen & Miric (2022), "Competing on freemium: Digital competition with network effects", Strategic Management Journal, 43(7), 1374–1401** — (note: the requested citation "Boudreau, Jeppesen & Reisinger 2022, Management Science" could not be located; the paper by these authors on this topic is in SMJ with Miric as third author).
- Design: natural experiment on the Apple App Store, where an Apple policy change strengthened network effects — [IDEAS/RePEc](https://ideas.repec.org/a/bla/stratm/v43y2022i7p1374-1401.html)
- Finding: "Stronger network effects did not on their own lead to greater revenues for market leaders with respect to followers. However, in settings where freemium strategies were used, network effects greatly amplified the advantage of leaders over followers." The authors state that "stronger network effects and freemium strategies only benefitted market leaders in our setting" — [IDEAS/RePEc](https://ideas.repec.org/a/bla/stratm/v43y2022i7p1374-1401.html)

**Shi, Zhang & Srinivasan (2019), "Freemium as an Optimal Strategy for Market Dominant Firms", Marketing Science, 38(1), 150–169** — (note: Marketing Science, not Management Science). Analytical screening model with network effects.
- Findings: "Freemium can only emerge if the high- and low-end products provide different levels of ('asymmetric') marginal network effects" — the firm sets a zero price on the low-end product only if the high-end product gains more utility from an expanded user base. Also, "a firm pursuing the freemium strategy might increase the baseline quality on its low-end product above the 'efficient' level, which seemingly reduces differentiation" — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormksc/v38y2019i1p150-169.html); [Marketing Science](https://pubsonline.informs.org/doi/fpi/10.1287/mksc.2018.1109)

**Liu, Au & Choi (2014), "Effects of Freemium Strategy in the Mobile App Market: An Empirical Study of Google Play", JMIS, 31(3), 326–354**
- Design: panel of 711 ranked Google Play apps — [JMIS](https://www.jmis-web.org/articles/1219)
- Findings: freemium (offering a free version) is positively associated with sales of the paid app; a high review rating of the free version raises paid sales, whereas high visibility (rank) of the free version does not; "offering a quality free app is more important in boosting sales of the paid app" than visibility — [JMIS](https://www.jmis-web.org/articles/1219)

**Wagner, Benlian & Hess (2014), "Converting freemium customers from free to premium — the role of the perceived premium fit in the case of music as a service", Electronic Markets, 24, 259–268**
- Design: survey of 317 freemium users; theory from Dual Mediation Hypothesis and Elaboration Likelihood Model — [LMU ePub](https://epub.ub.uni-muenchen.de/104779)
- Finding: "companies providing freemium services can increase the probability of user conversion by providing a strong functional fit between their free and premium services" — i.e., the premium should be a coherent extension of the free experience rather than maximally restricted — [LMU ePub](https://epub.ub.uni-muenchen.de/104779); [Springer](https://link.springer.com/article/10.1007/s12525-014-0168-4)

**Hamari, Hanner & Koivisto (2020), "Why pay premium in freemium services? A study on perceived value, continued use and purchase intentions in free-to-play games", International Journal of Information Management, 51**
- Design: online survey, N = 869 free-to-play gamers; SEM — [University of Turku record](https://research.utu.fi/converis/portal/detail/Publication/17788215?lang=en_GB)
- Findings: support for the "Demand Through Inconvenience" hypothesis — "the higher the enjoyment of the freemium service, the lower the intentions to purchase premium content but higher intention to use the service overall"; social value positively affects both use and purchase; perceived quality of the free service is associated with use but not with premium purchase; economic value raises use and, via use, premium purchase. The authors describe the "freemium paradox": raising the free tier's perceived value "may both add to and retract from future profitability via increased retention on one hand, reduced monetization on the other" — [University of Turku record](https://research.utu.fi/converis/portal/detail/Publication/17788215?lang=en_GB); [IDEAS/RePEc](https://ideas.repec.org/a/eee/ininma/v51y2020ics0268401218311812.html)

**Niemand, Mai & Kraus (2019), "The zero-price effect in freemium business models: The moderating effects of free mentality and price–quality inference", Psychology & Marketing, 36(8), 773–790**
- Design: Study 1 implicit association test; Study 2 choice-based conjoint on a media streaming service — [unibz record](https://bia.unibz.it/esploro/outputs/journalArticle/The-zero-price-effect-in-freemium-business/991005984347201241)
- Findings: free options carry "irrationally high value" (zero-price effect), which explains structurally low premium conversion; two opposing intuitions moderate this — a "free mentality" (digital should be free) and "price–quality inference" (higher price = higher quality) — and their interplay "provides a lever to tackle the issue of low conversions" — [unibz record](https://bia.unibz.it/esploro/outputs/journalArticle/The-zero-price-effect-in-freemium-business/991005984347201241). Precursor: Niemand, Tischer, Fritzsche & Kraus (2015), "The Freemium Effect: Why Consumers Perceive More Value with Free than with Premium Offers", ICIS 2015 — [AIS eLibrary](https://aisel.aisnet.org/icis2015/proceedings/eBizeGov/24)

**Oestreicher-Singer & Zalmanson (2013), "Content or Community? A Digital Business Strategy for Content Providers in the Social Age", MIS Quarterly, 37(2), 591–616**
- Design: Last.fm user data (free basic use, fixed monthly premium fee); propensity-score matching to address self-selection — [TAU working paper](https://en-coller.tau.ac.il/sites/coller-english.tau.ac.il/files/RP_277_Oestreicher-Singer.pdf); [MISQ DOI](https://www.doi.org/10.25300/MISQ/2013/37.2.12)
- Findings: although premium features target content consumption, "willingness to pay for premium services is strongly associated with the level of community participation"; WTP rises as users climb a "ladder of participation" and is "more strongly linked to community participation than to the volume of content consumption" — [TAU working paper](https://en-coller.tau.ac.il/sites/coller-english.tau.ac.il/files/RP_277_Oestreicher-Singer.pdf)

**Sato (2019), "Freemium as optimal menu pricing", International Journal of Industrial Organization, 63, 480–510**
- Analytical two-sided-market model: the optimal menu often consists of only two services — ad-supported basic and ad-free premium — and "if the willingness to pay of advertisers is sufficiently high, the basic service is offered for free" — [MPRA/IDEAS](https://ideas.repec.org/p/pra/mprapa/81599.html)

**Rietveld (2018), "Creating and capturing value from freemium business models: A demand-side perspective", Strategic Entrepreneurship Journal, 12(2), 171–193**
- Design: digital PC games market; freemium vs premium games — [Erasmus Pure](https://pure.eur.nl/en/publications/creating-and-capturing-value-from-freemium-business-models-a-dema/)
- Findings: "freemium games are played less and generate less revenues" than premium games; "greater variety in games' menus of paid items is associated with higher revenues"; to reach parity freemium firms must create more value (quality, ads, network externalities) or operate at lower cost — [Erasmus Pure](https://pure.eur.nl/en/publications/creating-and-capturing-value-from-freemium-business-models-a-dema/)

**Deng, Lambrecht & Liu (2023), "Spillover Effects and Freemium Strategy in the Mobile App Market", Management Science, 69(9), 5018–5041** (2021–2026 study)
- Design: difference-in-differences on daily launches of free and paid versions of game apps on Apple's App Store — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormnsc/v69y2023i9p5018-5041.html)
- Finding: "launching a free version increases demand of the paid version of the same app, with an 8.9% increase in daily ratings at the mean", driven by sampling and enhanced discovery — [LBS summary](https://www.london.edu/faculty-and-research/academic-research/s/spillover-effects-and-freemium-strategy-in-the-mobile-app-market)

**Runge, Levav & Nair (2022), "Price promotions and 'freemium' app monetization", Quantitative Marketing and Economics, 20(2)** (2021–2026 study; Dick Wittink Prize)
- Design: randomized cohorts (promotions on/off) at a free-to-play game, six months of observed behavior — [IDEAS/RePEc](https://ideas.repec.org/a/kap/qmktec/v20y2022i2d10.1007_s11129-022-09248-3.html)
- Findings: "conversion and revenue improved in the treatment group with no evidence of harmful inter-temporal substitution or negative quality inferences"; authors attribute this to the zero price of the base product plus complementarity between base and premium — [Stanford GSB summary](https://www.gsb.stanford.edu/insights/why-free-play-apps-can-ignore-old-rules-about-cutting-prices). Earlier related working paper: Runge, Wagner, Claussen & Klapper (2016), "Freemium pricing: Evidence from a large-scale field experiment", ESMT WP 16-06, three freemium pricing variants, ~300,000 users — [IDEAS/RePEc](https://ideas.repec.org/p/esm/wpaper/esmt-16-06.html)

**Voigt & Hinz (2016), "Making Digital Freemium Business Models a Success: Predicting Customers' Lifetime Value via Initial Purchase Information", Business & Information Systems Engineering, 58(2), 107–118**
- Three freemium companies selling virtual credits; CLV is higher for customers who (a) purchase early after registration, (b) spend more on the first purchase, (c) pay by credit card — [TU Darmstadt](https://tuprints.ulb.tu-darmstadt.de/5668/)

**Bichuch & Yaish (2026), "Freemium Is All You Need", arXiv 2608.00823** (2026, GenAI-specific theory)
- Game-theoretic model of a GenAI provider where free requests cost compute but improve model quality; shows a positive-quality free tier is offered under individual rationality, incentive compatibility, in-kind training and no-screening conditions, and the menu "must contain a maximal-quality training-exempt paid tier"; sufficient conditions for offering free service depend on inference cost — [arXiv](https://arxiv.org/abs/2608.00823). Context differs sharply from exam prep (AI compute cost, data-for-training exchange).

### Inferences
- The causal evidence (Gu et al. field experiment; Deng et al. DiD; Liu et al. panel) points consistently to a free version *expanding* paid demand for information goods via sampling and discovery, but the two correlational "value-perception" studies (Hamari et al.; Niemand et al.) warn that the better and more enjoyable the free tier, the lower the premium purchase intent. The managerial reconciliation is Wagner et al.'s "premium fit": make free good enough to be used and liked, but make premium a coherent extension of the same job, not a different product.
- Rietveld and Boudreau et al. together suggest freemium is a weak default for a product without network effects or market leadership; a question bank has at most weak network effects (user-generated explanations, peer statistics), so the case for a free tier must rest on sampling/uncertainty-reduction and word of mouth, not on network effects.
- Oestreicher-Singer & Zalmanson imply that community participation (discussion of questions, contributing explanations) could be a stronger predictor of WTP than raw question volume — relevant to which features to gate.

### Gaps
- Could not access the full text of Kumar (2014) HBR; the 2–5% and 15–25% figures are relayed through a secondary summary.
- Could not access the published Gu, Kannan & Ma (2018) article for exact effect sizes (percent lift in paperback sales, number of titles); only qualitative direction and moderators are documented.
- Could not locate any paper matching "Boudreau, Jeppesen & Reisinger (2022), Management Science"; the closest match is Boudreau, Jeppesen & Miric (2022), SMJ.
- No peer-reviewed freemium study in an education or exam-prep context was found; all empirical settings are cloud storage, music streaming, mobile games, apps, news and book publishing.

---

## Key Question 2: Benchmark free-to-paid conversion rates (freemium vs free trial; opt-in vs opt-out; B2B vs B2C; education)

### Takeaway
Across the largest industry datasets, self-serve freemium converts roughly 2–5% of free users (median ~3–4%, top quartile 8–15%), free trials convert ~8–25% (no-card/opt-in at the low end, card-required/opt-out ~2–3x higher), and in consumer mobile apps hard paywalls convert ~5x better than freemium per install and earn ~8x more revenue per install, with no retention penalty. Education/ed-tech freemium sits at the low end (2.6% freemium-to-paid in First Page Sage's client data), while ed-tech free trials convert ~25%.

### Cited Findings

**OpenView / Pendo / Lenny Rachitsky survey (1,000+ B2B products)**
- Freemium (self-serve): good 3–5%, great 6–8%. Freemium (sales-assist): good 5–7%, great 10–15%. Free trial: good 8–12%, great 15–25%. Distribution: roughly one third of freemium products convert at 2.5–5% and only 15% exceed 20%; 24% of free-trial products convert at 7.5–10% and 14% exceed 20%. Conversion falls as target customer size rises; developer-focused products convert at roughly half the rate of non-developer products — [Lenny's Newsletter](https://www.lennysnewsletter.com/p/what-is-a-good-free-to-paid-conversion)
- OpenView Product Benchmarks: website-to-signup conversion is ~5% for free-trial products vs ~9% for freemium (freemium brings 33% more visitors into the product), but "a free trial drives better free-to-paid conversion (nearly 2x)". OpenView's framing: "Freemium should be thought of as a lead generation play ... if you need revenue ASAP, go with a trial model" — [OpenView Product Benchmarks 2022](https://openviewpartners.com/blog/product-benchmarks-2022/); [OpenView Product Benchmarks](https://openviewpartners.com/productbenchmarks?ref=refind); [boldstart summary of OpenView 2023 dev-tool benchmarks](https://boldstart.vc/?p=1596)
- Median freemium conversion across B2B SaaS 2–5%, top performers 5–10% (OpenView 2022 as relayed by an aggregator) — [Artisan Growth Strategies (aggregator)](https://www.artisangrowthstrategies.com/blog/freemium-conversion-rate-benchmarks)

**2026 survey of 200 B2B software products (Kyle Poyar / ChartMogul / ProductLed)**
- One in four freemium products converts <2.5% of free users within six months; another quarter converts 10–15%; median 8% — [Userpilot summary](https://userpilot.com/blog/freemium-to-premium); report host — [ChartMogul SaaS Conversion Report](https://chartmogul.com/reports/saas-conversion-report/)

**First Page Sage (80+ SaaS clients, 2021–2025)**
- Average freemium-to-paid 3.7%; by industry from 2.6% (Education/EdTech) to 5.8% (RegTech). Education/EdTech: visitor-to-freemium 13.9%, freemium-to-paid 2.6% — [First Page Sage freemium benchmarks](https://firstpagesage.com/seo-blog/saas-freemium-conversion-rates/)
- Education/EdTech free trial: visitor-to-trial 10.3%, trial-to-paid 24.8% (2025) — [First Page Sage free trial benchmarks](https://firstpagesage.com/seo-blog/saas-free-trial-conversion-rate-benchmarks/)

**Opt-in vs opt-out trials**
- B2B SaaS free trials convert ~3.0–5.5% without a credit card vs ~18–25% with payment info upfront; consumer app data: opt-out trials ~48.8% vs opt-in ~18.2% ("same product, a different default, nearly triple the conversion"; attributed to RevenueCat/Adapty 2026 reports) — [Voxbooster 2026 compilation (aggregator)](https://voxbooster.com/blog/free-trial-conversion-statistics-2026). Card-required ~25% median vs no-card ~18% median — [Artisan Growth Strategies (aggregator)](https://www.artisangrowthstrategies.com/blog/freemium-conversion-rate-benchmarks)

**RevenueCat, State of Subscription Apps 2026 (115,000+ apps, >$16B revenue; consumer mobile)**
- Hard paywall apps: 10.7% median Day-35 trial-to-paid conversion vs 2.1% for freemium apps (~5x). Revenue per install at Day 60: $3.09 (hard paywall) vs $0.38 (freemium), ~8x; at Day 14: $2.32 vs $0.27. One-year retention of yearly subscribers: 27% (hard paywall) vs 28% (freemium), "statistically negligible". Trial length: 17–32 day trials convert 42.5% vs 25.5% for trials of 4 days or less; 55.4% of 3-day-trial cancellations happen on Day 0. Annual-plan churn: 35% cancel in month 1, ~72% within year 1 — [RevenueCat 2026 benchmarks](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026)

**Academic data points**
- Kumar (HBR 2014): typical freemium conversion 2–5% — [DBS summary](https://www.dbs.com.sg/sme/businessclass/articles/strategy-and-outlook/conversion-rate.page)
- Freemium gaming literature: "premiumization rates generally range between 1% and 10%" — [LJMU manuscript on freemium mobile gaming](https://researchonline.ljmu.ac.uk/id/eprint/18555/3/Manuscript%20-%20Freemium%20Mobile%20Gaming%20without%20author%20details.pdf)
- Duolingo (B2C education, see Q3): paid subscribers as % of MAU 3.3% (2019), 4.4% (2020), 4.5% (Mar 2021), 9.0% of LTM MAU (Q3 2025) — [Duolingo S-1](https://www.sec.gov/Archives/edgar/data/1562088/000162828021013065/duolingos-1.htm); [Duolingo Q3 2025 shareholder letter](https://www.sec.gov/Archives/edgar/data/1562088/000162828025049514/q3fy25duolingo9-30x25share.htm)

### Inferences
- The benchmark literature is consistent that freemium and trial measure different things: freemium's denominator is everyone who ever signed up (so 3% of a large base), whereas trial conversion is measured on intent-qualified users. A Free/Core/Infinite question bank should expect ~2–4% of all free registrants to pay, unless the free tier is tight enough that it behaves like a trial.
- Education skews low in freemium conversion (2.6%) but normal-to-high in trial conversion (24.8%), consistent with the "zero-price effect" and "free mentality" among students; this is a specific warning for an ed-tech freemium launch.
- RevenueCat's consumer data is the strongest large-N evidence that, for a product whose value is apparent quickly, a hard paywall with a trial out-earns freemium many times over without hurting retention. This is the central counter-argument to keeping a perpetual free tier.

### Gaps
- No ProfitWell/Paddle primary report with freemium vs trial conversion figures was retrievable; the "opt-out ~48% vs opt-in ~18%" figures come via aggregators citing RevenueCat/Adapty, not a ProfitWell primary.
- No benchmark splits B2C education vs B2B education; First Page Sage's EdTech figure is from an SEO agency's SaaS client base (sample ~80 companies total across all industries) and should be treated as indicative.
- Databox and Userpilot primary benchmark reports with their own data were not found; Userpilot relays third-party surveys.

---

## Key Question 3: Evidence specific to ed-tech and learning apps (Duolingo, Coursera, Quizlet, Chegg, Brainscape, Anki, Khan Academy, medical qbanks)

### Takeaway
Duolingo is the only ed-tech company with detailed public freemium metrics: paid penetration rose from 3.3% of MAU (2019) to 9.0% of LTM MAU (2025) with a free tier that keeps all learning content free and gates convenience (ads, hearts/energy, offline, AI). Other ed-tech firms disclose little; medical exam-prep incumbents (UWorld) largely use no-free/trial models, while challengers (AMBOSS) use a small metered free allowance plus a short trial.

### Cited Findings

**Duolingo (S-1, June 2021)**
- Paid subscribers vs MAU: 0.9M / 27.3M (3.3%) at Dec 2019; 1.6M / 36.7M (4.4%) at Dec 2020; 1.8M / 39.9M (4.5%) at Mar 2021. Subscriptions were 73% of 2020 revenue, advertising 17%, English Test and other 10% — [Duolingo S-1](https://www.sec.gov/Archives/edgar/data/1562088/000162828021013065/duolingos-1.htm)
- Rationale for free: free access "enables significant user scale"; two flywheels (learning data → better product → word of mouth; scale → capital to product rather than marketing). "Our learner scale and word-of-mouth growth allow us to focus our capital investments on product innovation and data analytics, as opposed to brand or performance marketing." Learning content is deliberately free; Plus sells ad-free plus extra features — [Duolingo S-1](https://www.sec.gov/Archives/edgar/data/1562088/000162828021013065/duolingos-1.htm)
- "Learners tend to use our product for months or even years before deciding to subscribe" — [TechCrunch on the S-1](https://techcrunch.com/2021/06/29/duolingos-s-1-depicts-heady-growth-monetization-new-focus-on-english-certification)
- App-store take rate: generally 30% on in-app purchases; 51% of 2020 revenue via Apple, 19% via Google — [Duolingo S-1](https://www.sec.gov/Archives/edgar/data/1562088/000162828021013065/duolingos-1.htm)

**Duolingo (2025 shareholder letters and FY2025 10-K)**
- Q3 2025: MAU 135.3M (+20% YoY), DAU 50.5M (+36%), paid subscribers 11.5M (+34%), paid subscriber penetration 9.0% of LTM MAU; subscription revenue per average paid subscriber +7% YoY driven by "mix shift toward higher-priced subscription tiers" (Super Duolingo, Duolingo Max, family plan) — [Q3 2025 shareholder letter](https://www.sec.gov/Archives/edgar/data/1562088/000162828025049514/q3fy25duolingo9-30x25share.htm); Q1 2025 penetration 8.9% — [Q1 2025 shareholder letter](https://www.sec.gov/Archives/edgar/data/1562088/000156208825000098/q1fy25duolingo3-31x25share.htm)
- Tier structure: all course content free; Super Duolingo = ad-free, unlimited hearts, mistake review, legendary levels, offline lessons; Duolingo Max (2023) = Super + AI features, priced above Super, offered to a portion of users; free users are limited by hearts/energy that regenerate with waiting or upgrade — [Duolingo FY2025 10-K](https://www.sec.gov/Archives/edgar/data/1562088/000162828026012494/duol-20251231.htm)

**Chegg (FY2024 10-K)**
- 6.6M subscribers to Subscription Services in 2024, down 14% from 7.7M in 2023. No free-trial conversion rate disclosed — [Chegg FY2024 10-K](https://www.sec.gov/Archives/edgar/data/1364954/000136495425000013/chgg-20241231.htm)

**Coursera (10-Ks and 2025 releases)**
- 183M registered learners as of June 30, 2025; consumer revenue +9% in 2024; "over 65% of our cash receipts from Consumer offerings came from individual learners who were registered on our platform as of December 31, 2022" (i.e., monetization of the existing free base over time). No free-to-paid conversion rate disclosed — [Coursera FY2024 10-K](https://www.sec.gov/Archives/edgar/data/1651562/000165156225000013/cour-20241231.htm); [Coursera Q2 2025 results](https://www.businesswire.com/news/home/20250724001650/en/Coursera-Reports-Second-Quarter-2025-Financial-Results/)

**Quizlet**
- 60M+ monthly users; Quizlet Plus subscriber counts not disclosed — [Quizlet help centre](https://help.quizlet.com/hc/en-au/articles/360041181691-Subscribing-to-Quizlet); earlier 50M MAU milestone — [Mobile Marketing Magazine](https://mobilemarketingmagazine.com/mobile-learning-tool-quizlet-reaches-50m-monthly-users/)

**Brainscape**
- Freemium with soft paywalls: free account can study a limited number of cards; key features gated; no free trial offered. No conversion data — [Fitgap (aggregator)](https://us.fitgap.com/products/brainscape)

**Medical exam-prep question banks (closest analogue to the reader's product)**
- AMBOSS: 5-day trial plus a free allowance of 50 questions per month; student plans from $19.99/month or $12.50/month billed annually, 30-day money-back guarantee — [Lecturio comparison](https://www.lecturio.com/blog/best-usmle-qbanks-2026-uworld-vs-amboss-vs-lecturio/); [Iatrox](https://www.iatrox.com/blog/free-vs-paid-qbanks-usmle-2026)
- UWorld: demo questions only; occasional 7-day full-access trials; positioned at the premium end; "90%+ of US medical students use UWorld" (vendor-blog claim) — [Lecturio comparison](https://www.lecturio.com/blog/best-usmle-qbanks-2026-uworld-vs-amboss-vs-lecturio/)

### Inferences
- Duolingo's model is "content free, convenience paid": friction (hearts/energy, ads) rather than content scarcity is the monetization lever, and penetration roughly tripled over six years as tiering deepened (Super → Max → Family). This shows a free tier can coexist with rising paid penetration, but Duolingo's economics depend on 130M+ MAU scale and ad revenue, which an exam-prep qbank will not have.
- The market leader in the reader's own category (UWorld) does not run freemium; the challenger (AMBOSS) runs a tightly metered free tier (50 questions/month) plus a 5-day trial. Category convention is therefore "trial or tight meter", not perpetual generous free.
- Coursera's statement that most consumer cash comes from learners registered a year earlier echoes Duolingo's "months or years before subscribing" — in education, free registrants convert slowly, which suits long-lifecycle products more than exam-bounded ones.

### Gaps
- No public free-to-paid conversion rates for Quizlet, Chegg, Coursera, Brainscape, Anki (free/open source) or Khan Academy (non-profit, no paid tier); none reported tier-mix data.
- No disclosed conversion or retention data for UWorld or AMBOSS; their models are inferred from pricing pages via third-party blogs.
- No academic study of freemium/trial in exam-prep or question-bank products was found.

---

## Key Question 4: Free trial vs freemium when usage is time-bounded (exam prep)

### Takeaway
Theory and experiments on trials indicate that time-locked trials are optimal when consumers learn quickly about product value, that longer trials raise delayed conversion but also cannibalize, and that trial-acquired customers have substantially lower lifetime value (−59%) than regular customers. No study directly addresses products whose useful life ends at an exam, but the logic of the literature (freemium's payoff accrues over long tenures via referral and slow conversion) implies freemium's advantage shrinks as the usage window shortens.

### Cited Findings
- Cheng & Liu (2012), "Optimal Software Free Trial Strategy: The Impact of Network Externalities and Consumer Uncertainty", ISR 23(2), 488–504: derives conditions under which time-locked trials should be introduced; trials are valuable when uncertainty inhibits purchase and network effects reward adoption; "longer trials reduce uncertainty but increase cannibalization risk"; a unified framework compares time-locked vs feature-limited trials — [IDEAS/RePEc](https://ideas.repec.org/a/inm/orisre/v23y2012i2p488-504.html)
- Cheng, Li & Liu (2015), "Optimal Software Free Trial Strategy: Limited Version, Time-locked, or Hybrid?", Production and Operations Management 24(3), 504–517: "the hybrid strategy weakly dominates the limited and time-locked versions, and the intensity of the network effects is a key factor" — [IDEAS/RePEc](https://ideas.repec.org/a/bla/popmgt/v24y2015i3p504-517.html)
- Dey, Lahiri & Liu (2013), "Consumer Learning and Time-Locked Trials of Software Products", JMIS 30(2), 239–268: "a time-locked trial is optimal only when the rate of learning is sufficiently large"; neither optimal trial length nor price is monotonic in learning rate; at moderate learning rates the firm offers a longer trial and a lower price, at high rates the opposite; "positive network effects have a minimal impact on this optimality" — [JMIS](https://jmis-web.org/articles/293)
- Datta, Foubert & van Heerde (2015), "The Challenge of Retaining Customers Acquired with Free Trials", JMR 52(2), 217–234: household panel from a digital TV service; "systematic behavioral differences ... make the average customer lifetime value (CLV) of free-trial customers 59% lower than that of regular customers", though trial customers are more responsive to marketing communication and usage — [Tilburg University](https://research.tilburguniversity.edu/en/publications/the-challenge-of-retaining-customers-acquired-with-free-trials/); [Phys.org summary](https://phys.org/news/2015-04-free-trial.html)
- Foubert & Gijsbrechts (2016), "Try It, You'll Like It—Or Will You? The Perils of Early Free-Trial Promotions for High-Tech Service Adoption", Marketing Science 35(5), 810–826 — [Marketing Science](https://pubsonline.informs.org/doi/references/10.1287/mksc.2015.0973)
- Zhang & Duan (2025), "Longer or shorter? A large-scale randomized field experiment on the impact of free trial duration on sustainable user conversion in the Freemium model", Frontiers in Psychology: RCT at a global image-editing SaaS, 680,588 new users in 190 countries, July 2022–July 2024, 7-day vs 3-day trial. 7-day trial raised trial adoption +11.1%, no change in immediate conversion, delayed conversion +42.36%, total conversion +20.92%, higher cumulative spend; benefits concentrated in task-oriented (not creative) features and high-individualism markets — [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12217587/)
- RevenueCat 2026: 17–32-day trials convert 42.5% vs 25.5% for ≤4-day trials; freemium and hard-paywall one-year retention equal (28% vs 27%) — [RevenueCat 2026](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026)
- Duolingo and Coursera both state that free users monetize slowly ("months or even years"; >65% of consumer cash from learners registered a year earlier) — [TechCrunch on Duolingo S-1](https://techcrunch.com/2021/06/29/duolingos-s-1-depicts-heady-growth-monetization-new-focus-on-english-certification); [Coursera FY2024 10-K](https://www.sec.gov/Archives/edgar/data/1651562/000165156225000013/cour-20241231.htm)
- Lee/Kumar/Gupta: 65% of a free user's ~$24/yr value comes from referrals — a channel that needs tenure to pay off — [Wharton abstract](https://marketing.wharton.upenn.edu/wp-content/uploads/2016/10/Title-and-Abstract-Lee-Clarence-10-10-2013.pdf)
- Category practice: AMBOSS 5-day trial + 50 free questions/month; UWorld demo questions and occasional 7-day trials — [Lecturio](https://www.lecturio.com/blog/best-usmle-qbanks-2026-uworld-vs-amboss-vs-lecturio/)

### Inferences
- Freemium's documented economic engine (slow conversion over long tenure + referral value) is weakest when the customer's need expires at a fixed exam date: a learner who stays free until the exam never converts and then churns. This favors a time-locked or hybrid trial (Cheng, Li & Liu) or a tight meter that forces the decision well before the exam.
- Exam prep plausibly has a high "rate of learning" about product value (a student knows after 20–50 questions whether explanations are good), which is exactly the condition under which Dey et al. find time-locked trials optimal and under which 7-day-style trials outperform 3-day ones.
- Datta et al.'s −59% CLV for trial-acquired customers is from a continuous-service context (digital TV); for a product with a naturally bounded lifecycle the comparison baseline differs, so the finding should be read as "trial customers are more marketing-sensitive and churn-prone", not as an argument against trials per se.

### Gaps
- No study was found on freemium vs trial for products with exogenously finite usage windows (exam, certification, course term). The inference above is reasoning from adjacent evidence, not a measured result.
- Yoganarasimhan, Barzegary & Pani, "Design and Evaluation of Optimal Free Trials" (Management Science, 2022/2023; SaaS field experiment comparing 7/14/30-day trials) could not be retrieved (publisher 403/503); it is known to exist from indexing but its effect sizes are not recorded here — [Management Science listing](https://pubsonline.informs.org/doi/fpi/10.1287/mnsc.2022.4507)

---

## Key Question 5: Marginal-cost argument and the optimal size of the free tier (theory)

### Takeaway
Information-economics models show that near-zero marginal cost is necessary but not sufficient for a large free tier: freemium is optimal when consumers underestimate value and learn by using, when word of mouth is strong, and when the premium gains more from network size than the free version does. Several models predict that the optimal free tier is *larger* than naive differentiation logic suggests (Shi et al.) and that the firm should deliberately tolerate cannibalization, but that feature-limited freemium is optimal only in particular ranges of consumer beliefs (Niculescu & Wu).

### Cited Findings
- Niculescu & Wu (2014), "Economics of Free Under Perpetual Licensing: Implications for the Software Industry", ISR 25(1), 173–199: two-period model comparing feature-limited freemium (FLF), uniform seeding (S) and charge-for-everything (CE) with bounded rationality, information asymmetry, WOM and experience-based learning. "Seeding proves optimal when consumers significantly underestimate functionality value and cross-module synergies are weak"; when synergies strengthen or priors improve, CE and FLF compete; "FLF is optimal when the prior on premium functionality is either relatively low or high, but not in between"; stronger WOM expands the seeding region and reduces required seeding ratios — [IDEAS/RePEc](https://ideas.repec.org/a/inm/orisre/v25y2014i1p173-199.html)
- Cheng & Liu (2012), ISR: free-trial optimality hinges on the trade-off between uncertainty reduction and cannibalization; network externalities raise the value of trials — [IDEAS/RePEc](https://ideas.repec.org/a/inm/orisre/v23y2012i2p488-504.html)
- Shi, Zhang & Srinivasan (2019), Marketing Science: freemium requires asymmetric marginal network effects (premium gains more from installed base than free), and the optimal free product's quality may be raised "above the 'efficient' level, which seemingly reduces differentiation" — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormksc/v38y2019i1p150-169.html)
- Sato (2019), IJIO: in two-sided (ad-funded) markets the optimal menu is two services, basic ad-supported and premium ad-free, with the basic service free when advertiser WTP is high enough — [IDEAS/RePEc](https://ideas.repec.org/p/pra/mprapa/81599.html)
- Lambrecht & Misra (2017), "Fee or Free: When Should Firms Charge for Online Content?", Management Science 63(4), 1150–1165: with heterogeneous and time-varying valuations and both subscription and ad revenue, firms should offer *more* free content in high-demand periods ("countercyclical offering"); empirically confirmed at an online content provider — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormnsc/v63y2017i4p1150-1165.html); [LBS summary](https://www.london.edu/faculty-and-research/academic-research/f/fee-or-free-when-should-firms-charge-for-online-content)
- Kumar (HBR 2014): diagnostic rule — too-high conversion signals the free tier is too small and acquisition is being throttled — [DBS summary](https://www.dbs.com/in/sme/businessclass/articles/business-strategy/conversion-rate.page)
- Bichuch & Yaish (2026): for GenAI, free-tier optimality depends on inference (marginal) cost and on free usage producing training data that raises future quality — a "data-for-access" rationale — [arXiv](https://arxiv.org/abs/2608.00823)

### Inferences
- For a question bank, the marginal cost of a free user is near zero only if AI-generated explanations/tutoring are not part of the free tier; if the Infinite tier includes LLM features, the Bichuch–Yaish logic applies and the free tier should exclude or cap compute-heavy features.
- Niculescu & Wu's condition — FLF is optimal when consumers' prior on premium value is low (they need to see it) or high (they will buy anyway), not in between — suggests a new entrant with low brand awareness (low prior) is in a region where feature-limited freemium can be optimal, whereas an established brand sits in the ambiguous middle.
- Lambrecht & Misra's countercyclical result translates to exam prep as: open the meter wider in low-demand months (off-season) to build the base, and tighten it as exams approach when WTP is high.
- Shi et al. imply that the free tier's quality (question and explanation quality) should not be degraded; differentiation should come from quantity/convenience/analytics, not from a worse experience.

### Gaps
- Could not access the full Niculescu & Wu paper to extract the exact threshold expressions for optimal free-feature share.
- No model specifically parameterizes "free tier size" as a share of total content for an education product.

---

## Key Question 6: Three-tier (good/better/best) pricing, decoy/compromise effects, and the "unlimited" top tier

### Takeaway
Behavioral research robustly shows that adding a third option shifts choice toward the middle (compromise effect: e.g., 57% choosing the middle camera vs a 50/50 split with two options) and that an asymmetrically dominated decoy can move the majority to the target (Economist experiment: 84% vs 32%). Practitioner guidance (Mohammed, HBR 2018) expects 25–50% of revenue from "Better" and 30–60% from "Best", with Good no more than ~25% below Better and Best no more than ~50% above Better, and at most four differentiating attributes between adjacent tiers. Flat-rate ("unlimited") plans are systematically over-chosen relative to usage (flat-rate bias), which supports an unlimited top tier, but a top tier that is only "more of the same" risks being a dominated decoy rather than a value step.

### Cited Findings
- Simonson & Tversky (1992), "Choice in Context: Tradeoff Contrast and Extremeness Aversion", JMR 29(3): "the attractiveness of an option is enhanced if it is an intermediate option in the choice set and is diminished if it is an extreme option"; compromise effect: adding an adjacent non-dominated option increases the share of the option that becomes the middle. Camera example: Minolta X-370 ($170) vs 3000i ($240) split evenly; adding the 7000i ($470) led 57% to choose the middle 3000i, the rest split roughly equally between extremes — [Simonson & Tversky 1992 PDF](https://cognition.aau.at/bg/BA/Simon%20&%20tversky,%201992.pdf)
- Huber, Payne & Puto (1982), "Adding Asymmetrically Dominated Alternatives: Violations of Regularity and the Similarity Hypothesis", JCR 9(1): adding an option dominated by one alternative but not the other increases the dominating alternative's share, violating the regularity axiom — [Huber, Payne & Puto 2014 retrospective (JMR)](https://people.duke.edu/~jch8/bio/Papers/HuberPaynePutoJMR%202014.pdf); [Wikipedia: Decoy effect](https://en.wikipedia.org/wiki/Decoy_effect)
- Ariely's Economist experiment (Predictably Irrational, 2008), 100 MIT Sloan students: web-only $59, print-only $125, print+web $125 → 16 chose web-only, 0 print-only, 84 print+web; with the print-only decoy removed, 68% chose web-only and 32% print+web — [NPR transcript](https://www.npr.org/transcripts/19231906); [Adam Nash summary](https://adamnash.blog/2008/02/06/)
- Gu, Kannan & Ma (2018), Journal of Marketing: in a randomized field experiment, adding a third paid format (e-book or hardcover) next to the paperback increased paperback sales; the e-book effect was larger when its price was closer to the paperback price; individual-level choices confirmed compromise and attraction effects — [IIM Bangalore summary](https://blog.iimb.ac.in/?p=1083)
- Mohammed (2018), "The Good-Better-Best Approach to Pricing", HBR Sept–Oct 2018: companies typically expect 10–20% of revenue from Good, 25–50% from Better, 30–60% from Best; Good should be no more than ~25% cheaper than Better and Best no more than ~50% more than Better; "no more than four attributes should differ between Good and Better and between Better and Best"; use "fence" attributes with broad appeal to stop premium customers trading down; lower-tier features must carry forward so each step is a clear improvement; Allstate used accident forgiveness and clean-record rewards as fences — [HBR landing page](https://hbr.org/2018/09/the-good-better-best-approach-to-pricing); [The Product Person summary](https://theproductperson.substack.com/p/the-good-better-best-approach-to); [FieldCamp summary](https://fieldcamp.ai/blog/good-better-best-pricing.md)
- Practitioner claims (aggregator-level, weak evidence): "tiered pricing increases average purchase value by 15–25%"; "implementing the decoy effect in digital pricing can increase conversion to higher-tier plans by up to 30%" (attributed to ConversionXL); "three pricing tiers convert better than two or four"; a common mistake is making the decoy "completely useless — it should still be a viable, just slightly inferior choice" — [FieldCamp](https://fieldcamp.ai/blog/good-better-best-pricing.md); [Monetizely](https://www.getmonetizely.com/articles/the-decoy-effect-how-strategic-pricing-tiers-can-maximize-revenue); [Kinde](https://kinde.com/learn/billing/pricing/leveraging-behavioral-economics-to-increase-conversions/)
- GBB pitfalls: "GBB can quietly undermine your growth through missed revenue and mis-served customers when applied without careful thought"; it suits relatively homogeneous user bases — [Monetizely](https://www.getmonetizely.com/blogs/killing-me-softly-bad-practices-with-good-better-best-pricing)
- Lambrecht & Skiera (2006), "Paying Too Much and Being Happy About It: Existence, Causes and Consequences of Tariff-Choice Biases", JMR 43(2), 212–223: across three datasets, many users choose a flat rate although pay-per-use would be cheaper (flat-rate bias), which is larger, more regular and more persistent than the opposite bias; causes: insurance effect, "taxi-meter effect", convenience effect, overestimation effect — [UCLA Anderson PDF](https://www.anderson.ucla.edu/documents/areas/fac/marketing/paying_too_much.pdf)
- Durability/robustness caveats: compromise effects are smaller or less stable when choices have real consequences and vary across segments — [Müller, Kroll & Vogt, "Fact or Artifact? Does the compromise effect occur when subjects face real consequences"](https://ideas.repec.org/p/mag/wpaper/09009.html); [Müller, Vogt & Kroll 2012, Marketing Letters](https://ideas.repec.org/a/kap/mktlet/v23y2012i1p73-92.html); [Lichters et al. 2016, "How durable are compromise effects?", JBR](https://ideas.repec.org/a/eee/jbrese/v69y2016i10p4056-4064.html)

### Inferences
- With Free / Core / Infinite, the compromise effect predicts Core will be over-chosen relative to a Core-only offer, and the Economist/Huber logic says Infinite will pull buyers upward only if Core is positioned close to it in price (Gu et al.: the e-book worked best when priced close to the paperback) and Infinite adds a visible, qualitatively different benefit (Mohammed's "fence").
- Flat-rate bias (Lambrecht & Skiera) is direct support for an "unlimited" top tier for exam prep: students overestimate how many questions they will do and value the insurance of no meter — but this also means Core must have a salient cap (the "taxi meter") for Infinite to sell.
- "More of the same" top tiers (just a higher question cap) risk Rietveld's finding that revenue comes from *variety* in paid items, and Mohammed's warning to differentiate on ≤4 clear attributes; adding analytics, adaptive scheduling, or AI tutoring to Infinite is more consistent with the literature than only lifting the cap.
- The academic effects are measured in lab or single-category settings; the "up to 30%" and "15–25% AOV" practitioner numbers have no traceable primary source and should not be cited as evidence.

### Gaps
- No peer-reviewed field experiment on SaaS pricing pages comparing two vs three tiers was found; the "three beats two" claim rests on practitioner lore and lab compromise-effect studies.
- The full HBR text of Mohammed (2018) was paywalled; figures come from secondary summaries that quote the article.
- No published study quantifies the share of buyers choosing the middle tier in software subscriptions specifically.
- A meta-analysis of the compromise effect (Neumann & Böckenholt 2014 was requested) could not be located under that citation.

---

## Key Question 7: Cannibalization vs market expansion — when is the net effect of a free tier positive?

### Takeaway
Causal studies in app and book markets find that free versions expand paid demand on net (Deng et al. +8.9% paid-app demand; Liu et al. positive association; Gu et al. positive in a field experiment), while structural and survey evidence identifies the cannibalization mechanism (zero-price effect; enjoyment lowers purchase intent; freemium games earn less than premium). The literature's conditions for a positive net effect are: strong word of mouth/referral, network effects that favor the premium, high consumer uncertainty about quality (so sampling matters), low marginal cost, heterogeneous WTP, and a free tier that is used but leaves a salient inconvenience.

### Cited Findings
- Deng, Lambrecht & Liu (2023), Management Science: launching a free version raises paid-version demand by 8.9% (daily ratings at mean) via sampling and discovery — [LBS](https://www.london.edu/faculty-and-research/academic-research/s/spillover-effects-and-freemium-strategy-in-the-mobile-app-market)
- Liu, Au & Choi (2014), JMIS: freemium positively associated with paid-app sales across 711 apps; quality of the free version, not its visibility, drives paid sales — [JMIS](https://www.jmis-web.org/articles/1219)
- Gu, Kannan & Ma (2018), JM: with a free PDF always available, adding paid formats increased paperback sales, especially for popular and cheaper titles — [IIM Bangalore](https://blog.iimb.ac.in/?p=1083)
- Lee, Kumar & Gupta: referral program accounts for 65% of a free user's value (~$24/yr) — [Wharton abstract](https://marketing.wharton.upenn.edu/wp-content/uploads/2016/10/Title-and-Abstract-Lee-Clarence-10-10-2013.pdf)
- Kumar (HBR 2014): free users worth 15–25% of a premium subscriber, largely via referrals — [DBS summary](https://www.dbs.com.sg/sme/businessclass/articles/strategy-and-outlook/conversion-rate.page)
- Shi, Zhang & Srinivasan (2019): freemium only emerges with asymmetric network effects favoring premium — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormksc/v38y2019i1p150-169.html)
- Boudreau, Jeppesen & Miric (2022): freemium plus network effects amplify leaders' advantage; followers do not benefit — [IDEAS/RePEc](https://ideas.repec.org/a/bla/stratm/v43y2022i7p1374-1401.html)
- Rietveld (2018): freemium games are played less and earn less than premium games; paid-item variety raises revenue — [Erasmus Pure](https://pure.eur.nl/en/publications/creating-and-capturing-value-from-freemium-business-models-a-dema/)
- Hamari, Hanner & Koivisto (2020): enjoyment of the free service lowers premium purchase intention (N = 869) — [University of Turku](https://research.utu.fi/converis/portal/detail/Publication/17788215?lang=en_GB)
- Niemand, Mai & Kraus (2019): zero-price effect inflates perceived value of free, structurally depressing conversion — [unibz](https://bia.unibz.it/esploro/outputs/journalArticle/The-zero-price-effect-in-freemium-business/991005984347201241)
- Niculescu & Wu (2014): freemium/seeding optimal when consumers underestimate value and WOM is strong — [IDEAS/RePEc](https://ideas.repec.org/a/inm/orisre/v25y2014i1p173-199.html)
- Oestreicher-Singer & Zalmanson (2013): WTP tied to community participation more than content consumption — [TAU](https://en-coller.tau.ac.il/sites/coller-english.tau.ac.il/files/RP_277_Oestreicher-Singer.pdf)
- Chiou & Tucker (2013), "Paywalls and the Demand for News", Information Economics and Policy 25(2): a field test of paywalls across local media markets produced a 51% drop in visits, far larger among younger readers — [MIT DSpace](https://dspace.mit.edu/handle/1721.1/110528)
- RevenueCat 2026: freemium apps earn $0.38 RPI at Day 60 vs $3.09 for hard paywall; retention equal — [RevenueCat](https://www.revenuecat.com/blog/growth/subscription-app-trends-benchmarks-2026)

### Inferences
- Positive-net conditions that *do* apply to an educational question bank: low marginal cost of serving questions, high uncertainty about explanation quality before trying, heterogeneous WTP (students vs residents vs institutions), and strong peer word of mouth within cohorts.
- Conditions that *do not* clearly apply: strong network effects favoring premium (unless peer statistics/leaderboards are premium-only), market leadership (Boudreau et al. show followers gain little from freemium), and long tenure for referral value to accrue.
- Chiou & Tucker's finding that young readers react most strongly to paywalls suggests students (young, "free mentality") are the segment most likely to abandon rather than pay when the free allowance is removed, which cuts both ways: a free tier retains them for word of mouth, but they are also the least likely to convert.

### Gaps
- No study decomposes the net effect into cannibalization vs expansion for an education product; the directional findings are from games, apps, books and news.
- Effect sizes for word-of-mouth value outside Dropbox-like products (Lee/Kumar/Gupta) were not found.

---

## Key Question 8: Metered / usage-based paywalls (N per day/month) — optimal meter size and conversion

### Takeaway
The two rigorous NYT studies show that a metered paywall reduces content demand (−9.9% to −16.8% overall; −57% among heavy users) but raises subscriptions substantially (+31% in seven months when the mobile meter tightened from unlimited to 3 articles/day) and is net revenue-positive; the quantity restriction has the largest and growing effect on subscription propensity, and it works mainly on heavy, registered users. Metered designs work best when the meter binds for the engaged minority while leaving light users untouched; no study identifies a universally optimal meter size, and effects are strongest when quantity and exclusivity (content variety) levers are combined.

### Cited Findings
- Aral & Dhillon (2021), "Digital Paywall Design: Implications for Content Demand and Subscriptions", Management Science 67(4): panel of 29,705,796 NYT users (~202 million daily observations), seven-month quasi-experiment around June 27, 2013, when the mobile app changed from unlimited articles (top news/video sections only) to 3 articles/day from any section, with a one-week free trial at update; browser meter stayed at 10 articles/month. Results: total content demand −9.9% (−3.5% on browser alone); users who tried to exceed the quota −18.7% consumption; subscriptions +31% (≈31% of the 38,490 new subscriptions in the period), net revenue ≥ +$230,000 after ~$1.57M lost ad revenue (149.4M fewer impressions at $10.50 CPM) vs ~$1.80M added subscription revenue (~$150 average bundle). Subscription propensity rose by ~0.02 per additional article/day of prior readership; registered users who exceeded quota: +0.08 subscription probability; more-diverse readers: +0.05. "The quantity restriction has the largest sustained impact on subscription propensity and its effect increases over time"; quantity and exclusivity are complementary. Managerial conclusion: multidimensional paywall designs that also restrict variety of free content "are more effective at increasing subscriptions, demand, and revenue" than quantity alone — [Aral & Dhillon PDF](https://www.gwern.net/docs/traffic/2020-aral.pdf); [MIT DSpace record](https://dspace.mit.edu/handle/1721.1/129936)
- Pattabhiramaiah, Sriram & Manchanda (2019), "Paywalls: Monetizing Online Content", Journal of Marketing 83(2), 19–36 (MSI/H. Paul Root Award finalist): NYT's March 2011 paywall (20 free articles/month). Working-paper version: unique visitors −16.8%; −11.3% among light users vs −57.2% among heavy users; print circulation lifted by 0.18–0.68 share points (≈1.05–3.98%) across top DMAs; online ad revenue fell ~48.9% relative to category baseline (~$7.34M loss) but total two-year revenue gain of $117.7–149.1M (6.4–8.1% of NYT revenue) — [Working paper PDF](https://www.scheller.gatech.edu/directory/research/marketing/pattabhiramaiah/pdf/draft_nytpaywall_r4_final.pdf). Published-version summary: unique visitors −13.1%, no significant change in visits/pages/duration overall, heavy users adversely affected, ad revenue −48%, print decline arrested by ~27%, total revenue +13.5% within two years with about half from digital subscriptions — [MSI research recap](https://www.msi.org/research-recap/paywalls-monetizing-online-content-2/). Caveat from authors: metered paywalls "might suppress usage among loyal consumers, which could have implications for the firm's future growth potential" — [AMA](https://www.ama.org/2019/03/07/before-you-put-up-a-paywall-read-this-study/)
- Chiou & Tucker (2013), Information Economics and Policy 25(2): field test across local markets, visits −51% after paywall, larger drop for younger readers — [MIT DSpace](https://dspace.mit.edu/handle/1721.1/110528)
- Lambrecht & Misra (2017), Management Science: with ad plus subscription revenue, loosen the meter (more free content) in high-demand periods and tighten in low-demand periods ("countercyclical offering") — [IDEAS/RePEc](https://ideas.repec.org/a/inm/ormnsc/v63y2017i4p1150-1165.html)
- Lambrecht & Skiera (2006): metered consumption triggers the "taxi-meter effect", pushing users toward flat rates — [UCLA Anderson PDF](https://www.anderson.ucla.edu/documents/areas/fac/marketing/paying_too_much.pdf)
- Category example: AMBOSS meters 50 free questions/month alongside a 5-day trial — [Lecturio](https://www.lecturio.com/blog/best-usmle-qbanks-2026-uworld-vs-amboss-vs-lecturio/)

### Inferences
- A daily meter (N questions/day) replicates the NYT 2013 mobile design that produced the largest sustained subscription lift; the evidence says the meter should bind for the engaged minority (heavy users convert, light users are unaffected) and should be combined with an exclusivity dimension (e.g., only some topics or no explanations beyond a basic level in free) rather than quantity alone.
- Because paywall effects were strongest among registered users, requiring registration for the free tier (rather than anonymous access) is consistent with the evidence.
- The NYT studies had ad revenue to lose; a qbank with no ads loses nothing on the demand side except word-of-mouth and future conversion, so the cost side of tightening the meter is lower than in news.
- Lambrecht & Misra's countercyclical logic (loosen free in high-demand periods) was derived for ad-funded content; without ads, the opposite (tighten before exams when WTP peaks) is the more natural application, and this should be flagged as an inference, not a finding.

### Gaps
- No study estimates an optimal meter size as a function of product parameters; the NYT papers evaluate specific policy changes (20/month; unlimited → 3/day), not a continuum.
- No paywall study exists for educational or question-bank content; all are news (NYT, local papers).
- The published Pattabhiramaiah et al. article's exact numbers differ from the working paper (−13.1% vs −16.8% visitors; +13.5% vs +6.4–8.1% revenue); only the published-version summary was accessible, so both are reported.
