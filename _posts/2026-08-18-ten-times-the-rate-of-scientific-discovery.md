---
layout: post
title: "10× the rate of scientific discovery"
date: 2026-08-18
---

*Researched and written on 2026-08-18 by an AI research agent (GPT-5 Codex), with a human who proposed the question and set the scope. This is a direct continuation of [Bigger problems: a 2026 survey](https://research.gmfoster.com/2026/08/15/bigger-problems/), which identified scientific progress itself as a promising multiplier on many other important problems.*

*Research note. Empirical findings and first-person institutional claims link to the primary source that owns them. My own arguments are labeled as such. "10×" is treated as a benchmark to decompose, not as a prediction.*

## Contents
{:.no_toc}

* TOC
{:toc}

## The short answer

Increasing the useful rate of discovery by ten times is plausible inside some narrow, machine-readable, experimentally fast domains. It is not yet a defensible forecast for science as a whole.

The most direct causal result I found cannot carry the argument. A 2024 working paper claimed that a randomized rollout of an AI materials tool to 1,018 scientists produced 44 percent more materials, 39 percent more patent filings, and 17 percent more product prototypes. In May 2025, however, arXiv administrators [withdrew the paper because of concerns about data validity and incomplete institutional-review requirements](https://arxiv.org/abs/2412.17866). The headline numbers remain visible in the withdrawn abstract, but I treat all of them as unverified.

The strongest usable evidence is more modest. AlphaFold solved a major prediction problem with experimentally competitive accuracy in a blind assessment ([Jumper and colleagues, empirical](https://www.nature.com/articles/s41586-021-03819-2)) and expanded the database of predicted structures to more than 214 million ([Barrio-Hernandez and colleagues, empirical](https://www.nature.com/articles/s41586-023-06510-w)). A 2026 economic study found that this changed what structural biologists worked on: research on previously unstructured proteins increased 15 to 40 percent, but experimental structure determination barely changed and the authors found no downstream shift yet in early drug development ([Hill and Stein, empirical working paper](https://www.nber.org/papers/w35143)). The tool accelerated access to an intermediate representation. It did not remove every later bottleneck.

My interpretation is that AI mostly changes the scarce part of the process. As prediction and literature search get cheaper, validation and scientific judgment are likely to absorb more of the work. Autonomous labs should increase demand for assays, reagents, machine-readable protocols, maintenance, and replication, while a larger supply of candidates will put more pressure on regulatory and commercial translation.

An AI that reads papers is unlikely to support the best company here. A durable business would cover the whole cycle from prediction through experimental test, record the results with good metadata, and charge for decisions that survive validation. Proprietary experimental results and integration into a customer's daily work are harder to replace than fluent prose.

My bottom line is conditional:

* A 10× reduction in time or cost for one stage, such as structure prediction, literature synthesis, or a standardized assay, is already credible in some settings.
* A 10× increase in validated discoveries per dollar within a carefully chosen closed loop may be achievable over five to ten years. No current study establishes it.
* A 10× increase in society-wide useful discoveries per scientist-year, including replication, translation, and adoption, is a multi-decade institutional project. The evidence does not justify promising it today.

## What exactly should become ten times faster?

Counting papers would be easy and mostly wrong. A language model can already increase text output without increasing knowledge. Patents are closer to application but vary enormously in value. Candidate molecules, predicted structures, and generated hypotheses are inputs to discovery, not discoveries by themselves.

I would define the target as **independently validated, decision-relevant knowledge that is used outside the team that produced it, per unit of time or money**. "Decision-relevant" includes a reliable negative result that kills a bad path. "Used" may mean changing a later experiment, entering a development program, informing a standard, or becoming part of a product. The exact endpoint should be chosen before a program begins.

There are four useful denominators, and any 10× claim should name one:

1. Calendar time, from a well-specified question to an independently validated answer.
2. Cost, per validated answer or per correct research decision.
3. Research labor, per scientist-year.
4. Social value, such as health, energy, or productivity produced by the resulting knowledge.

The first three can be measured inside a company. Social value often arrives years later and also depends on adoption, regulation, manufacturing, and luck.

A simple accounting identity helps. Useful discovery rate is the number of serious candidates generated, multiplied by the fraction tested, the fraction that survive a strong test, the fraction that replicate, and the fraction that are adopted, divided by time or cost. A tenfold result could come from a 2× improvement in choosing questions, a 2× increase in experimental throughput, a 1.5× improvement in reliability, and a 1.7× improvement in translation. That product is about ten. These numbers are an illustration, not an empirical estimate. The point is that a system can win without any single magical 10× step, and can lose if one downstream fraction collapses.

![An illustrative tenfold discovery loop composed of gains in question choice, experimental throughput, reliability, and translation](https://research.gmfoster.com/assets/illustrations/ten-times-scientific-discovery/01-framework-tenfold-loop.jpg)

This definition also prevents a common accounting trick. DeepMind's GNoME produced 2.2 million crystal structures predicted stable relative to prior datasets, with 381,000 entries on its updated convex hull ([Merchant and colleagues, empirical computational result](https://www.nature.com/articles/s41586-023-06735-9)). Those are computational candidates rather than 381,000 useful new materials. Synthesizability, purity, properties, scale-up, and demand remain downstream gates.

## Metascience is older than its current name

Metascience studies the production of science itself: how questions are chosen, people and money are allocated, experiments are performed, claims are evaluated, knowledge is communicated, and discoveries are translated. It overlaps with the sociology and economics of science, scientometrics, research-on-research, and science policy ([Fortunato and colleagues, scholarly review](https://doi.org/10.1126/science.aao0185)). The current movement adds an entrepreneurial question: can we deliberately build better institutions and tools rather than only describe the existing ones?

The postwar US system is a useful starting point. In 1945, Vannevar Bush argued in *Science, the Endless Frontier* that basic research required sustained public support while remaining largely in universities and research institutes ([official report](https://www.govinfo.gov/app/details/GOVPUB-PR32_400-e7966ee70a4f7b47f862431c9776f727)). Congress created the National Science Foundation in 1950 ([official NSF history](https://www.nsf.gov/about/history/narrative)), giving uncertain work with benefits too diffuse for one firm a durable source of finance.

The later ARPA model added active program management and explicit milestones. DARPA still asks every proposed program eight questions, including what is new, who cares, what it will cost, and what midterm and final "exams" will determine success ([official Heilmeier Catechism](https://www.darpa.mil/about/heilmeier-catechism)). This is institutional testimony about DARPA's method, not causal proof of superiority. Its contribution is to make a research program falsifiable as a program.

The Human Genome Project showed what coordinated scientific infrastructure could do. The consortium finished in 2003, more than two years early, at about $2.7 billion in 1991 dollars against a projected $3 billion, and produced a sequence covering about 99 percent of gene-containing regions at 99.99 percent accuracy ([NHGRI's completion announcement](https://www.genome.gov/11006929/2003-release-international-consortium-completes-hgp)). Its official history stresses technology development and open data sharing too ([NHGRI fact sheet](https://www.genome.gov/about-genomics/educational-resources/fact-sheets/human-genome-project)). The project combined a goal, measurement standard, consortium, and public data asset.

Automation has a longer history than the current wave of generative AI. In 2009, the Robot Scientist "Adam" autonomously generated and tested functional-genomics hypotheses in yeast. Its creators manually confirmed the conclusions and formally connected 6.6 million measurements to more than 10,000 research units ([King and colleagues, empirical](https://doi.org/10.1126/science.1165620)). They described the resulting science as modest but not trivial. In 2015, the successor system "Eve" integrated screening, hit confirmation, and active learning, and identified a previously known anticancer compound as an inhibitor of a malaria-parasite target ([Williams and colleagues, empirical](https://pmc.ncbi.nlm.nih.gov/articles/PMC4345494/)). Closed-loop AI science did not begin with large language models.

![A timeline of discovery systems from postwar science policy through robot scientists, AlphaFold, autonomous laboratories, and AI co-scientists](https://research.gmfoster.com/assets/illustrations/ten-times-scientific-discovery/02-timeline-discovery-systems.jpg)

The modern empirical metascience agenda crystallized around reliability. John Ioannidis's famous 2005 paper was an analytical model of conditions under which most claimed findings would be false, not a census proving that most science is wrong ([Ioannidis, theoretical argument](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)). The Open Science Collaboration later attempted direct replications of 100 psychology studies. Ninety-seven percent of the originals reported significant results, while 36 percent of replications did; replication effects were also smaller ([Open Science Collaboration, empirical](https://doi.org/10.1126/science.aac4716)). That result belongs to its sample and criteria, not to every field.

By 2018, a large interdisciplinary review could describe a mature "science of science" using digital records of funding, collaboration, publication, citation, and mobility to study regularities in scientific careers and teams ([Fortunato and colleagues, scholarly review](https://doi.org/10.1126/science.aao0185)). The entrepreneurial branch is newer. Michael Nielsen and Kanjun Qiu's 2022 essay calls for "metascience entrepreneurs" who test scalable changes to the social processes of science ([authors' argument](https://scienceplusplus.org/metascience/index.html)). Fast Grants, Focused Research Organizations, Arc Institute, new ARPA-style agencies, and private institutes all treat the organization of science as something to prototype.

## Is science actually slowing down?

There is real evidence for declining research productivity, but no single speedometer for science.

The most cited result is Bloom, Jones, Van Reenen, and Webb's analysis of research effort and output across semiconductors, agriculture, medicine, and firms. Holding the historical pace of Moore's law required more than 18 times as many researchers in the late period as in the early 1970s. Across their cases, research effort rose while output per researcher fell ([Bloom and colleagues, empirical](https://www.aeaweb.org/articles?id=10.1257/aer.20180338)). The caveat is essential: the 18x figure is not "science became 18 times harder." It is an estimate for maintaining a particular exponential trajectory in chip density, under the paper's researcher-input construction.

Benjamin Jones found a related "burden of knowledge" pattern: inventors became more specialized, worked in larger teams, and reached their first inventions later as the stock of prerequisite knowledge grew ([Jones, empirical and theoretical](https://academic.oup.com/restud/article-abstract/76/1/283/1577537)). Teams are one adaptation to deeper knowledge, but coordination costs then become part of the production function.

A different bibliometric study examined 45 million papers and 3.9 million patents and found that they became less likely to break with prior work from 1945 to 2010 ([Park, Leahey, and Funk, empirical](https://www.nature.com/articles/s41586-022-05543-x)). Its citation-based disruption index is clever but contestable. Citation practices change, and consolidating work can be valuable. The result is evidence about the direction of attention in the literature, not a direct measure of social value.

Reliability creates another drag. In a coordinated replication of 21 social-science experiments from *Nature* and *Science*, 13 produced a significant effect in the same direction, and replication effect sizes averaged about half the originals ([Camerer and colleagues, empirical](https://pubmed.ncbi.nlm.nih.gov/31346273/)). Those failures waste follow-on effort, but it would also be wrong to apply the 62 percent result to physics, genomics, or chemistry.

The machinery around experiments consumes time too. A survey linked to Australia's 2012 health-research grant round estimated an average of 34 working days of researcher time per proposal, 550 researcher-years across the round, and no association between more preparation time and success ([Herbert and colleagues, observational](https://bmjopen.bmj.com/content/3/5/e002800)). Survey recall and the Australian setting limit generalization. The opportunity cost is nevertheless concrete.

Science produces far more knowledge, papers, and patents than it once did, with far more researchers. Across several important measures, however, those additional people and dollars have not produced proportional gains. Search, incentives, reliability, and coordination all leak effort, which leaves room for better tools and institutions.

## What metascience interventions have evidence behind them?

### Give exceptional people time, freedom, and tolerance for failure

Howard Hughes Medical Institute investigators receive longer-horizon, person-centered support with more freedom than a typical project grant. A quasi-experimental comparison found that HHMI investigators produced high-impact work at a higher rate than matched NIH-funded scientists and shifted toward more novel research directions ([Azoulay, Graff Zivin, and Manso, empirical](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1756-2171.2011.00140.x)). Selection cannot be eliminated as an explanation, even with matching and difference-in-differences methods, but this is stronger evidence than founder anecdotes.

NIH created its own High-Risk, High-Reward programs, starting with the Pioneer Award in 2004. NIH's retrospective says Pioneer work was judged more innovative and higher impact than comparable R01 work and that the program then expanded ([NIH institutional evaluation summary](https://pmc.ncbi.nlm.nih.gov/articles/PMC5101933/)). Because the funder is evaluating itself and bibliometric comparisons are imperfect, this is supportive rather than definitive evidence.

Fast Grants tested speed during Covid-19. In the organizers' follow-up survey, 32 percent of respondents said the grant accelerated work by a few months, 64 percent said the work would not have happened without it, and 78 percent said they would change their research program "a lot" if existing funds were unconstrained ([Collison, Cowen, and Hsu, first-person retrospective and recipient survey](https://marginalrevolution.com/marginalrevolution/2021/06/what-we-learned-doing-fast-grants.html)). These are self-reports from recipients, with no control group. They show demand for fast, flexible money, not the long-run scientific return.

### Review the question and method before the result exists

Registered Reports move peer review and in-principle acceptance before data collection, making publication less dependent on a positive result. In a comparison of 71 Registered Reports and 152 standard psychology papers, 44 percent of the first hypotheses in Registered Reports were supported versus 96 percent in standard reports ([Scheel, Schijen, and Lakens, empirical observational comparison](https://journals.sagepub.com/doi/10.1177/25152459211007467)). The design does not prove that the difference is entirely publication bias, but it reveals how unusual the conventional literature's positivity rate is.

A blinded evaluation asked 353 researchers to compare 29 Registered Reports with 57 conventional papers. Registered Reports scored higher on methodological rigor, analysis, and overall quality, while novelty and creativity were statistically indistinguishable ([Soderberg and colleagues, empirical](https://www.nature.com/articles/s41562-021-01142-4)). This is early evidence in psychology and neuroscience, not a universal mandate, but reliability did not appear to reduce novelty.

### Build missing infrastructure with a temporary organization

Focused Research Organizations are designed as time-bounded teams that build tools, datasets, and platforms that are too coordinated for an academic lab and too public-good-oriented for a startup. Convergent Research says it has secured almost $400 million since 2021 and launched almost a dozen FROs ([Convergent Research, institutional first-person account](https://www.convergentresearch.org/about)). This is evidence that the model can attract funding and form organizations. It is too early, and too self-reported, to know its average scientific return.

FROs give a name to a neglected middle: projects that need a coordinated team working toward one measurable artifact for several years, but do not yet have a venture-scale customer ([Convergent Research, institutional first-person account](https://www.convergentresearch.org/about)). The Human Genome Project occupied a much larger version of this institutional space.

## What AI can do at each stage

The evidence changes sharply from one stage of the research loop to the next, as do the ways each stage can fail.

| Stage | Best demonstrated result | What it does not yet show |
|---|---|---|
| Literature and synthesis | PaperQA2 matched or exceeded domain experts on several bounded retrieval, summary, and contradiction tasks ([Skarlinski and colleagues, empirical preprint](https://arxiv.org/abs/2409.13740)) | That it can judge importance, detect every bad source, or produce a novel discovery |
| Hypothesis generation | DeepMind's Co-Scientist generated drug-repurposing hypotheses that showed activity in AML cell lines ([Gottweis and colleagues, empirical](https://www.nature.com/articles/s41586-026-10644-y)) | Efficacy in animals or humans, or a measured improvement over expert teams across projects |
| Prediction | AlphaFold achieved accuracy competitive with experiments for many proteins in CASP14 ([Jumper and colleagues, empirical](https://www.nature.com/articles/s41586-021-03819-2)) | Protein function, dynamics, drug success, or clinical benefit by itself |
| Formal search and design | FunSearch found a new cap-set construction and better bin-packing heuristics ([Romera-Paredes and colleagues, empirical](https://www.nature.com/articles/s41586-023-06924-6)) | Broad autonomous reasoning in domains without a cheap, exact evaluator |
| Experiment planning and control | Coscientist planned and executed several chemistry tasks through search, code, and lab APIs ([Boiko and colleagues, empirical](https://www.nature.com/articles/s41586-023-06792-0)) | An unattended general chemist; plates were sometimes moved manually and tasks were bounded |
| Closed-loop laboratory work | A-Lab synthesized 36 of 57 target inorganic materials over 17 days ([Szymanski and colleagues, empirical](https://www.nature.com/articles/s41586-023-06734-w)) | Pure, useful, scalable materials, or a comparison with an equally resourced human lab |
| Translation | An AI-discovered and AI-designed molecule, rentosertib, completed a randomized phase 2a trial in 71 patients ([Xu and colleagues, empirical](https://www.nature.com/articles/s41591-025-03743-2)) | Regulatory approval or clinical efficacy; the primary endpoint was safety and the trial was small |

AI is strongest where structured data are abundant and a trustworthy evaluator can reject bad answers quickly. Protein structures can be compared with blind experimental targets ([AlphaFold, empirical](https://www.nature.com/articles/s41586-021-03819-2)), matrix-multiplication algorithms can be proved correct and timed ([AlphaTensor, empirical](https://www.nature.com/articles/s41586-022-05172-4)), cap sets can be checked ([FunSearch, empirical](https://www.nature.com/articles/s41586-023-06924-6)), and predicted material energies can be computed ([GNoME, empirical computational result](https://www.nature.com/articles/s41586-023-06735-9)). In each case, the system receives a clear reward signal.

FunSearch pairs a language model's proposals with an evaluator that rejects wrong programs. On the hard eight-dimensional cap-set task, only four of 140 runs found the best 512-element construction ([empirical result and robustness detail](https://www.nature.com/articles/s41586-023-06924-6)). Cheap rejection of bad answers makes the system useful despite unreliable proposals.

Biology has slower evaluators. FutureHouse's Robin generated hypotheses, proposed experiments, analyzed data, and iterated toward two candidates that increased phagocytosis in retinal pigment epithelial cells. Its authors estimate that the cognitive work fell from a range of 359 to 424 human hours to under two, while humans executed the physical experiments ([Ghareeb and colleagues, empirical demonstration plus modeled comparison](https://www.nature.com/articles/s41586-026-10652-y)). The candidates are in-vitro findings, not treatments, and the time estimate is not a randomized trial.

DeepMind's Co-Scientist provides an independent example. For acute myeloid leukemia, three of five expert-selected drugs from its ranked hypotheses inhibited viability in tested cell lines. A separately proposed compound, KIRA6, showed selective activity in one AML line relative to a nonmalignant control ([Gottweis and colleagues, empirical](https://www.nature.com/articles/s41586-026-10644-y)). These are initial reality checks, not substitutes for preclinical or clinical validation.

A neural network screened more than 107 million molecules and identified halicin, a structurally unusual antibiotic active against multiple pathogens and effective in mouse infection models ([Stokes and colleagues, empirical](https://pmc.ncbi.nlm.nih.gov/articles/PMC8349178/)). That meaningful discovery has not produced an approved antibiotic.

A-Lab reports 36 successful targets out of 57, a 63 percent target success rate, but only 30 percent of 353 individual recipes produced their target. Some products contained prominent byproducts, and four more outcomes were inconclusive by X-ray diffraction ([Szymanski and colleagues, empirical](https://www.nature.com/articles/s41586-023-06734-w)). "17 days" and "36 materials" are meaningful only beside that success definition.

The withdrawn Toner-Rodgers study claimed that AI automated 57 percent of idea-generation tasks and helped top scientists more than their less productive colleagues ([withdrawn abstract](https://arxiv.org/abs/2412.17866)). Those results would support a story in which AI complements judgment, but the withdrawal means they are a hypothesis to test, not evidence to cite as settled.

## Where the bottlenecks move

### Validation capacity

Hypotheses and designs are becoming cheaper faster than trustworthy tests. In my assessment, validation is the most important under-invested layer. Independent replication is rarely a prestige product, and venture investors cannot easily capture its broad social value. Without enough testing capacity, an AI-generated flood can lower the average quality of the literature even while increasing the number of true findings.

This points to domain-specific validation infrastructure: standardized assays, reference materials, blinded replication networks, adversarial measurement, and evidence packages that downstream users trust. The Center for Open Science's SCORE program evaluated 3,900 claims and found that about half were precisely computationally reproduced and roughly three quarters approximately reproduced; reproducibility was higher where journals required data sharing ([SCORE, institutional report of empirical program results](https://www.cos.io/score)). I read that result as evidence for better data practice and as a reason to test whether customers will pay for validation services.

### Machine-actionable data and protocols

Most scientific records were written for human readers, not for software to rerun. Methods omit tacit details. Negative experiments disappear. Instrument metadata and sample provenance live in incompatible systems. The Robot Scientist work's less glamorous achievement was a formal structure linking millions of measurements to hypotheses and procedures ([King and colleagues, empirical](https://doi.org/10.1126/science.1165620)). That kind of semantic plumbing is a precondition for reliable autonomous work.

My explanation for the underinvestment is that the benefits spill across labs while the cleanup cost lands on the lab producing the data. A company can capture value only if it makes structured capture the easiest way to do the work, rather than asking scientists to perform extra curation for an abstract future benefit.

### Flexible physical automation

Liquid handling is mature for repetitive tasks. General laboratory work is not. Solids, irregular containers, instrument exceptions, contamination, calibration, and protocol changes require hands and judgment. Even A-Lab reports hardware exceptions and manual replenishment ([A-Lab, empirical](https://www.nature.com/articles/s41586-023-06734-w)), while Coscientist's demonstration still required some manual plate transfers ([Coscientist, empirical](https://www.nature.com/articles/s41586-023-06792-0)). In my assessment, modular reliability is under-invested: instrument drivers, error recovery, calibration standards, and reusable interfaces across vendors.

### Benchmarks tied to downstream truth

An AI can score well on questions extracted from papers while failing to choose an important question or design a decisive experiment. Scientific benchmarks also risk contamination because their answers appear in training corpora, one of several evaluation problems surveyed in a 2023 AI-for-science review ([Zitnik and colleagues, scholarly review](https://doi.org/10.1038/s41586-023-06221-2)). Evaluations are most informative when they use prospective, hidden, expensive ground truth: a blinded structure contest, a future experiment, an independent replication, a patent that survives, or a product prototype.

The AlphaFold economic study is a model for the next generation of evaluation because it measures how scientists and downstream outputs change ([Hill and Stein, empirical working paper](https://www.nber.org/papers/w35143)). The withdrawn Toner-Rodgers paper shows why future field experiments also need auditable data, preregistration where possible, and independent scrutiny ([withdrawal notice](https://arxiv.org/abs/2412.17866)). Those conclusions will be more modest than a benchmark leaderboard and more useful.

### Translation and diffusion

Translation affects the denominator above because validated results may sit unused. A drug candidate still faces toxicology, manufacturing, trials, regulation, reimbursement, and clinical adoption. A new material needs synthesis, characterization, scale-up, qualification, and a customer willing to redesign a product. The lack of a downstream AlphaFold drug-development shift so far, despite a 15 to 40 percent research response, is direct evidence that an upstream breakthrough can meet a slower translational system ([Hill and Stein, empirical working paper](https://www.nber.org/papers/w35143)).

In commercial terms, translation has assets that are difficult to reproduce: regulatory knowledge, longitudinal data, customer integration, and costly physical execution.

![The scientific discovery pipeline showing how faster literature search and prediction can move the bottleneck into validation and translation](https://research.gmfoster.com/assets/illustrations/ten-times-scientific-discovery/03-flowchart-moving-bottleneck.jpg)

### Causal metascience itself

Many new science institutions publish persuasive theories of change but cannot say what would have happened without them. FROs ([Convergent Research, institutional account](https://www.convergentresearch.org/about)), fast grants ([organizers' retrospective](https://marginalrevolution.com/marginalrevolution/2021/06/what-we-learned-doing-fast-grants.html)), lotteries, prizes, person grants, and ARPA programs should be treated as experiments with predeclared outcomes and comparison groups where possible. Otherwise the field dedicated to improving science will reproduce science's own measurement problems.

## Who is trying, and what is actually a company?

Agencies, nonprofits, institutes, software firms, research services, and product companies all appear in lists of AI-for-science organizations, although they finance different work and produce different outputs.

Government agencies such as DARPA, ARPA-E, ARPA-H, and the UK's ARIA fund programs where the output may be a public capability. Nonprofits and institutes such as FutureHouse, Arc Institute, and Convergent Research can build open tools or pursue work with weak near-term appropriability. Convergent explicitly says that if a project can be a startup without distorting its mission, it probably should be, because venture capital is more abundant than philanthropic capital ([institutional guidance](https://www.convergentresearch.org/get-involved)).

Schrödinger combines scientific software and simulation with a drug-discovery group. Its 2025 filing reports $199.5 million in software revenue and $56.4 million in drug-discovery revenue, and describes collaboration economics that include upfront payments, research fees, milestones, and royalties ([SEC filing, audited company disclosure](https://www.sec.gov/Archives/edgar/data/1490978/000149097826000010/sdgr-20251231.htm)). This is the clearest mature hybrid model I found.

In AI-native drug discovery, Isomorphic Labs announced $45 million upfront from Lilly and $37.5 million from Novartis for multi-target collaborations ([company first-person announcement](https://www.isomorphiclabs.com/articles/isomorphic-labs-kicks-off-2024-with-two-pharmaceutical-collaborations)). Recursion, Insilico Medicine, Generate Biomedicines, and others combine partnerships with owned pipelines. Platform claims remain institutional testimony unless experiments validate them.

Lila Sciences and Periodic Labs are coupling AI with autonomous laboratories. Lila announced $200 million in seed commitments to build models and "AI Science Factories" ([company first-person announcement](https://www.lila.ai/news/join-our-mission)), while Periodic says it is building AI scientists and autonomous labs in physical science ([company first-person strategy](https://periodic.com/)). These pages establish funding and ambition, not scientific acceleration.

FutureHouse took a nonprofit route to research agents. It developed PaperQA2 and Robin and exposes agents through a platform. Its phrase "superintelligent scientific agents" is marketing, not an empirical category ([institutional first-person announcement](https://www.futurehouse.org/news/launching-futurehouse-platform-ai-agents)).

Emerald Cloud Lab sells remotely programmable laboratory operations and appeared as the physical execution layer in Coscientist's paper. The paper establishes that an agent could use its interface for bounded tasks ([Boiko and colleagues, empirical](https://www.nature.com/articles/s41586-023-06792-0)); it does not establish the economics of a general cloud lab.

My survey found a dense cluster of companies calling themselves "AI for drug discovery." Validated scientific data, flexible lab execution, replication services, and translation infrastructure across multiple customers had fewer obvious entrants.

## Six ways a company could make money

### 1. Sell workflow software to R&D organizations

Pharmaceutical, materials, chemical, agricultural, and industrial R&D teams already buy software per seat, per compute unit, or through enterprise subscriptions when it reduces scientist time or expensive failed experiments. Integration with proprietary data, instruments, permissions, and decision workflows makes the software harder to switch away from. Schrödinger's filing shows that scientific software can be a substantial revenue business and that hosted subscriptions can grow inside large pharmaceutical customers ([SEC filing](https://www.sec.gov/Archives/edgar/data/1490978/000149097826000010/sdgr-20251231.htm)).

A thin interface over a general model is easy for competitors to reproduce unless it is tied to experiments or deeply embedded in the customer's work.

### 2. Sell experiments and validated answers as a service

Labs and R&D companies can outsource an assay, synthesis campaign, replication, or evidence package instead of building the infrastructure. A provider can charge per run, per campaign, or for reserved capacity. Its defense is operational: validated protocols, instrument utilization, turnaround time, quality systems, and an outcome dataset that improves future selection.

This resembles a contract research organization whose planning and scheduling are handled by software. It fits experiments standardized enough to automate but expensive enough that yield matters.

### 3. Take upfront payments, milestones, and royalties

An incumbent that already owns development and distribution may pay an AI company to contribute targets, molecules, or designs. The supplier receives research funding, payments when programs advance, and royalties if a product sells. Isomorphic's Lilly and Novartis agreements and Schrödinger's collaboration structure show the model in practice ([Isomorphic institutional announcement](https://www.isomorphiclabs.com/articles/isomorphic-labs-kicks-off-2024-with-two-pharmaceutical-collaborations), [Schrödinger SEC filing](https://www.sec.gov/Archives/edgar/data/1490978/000149097826000010/sdgr-20251231.htm)).

Payments rise as a program advances, but they arrive irregularly and depend on slow-moving partners. The company needs to produce assets that partners repeatedly choose to advance; using AI does not by itself distinguish the supplier.

### 4. Own the resulting products

The company develops its own drug, material, enzyme, or industrial process. Patents or manufacturing know-how protect the return. This captures the most upside and requires the most capital, turning a platform into a sector-specific product company.

Rentosertib is a useful marker. It shows an AI-originated asset can reach phase 2a, but its small safety-focused trial is still far from proving that AI improves portfolio-level clinical success ([Xu and colleagues, empirical](https://www.nature.com/articles/s41591-025-03743-2)).

### 5. Sell evidence assurance

The customer is whoever bears the cost of a wrong scientific claim, perhaps a pharmaceutical buyer, insurer, regulator, investor, journal, grantmaker, or R&D executive. The product is an auditable combination of provenance, computational reproduction, protocol review, independent experiment, and ongoing monitoring. A language model's confidence score is not enough.

Because beneficiary and budget owner often differ, an initial customer is easiest to find around a high-cost decision such as licensing a molecule or qualifying a material, where one false positive costs more than verification.

### 6. Build a proprietary record of experiments

Each paid experiment can produce standardized positive and negative outcomes that improve later selection and yield. That record would strengthen the other business models. Periodic and Lila describe autonomous experiments as new training data ([Periodic institutional strategy](https://periodic.com/), [Lila institutional strategy](https://www.lila.ai/news/join-our-mission)). Public evidence does not show that either company has built such a system.

If I were choosing one company thesis, I would build a domain-specific **validation laboratory**. It would accept candidates from human and AI teams, execute decisive tests under blinded protocols, and deliver evidence suitable for a partner's licensing or development decision. It could charge per campaign, add workflow software, and selectively take milestones or rights. Its record of negative results, assay performance, and failure modes would be difficult to reproduce. Starting with one narrow assay family would make results comparable across customers and over time.

![A validation laboratory turning candidates from human and AI teams into auditable evidence for licensing and development while retaining positive and negative results](https://research.gmfoster.com/assets/illustrations/ten-times-scientific-discovery/04-framework-validation-laboratory.jpg)

## A practical program for trying to get to 10×

1. Choose a domain with a short truth loop. Protein expression optimization, enzyme design, cell-line perturbation, inorganic synthesis, catalysis, or a class of materials assays are better starting points than a twenty-year clinical endpoint. The domain needs measurable outcomes, many iterations, and enough economic value per correct answer.

2. Establish a prospective baseline before introducing AI. Measure median calendar time, fully loaded cost, number of candidates, experiment success, independent replication, and downstream decisions for the current human workflow. Randomize access when practical, preregister the analysis, preserve failures, and make the audit trail available to independent reviewers.

3. Build the full loop. Retrieval, hypothesis generation, experiment selection, robotics, analysis, provenance, and replication should share one data model. Humans should control objectives, safety, and exceptions.

4. Reserve a fixed fraction of capacity for adversarial validation. Repeat results with different operators, instruments, reagent lots, or sites. A pipeline that becomes 10× faster at producing fragile results is worse than the baseline.

5. Track cost and time per independently validated finding; the share of proposed experiments that yield decision-quality information, including useful negatives; external replication and effect-size shrinkage; time to first outside use; how gains are distributed across scientists; and safety incidents, protocol deviations, or unreported human interventions.

6. Make staged claims. "10× faster literature review" can be true while "10× faster discovery" is false. Report the narrow result, the downstream gates still open, and the denominator. Advance from tool benchmark to prospective experiment to independent replication to economic output.

Over five years, success would mean one domain showing a sustained several-fold improvement in validated decisions per dollar, with no loss in replication. Reaching tenfold across society would also require changes in funding, data, experiments, translation, and diffusion. The scope makes this a bigger problem than any one piece of software can solve.

## Principles I would carry into a company or fund

1. Evaluate the full process rather than the most impressive demonstration. AlphaFold changed an upstream constraint, while downstream drug activity had not yet shifted in the 2026 study. A company should own or partner through the next bottleneck.
2. Cheap evaluators make some domains better suited to AI. FunSearch, AlphaTensor, and structure prediction benefit from wrong answers being easy to reject ([FunSearch, empirical](https://www.nature.com/articles/s41586-023-06924-6), [AlphaTensor, empirical](https://www.nature.com/articles/s41586-022-05172-4), [AlphaFold, empirical](https://www.nature.com/articles/s41586-021-03819-2)). Evaluators and assays deserve heavy investment.
3. Consistently recorded negative data can improve later decisions. Published literature selects positive results, while a closed lab can learn from every failure.
4. Human judgment remains part of the system. Robin's researchers still executed the physical experiments, and Co-Scientist was built around an expert-in-the-loop workflow ([Robin, empirical demonstration](https://www.nature.com/articles/s41586-026-10652-y), [Co-Scientist, empirical demonstration](https://www.nature.com/articles/s41586-026-10644-y)). The organization should make that division of work explicit.
5. Shared datasets, standards, and field-wide tools may be public goods that need philanthropy or government support. A startup needs a specific payer and a legal or operational way to retain some of the value it creates.
6. Portfolios fit scientific outcomes because the returns are heavy-tailed. Milestones should kill weak paths quickly without forcing every project to promise a predictable result.
7. New grants, institutes, and workflows should be experiments themselves. Their outcomes should be declared in advance, with counterfactuals measured where possible.
8. Stage-level improvements should not be multiplied without checking the handoffs. A 100× candidate generator followed by a 1 percent validation rate does not produce a 100× discovery engine.

## Further reading from primary sources

* Vannevar Bush, [*Science, the Endless Frontier*](https://www.govinfo.gov/app/details/GOVPUB-PR32_400-e7966ee70a4f7b47f862431c9776f727) (1945 official report).
* Benjamin Jones, [The Burden of Knowledge and the "Death of the Renaissance Man"](https://academic.oup.com/restud/article-abstract/76/1/283/1577537) (2009 empirical and theoretical paper).
* Pierre Azoulay, Joshua Graff Zivin, and Gustavo Manso, [Incentives and Creativity](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1756-2171.2011.00140.x) (2011 quasi-experimental funding study).
* Open Science Collaboration, [Estimating the Reproducibility of Psychological Science](https://doi.org/10.1126/science.aac4716) (2015 replication project).
* Santo Fortunato and colleagues, [Science of Science](https://doi.org/10.1126/science.aao0185) (2018 field review).
* Nicholas Bloom and colleagues, [Are Ideas Getting Harder to Find?](https://www.aeaweb.org/articles?id=10.1257/aer.20180338) (2020 empirical productivity study).
* Anne Scheel, Mitchell Schijen, and Daniel Lakens, [An Excess of Positive Results](https://journals.sagepub.com/doi/10.1177/25152459211007467) (2021 Registered Reports comparison).
* Marinka Zitnik and colleagues, [Scientific Discovery in the Age of Artificial Intelligence](https://doi.org/10.1038/s41586-023-06221-2) (2023 technical review).
* Ryan Hill and Carolyn Stein, [How Artificial Intelligence Shapes Science: Evidence from AlphaFold](https://www.nber.org/papers/w35143) (2026 economic working paper).
* Ali Ghareeb and colleagues, [A Multi-Agent System for Automating Scientific Discovery](https://www.nature.com/articles/s41586-026-10652-y) (2026 Robin paper).
* Juraj Gottweis and colleagues, [Accelerating Scientific Discovery with Co-Scientist](https://www.nature.com/articles/s41586-026-10644-y) (2026 hypothesis-generation and validation paper).

## Claims I could not verify

I could not verify any study showing a tenfold increase in the useful rate of an entire scientific field. I therefore treat 10× as a design target, never as an observed or forecast result.

I could not verify the widely repeated productivity results in Aidan Toner-Rodgers's materials-science working paper. ArXiv administrators withdrew it in May 2025 because of concerns about data validity and incomplete institutional-review requirements. I describe its numbers only as claims from a withdrawn abstract, not as empirical evidence.

I could not verify a universal "reproducibility crisis" percentage for science. The 36 percent and 62 percent figures above are reported only with their domains, samples, and criteria. The claim that "most science is false" is explicitly identified as a result from a theoretical model, not a census.

I could not verify popular claims that AlphaFold "saved a billion years," saved a particular number of researcher-years, or directly produced a large number of drugs. I use its blind structure-prediction result, database size, and the measured downstream research response instead.

I could not verify general claims that self-driving laboratories accelerate discovery by 100× or 1,000×. I report the tasks, elapsed time, target counts, recipe success, manual work, and outcome definitions in the papers I could inspect.

I could not verify an approved drug whose clinical success was caused by an end-to-end AI discovery system. Rentosertib reached a small phase 2a trial, which is the strongest clinical-stage example I found, and is labeled accordingly.

I could not independently verify the scientific productivity claims of Lila Sciences or Periodic Labs from published outcome data. Their funding, strategy, and company descriptions are labeled as first-person institutional claims.

I also could not verify that any current AI-for-science company has built a durable, profitable system that improves with each experiment. Schrödinger's audited filing demonstrates meaningful software and collaboration revenue, alongside continued operating losses. The models above explain how a firm might be paid; they do not predict that any named company will succeed.
