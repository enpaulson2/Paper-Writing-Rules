# Adaptive Block SCA — Writing Rules
**Document label:** IoT Journal Writing Rules  
**Central repository:** `enpaulson2/Paper-Writing-Rules`  
**Canonical location:** `IoT_Journal/Adaptive_Block_SCA_Writing_Rules.md`  
**Rule set:** `Adaptive_Block_SCA_Writing_Rules.md`  
**Target journal:** IEEE Internet of Things Journal  
**Target paper:** Adaptive Block SCA for Resource Optimization in Multibeam LEO Satellite–Terrestrial Networks  
**Version:** 1.0 — approved direction consolidated 2026-11-12  

## Purpose, hierarchy, and transfer policy
These rules govern writing and editing the specified manuscript. For future papers, copy this document, replace paper-specific terms and evidentiary constraints, and explicitly approve any changed rules. Follow: (1) authors' latest express decisions; (2) scientific evidence and mathematical correctness; (3) the current journal's author requirements and IEEE conventions; (4) this rulebook; (5) stylistic examples. A style example never authorizes copying another article's scientific results, claims, equations, or unsupported metadata.

**Sources of transferable practice**
- `FINAL VERSION.tex`: accepted *Extended DL Coverage in SAGIN: Cell Association and Resource Allocation with Beam Hopping LEO*; primary IEEEtran/author-block, presentation, literature-comparison-table and figure-format reference.
- `Final Accepted.tex`: accepted *Distributed Two-Timescale Online Optimization Framework for LEO Space–Ground Task Offloading under Time-Varying Connectivity*; preferred analytical exposition, category-based Related Work, explicit assumptions, systematic evaluation.
- `enpaulson2/IEEE-TWC-DRL/bibliography.bib`: examples of official publication abbreviations, conference proceedings, conference city/country and month/year fields. Existing entries are examples to audit, not guaranteed accurate.
- TAES decision letter in the current paper repository: problem-specific revision requirements and evidence gaps.

## A. Academic language and claim calibration
- **WR-01:** Avoid *must*, *can*, *will*, *shall* and other categorical or predictive modal verbs in manuscript prose. Prefer *should*, *would*, *may*, *could* when genuinely discussing conditional behavior, recommendations, and uncertainty. Do not mechanically insert weak modals into factual statements or equations; use precise declarative present tense for established operations, definitions, and results. Preserve any mandatory wording needed to quote an external standard or state a mathematically necessary condition unambiguously.
- **WR-02:** Express algorithm operations directly in present tense: “The algorithm updates…”, “The constraint limits…”, “The results show…”. Use past tense for specific completed experiments where appropriate.
- **WR-03:** Avoid speculative performance claims, rhetorical marketing, absolute superiority or unsupported adjectives: *optimal*, *guaranteed*, *always*, *significantly*, *state-of-the-art*, *robust*, *scalable*, *efficient*, unless precisely substantiated.
- **WR-04:** Avoid filler and formulaic bridges (*Nowadays*, *It is well known*, *It is worth noting*, *Overall*, *Together*, gratuitous end-of-section transition sentences).
- **WR-05:** Prefer technically complete, compact sentences; one clear technical purpose per paragraph. Avoid repetition, circular definitions, excessive nominalizations, and restating an equation without interpretation.
- **WR-06:** Expand acronyms at first use and apply consistent abbreviations, symbols, case and compound adjectives throughout.
- **WR-07:** Calibrate verbs to evidence: mathematical derivation *establishes* only proved claims; numerical figures *show/indicate* tested trends; hypotheses *may/could* hold only under stated conditions.
- **WR-08:** Do not copy unnatural or unsupported wording from accepted reference papers. Their historical uses of *can/will* do not override WR-01.

## B. Introduction and contributions
- **INTRO-01:** Progress from satellite–terrestrial network context to multibeam LEO resource constraints, actual interference/power coupling, specific gap, problem scope, and contributions.
- **INTRO-02:** Keep IoT relevance in the service-architecture and practical motivation; do not present an unmodeled IoT-specific traffic profile or terrestrial optimization result.
- **INTRO-03:** Make the gap narrow and demonstrable. Do not claim no previous work addresses an area without an exhaustive comparison.
- **INTRO-04:** Contributions distinguish: original resource-allocation formulation; existing adaptive block SCA mechanism; valid mathematical/complexity discussion; actual evaluation evidence. Never present literature review or ordinary SCA itself as a new invention.
- **INTRO-05:** Match every contribution with the appropriate actual method, equation, analytical argument or existing figure.
- **INTRO-06:** State architecture boundaries clearly: satellite access power is optimized; a terrestrial service segment may contextualize access, but terrestrial powers, gateway scheduling or cross-domain control are not jointly optimized unless explicitly modeled.

## C. Related Work rules
- **RW-01:** Structure by research question/method family, not chronology or a disconnected one-paper-per-sentence catalogue.
- **RW-02:** Preferred relevant groups: multibeam LEO power/resource optimization; interference management and beam-level coordination; SCA and iterative surrogate optimization; dynamic satellite–terrestrial and IoT-service architectures. Adapt only to truly relevant sources.
- **RW-03:** For each important paper, record its objective, decision variables, scenario, principal technique, assumptions and verifiable analytical/empirical scope.
- **RW-04:** Compare methods fairly; differences in research scope are not evidence of deficiency. Distinguish satellite-only, integrated satellite–terrestrial, and jointly optimized satellite/terrestrial formulations.
- **RW-05:** Maintain a focused literature-comparison table modeled on the accepted papers, with columns relevant to this paper (e.g., network setting, interference modeling, decision variables, constraint type, adaptation method, guarantee type). Every entry and check mark requires evidence.
- **RW-06:** Group references with the same relevant point; discuss particular papers individually where method or novelty distinctions materially matter.
- **RW-07:** Each literature paragraph should contribute to positioning the present research; synthesize the exact open issue at the end without unqualified “none of the literature” claims.
- **RW-08:** Do not assert numerical superiority over a prior article unless its scheme was actually included in the retained benchmark experiment.
- **RW-09:** The two archived bibliography pools and author papers provide candidates, not automatically approved citations. Check original papers before making detailed limitation claims.

## D. Bibliography, referencing, and citation formatting
- **REF-01:** Prioritize directly relevant peer-reviewed IEEE sources; emphasize IEEE Internet of Things Journal, IEEE Transactions on Wireless Communications, IEEE Transactions on Communications, IEEE Transactions on Vehicular Technology, IEEE Transactions on Aerospace and Electronic Systems, IEEE Journal on Selected Areas in Communications, and appropriate IEEE standards/surveys.
- **REF-02:** Aim for approximately 35 genuinely relevant sources, including approximately 10 IEEE IoT-J studies where warranted. Relevance, accuracy and coverage take precedence over artificial counts; both targets may be revised by author decision.
- **REF-03:** Retain relevant foundational papers and prioritize current research where its methods and assumptions match the present study.
- **REF-04:** Every journal record should carry full verified author list, exact published article title, **official abbreviated IEEE journal name**, final volume, issue, pages or article identifier, **publication month and year**, where the publisher has assigned them.
- **REF-05:** Every conference record should carry verified authors/title, standard abbreviated proceedings title, **conference city and country**, **month and year of the actual conference edition**, and page range or article identifier where available. Include day-range if readily verified and germane. Do not infer a location from a different year's edition or from organizer headquarters.
- **REF-06:** A journal's online/early-access posting year and final volume-issue year are not interchangeable. When the final issue is assigned, use its final issue metadata. For genuine early-access entries, label that status and do not invent volume/issue/pages or a month not documented.
- **REF-07:** Maintain IEEE-formatted standard abbreviations, e.g., `IEEE Internet Things J.`, `IEEE Trans. Wireless Commun.`, `IEEE Trans. Commun.`, `IEEE Trans. Veh. Technol.`, `IEEE Trans. Aerosp. Electron. Syst.`, `IEEE J. Sel. Areas Commun.`, `IEEE Wireless Commun. Lett.`; use `Proc.` and the appropriate official conference abbreviation in conference entries.
- **REF-08:** Preserve official spelling and capitalization of titles, and protect acronyms in BibTeX with braces (e.g., `{LEO}`, `{IoT}`, `{SCA}`, `{ISTN}`).
- **REF-09:** Keep citation keys stable, unique and descriptive when feasible; avoid duplicate entries and conflicting metadata for the same publication.
- **REF-10:** Cite close to the specific claim supported; avoid excessive undifferentiated citation clusters or citations implying support for a claim the source does not make.
- **REF-11:** Cite the authors' previous work when technically relevant, without padding or claiming another paper's results as results of the current work.
- **REF-12:** Use `\bibliographystyle{IEEEtran}` and consistent numerical IEEE citations via `\cite{...}` or corresponding IEEE style; check rendered order, punctuation and abbreviations after compilation.
- **REF-13:** Mandatory pre-submission audit per entry: authors; title; venue; standard abbreviation; year and month; volume/issue; pages/article number; conference location/date; duplicates; citation-key correctness. Missing publisher-supplied fields should be marked as unavailable, not fabricated.
- **REF-14:** DOI is **not a required field or audit criterion** in this rulebook. Do not remove previously correct data from source bibliographies solely because DOI is optional. This rulebook deliberately imposes no DOI-completeness target.
- **REF-15:** Reference examples inherited from the two accepted IoT-J articles or the DRL bibliography require independent checking; neither is assumed error-free.

**Illustrative IEEE journal entry format** (placeholder publication): A. B. Author and C. D. Author, “Paper title,” *IEEE Trans. Wireless Commun.*, vol. xx, no. x, pp. xxx–xxx, Mon. YYYY.

**Illustrative IEEE conference entry format** (placeholder publication): A. B. Author and C. D. Author, “Paper title,” in *Proc. IEEE Global Commun. Conf. (GLOBECOM)*, City, Country, Mon. YYYY, pp. xxx–xxx.

## E. Mathematical model, optimization and algorithm
- **MATH-01:** Define every set, index, parameter, decision variable and unit at first use. Never reuse a symbol for conflicting quantities.
- **MATH-02:** Explain the physical meaning and timing of a state observation, especially channel/interference indicators, before introducing its dependence in the objective or algorithm.
- **MATH-03:** Distinguish precomputed/fixed link-condition weights from interference that depends on trial power values. Avoid differentiating or optimizing an indicator that is assumed exogenous.
- **MATH-04:** Introduce the physical and mathematical motivation for each equation and constraint. Maintain traceability from the original system model to the surrogate and block update.
- **MATH-05:** Specify assumptions needed for first-order lower bounds, block optimization, regularization, feasibility, monotonicity or stationary-point convergence. Do not conflate local stationarity, convergence of objective values and global optimality.
- **MATH-06:** Analyze the complexity of the actual block variables and solution steps, distinguishing formal order from measured runtime.
- **MATH-07:** Distinguish a logical coordinator with relevant channel state from a demonstrated distributed inter-satellite coordination protocol.
- **MATH-08:** Do not claim channel-model propagation terms, physical sensing signals, sensing-power constraints, power-flux-density compliance or latency equations were implemented without support in the original scientific record.
- **MATH-09:** Preserve model, objective, original SCA updates and experimental settings; change an equation only to resolve a clearly documented internal inconsistency and trace consequences.

## F. Performance evaluation and figure rules
- **PE-01:** No new simulations, numerical datasets, DRL baselines, convergence plots, runtime comparisons or additional experiments for this revision.
- **PE-02:** Retain existing figures and numerical values. Three approved future figures, if created, are **conceptual explanatory diagrams**, not additional results.
- **PE-03:** Use precise experimental variable names **number of users** and **number of LEO satellites** where those are the actual plotted dimensions.
- **PE-04:** Discuss actual communication rate and average latency, and only other directly documented original metrics. Do not claim measured IoT reliability, service quality, fairness, network scalability, terrestrial segment performance, energy efficiency or power-flux-density compliance if they were not evaluated.
- **PE-05:** Explain each existing plot through the varied parameter, direction of observed trend, baseline difference where verifiable, and a technical interpretation grounded in the original model. Do not invent hidden causal mechanisms to rationalize curves.
- **PE-06:** Percentages and absolute gains require reproducibility from plots/data; never invent them.
- **PE-07:** Document available bandwidth, optimizer settings, simulation configuration, observation timing, and average-latency generation method; flag missing provenance rather than silently filling gaps.
- **PE-08:** The TAES reviewers requested further comparisons and experiments. Acknowledge requests that cannot be conclusively resolved under the no-new-results constraint.
- **PE-09:** Figure captions specify the plotted metrics and varied parameters, with detailed interpretations in the body. Reference each figure/table/algorithm and maintain figure numbering.

## G. LaTeX, structure and publication format
- **FMT-01:** Use `\documentclass[journal]{IEEEtran}` and follow `FINAL VERSION.tex` for title/author/affiliation/thanks presentation, subject to verifying actual authors, IEEE membership status and funding provenance for this manuscript.
- **FMT-02:** Use the accepted reference papers for technical writing conventions, not literal replication of their content or unsupported claims.
- **FMT-03:** Maintain seven substantive sections: Introduction; Related Work; System Model; Optimization Problem Formulation; Proposed Adaptive Block SCA; Performance Evaluation; Conclusion, unless an author-approved restructure improves clarity.
- **FMT-04:** One-paragraph self-contained abstract: scenario, technical challenge, true objective/constraints, actual algorithm, tested outcomes. Avoid unsupported numerical gains and false algorithm guarantees.
- **FMT-05:** Tables, figures and algorithms have specific captions, consistent notation, and numbered in-text references. Avoid manual negative spacing that obscures page-limit or layout issues.
- **FMT-06:** Target 10–11 IEEE two-column pages **including references**, with a maximum of 11 under the current author direction; check actual compiled output.
- **FMT-07:** Maintain normal IEEE typography, non-bold body text, working figure paths and compatible algorithm packages. Compile and review equations, figure resolution, page count and bibliography.
- **FMT-08:** Log manuscript decisions and substantive changes; do not overwrite author edits or recreate intentionally deleted files.

## H. Required revision and quality gates
1. Verify title, author listing, affiliations, correspondence, class and funding/acknowledgments.
2. Verify claims in abstract, contributions and Related Work against actual model, literature and original evaluations.
3. Audit all citations and bibliographic metadata, including issue month/year and conference city/country.
4. Audit notation, equations, approximation conditions, algorithm pseudocode and reviewer-identified inconsistencies.
5. Check all original plots, captions, metric definitions and benchmark descriptions against available evidence.
6. Compile and inspect the Overleaf PDF for package errors, missing figures, warnings, bibliography correctness and page limit.
7. Preserve no-new-results policy and mark unresolved reviewer requests explicitly.
8. Record revisions in `REVISION_CHANGELOG.md`.

## Reuse for later manuscripts
Create a **new, separately named Markdown rules file** in the `Paper-Writing-Rules` repository for each manuscript or target journal. Start from this rulebook's language, citation accuracy and quality-control standards; replace only paper-specific title, venue, notation, research restrictions and section architecture. Keep earlier versions available for provenance rather than retroactively changing their scientific conditions.
