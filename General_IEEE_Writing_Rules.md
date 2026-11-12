# General IEEE Paper Writing Rules
**Status:** Shared baseline, version 1.0 (2026-11-12)  
**Applies to:** IEEE journal/conference manuscript drafting unless overridden by verified venue requirements or an approved paper-specific rulebook.  
**Canonical repository:** `enpaulson2/Paper-Writing-Rules`

## 1. Evidence, correctness, and editorial priority
1. The latest explicit author decisions and the actual scientific record take precedence over any sample paper's wording or formatting.
2. Do not introduce invented numerical results, baselines, equations, assumptions, citations or references. Do not infer experimental conditions from plots when the provenance is unknown.
3. State what the model actually optimizes, including variable scope, constraints, coordination assumptions and evaluated metrics.
4. Distinguish evidence from simulations, mathematical proof, modeling assumptions and future possibilities.
5. Maintain a change log in the relevant paper repository for substantive editorial and technical decisions.

## 2. Academic language
1. Avoid *must, can, will, shall* in ordinary research prose. Prefer *should, would, may, could* only for genuinely conditional or uncertain statements. Use direct declarative present tense for established mathematical statements and implemented algorithm operations.
2. Avoid rhetorical fillers and generic transitions (e.g., “Nowadays,” “It is worth noting,” “Overall,” “Together”). Organize paragraphs around a single technical point.
3. Do not claim “optimal,” “guaranteed,” “significant,” “state-of-the-art,” “robust” or “scalable” without proof, appropriate statistics or explicit evaluation.
4. Expand and define technical acronyms once; use consistent terminology and notation throughout.
5. Write the paper's actual technical contribution, not a marketing claim or a generic methodological summary.

## 3. Introduction, Related Work, and contributions
1. Lead from a well-supported system context to a specific research challenge, then establish a narrow, documented research gap and distinguishable contributions.
2. Organize Related Work by problem/method category rather than a chronological catalogue.
3. Characterize key prior works by objectives, decision variables, architectures, assumptions, methods and relevant guarantees. Differences of scope are not necessarily deficiencies.
4. Use a comparison table when it helps demonstrate methodological distinctions; verify every cell against original publications.
5. Cite sources next to claims they support. Group related citations selectively, with individual treatment of important technical contrasts.
6. Each contribution should map to a substantive, demonstrable part of the model, method, proof or retained evaluation.

## 4. Complete IEEE bibliographic metadata
1. Use the official IEEE abbreviated journal and conference-proceedings names consistently and format references with the appropriate IEEE bibliography style, typically `\bibliographystyle{IEEEtran}`.
2. **Journal articles:** list verified authors, published title, standard journal abbreviation, volume, issue, page range or article number, **publication month**, and **publication year**, where assigned.
3. **Conference papers:** list verified authors, title, standard abbreviated proceedings venue, actual conference **city and country**, **month and year**, and page range or article number where available; include exact event dates when verifiable and useful.
4. Final issue metadata supersedes preliminary early-access metadata. Label genuine early-access references explicitly and do not manufacture unassigned fields.
5. Protect acronyms (such as `{LEO}`, `{IoT}` and `{SCA}`) in BibTeX article titles. Avoid duplicated entries and inconsistent citation keys.
6. **DOI inclusion is optional**, not required by these rules. Existing accurate DOI metadata may remain. Do not invent or duplicate DOI strings.
7. Audit reference author/title/date/venue metadata against a credible publisher or conference record. Prior bibliographies serve as starting points, not unquestionable sources.

### Typical IEEE journal reference format
A. B. Author and C. D. Author, “Article title,” *IEEE Trans. Wireless Commun.*, vol. xx, no. x, pp. xxx–xxx, Mon. YYYY.

### Typical IEEE conference reference format
A. B. Author and C. D. Author, “Article title,” in *Proc. IEEE Global Commun. Conf. (GLOBECOM)*, City, Country, Mon. YYYY, pp. xxx–xxx.

These are formatting placeholders, not actual publications.

## 5. Mathematics and algorithm writing
1. Introduce all symbols, indices, units and relevant assumptions before formal use.
2. Explain the meaning of the objective, constraints, approximation and update mechanism without paraphrasing every equation.
3. Distinguish exogenous measurements and fixed algorithm inputs from decision-dependent quantities.
4. Assert convergence, complexity and optimality properties only with justified derivations, proof or explicitly supported conditions.
5. Preserve internal coherence among the system model, optimization problem, algorithm and evaluation.

## 6. Evaluation and figures
1. Specify the actual compared methods, varied parameters, metrics and assumptions. Describe empirical trends precisely.
2. For each result figure, discuss the independent variable, observed pattern, relevant benchmark and defensible technical explanation.
3. Never insert unverified numerical improvements or unexplained causal claims.
4. Figures, tables and algorithms require meaningful captions, correct references and readable formatting.
5. Verify simulation parameter provenance and metric definitions; identify unresolved details instead of fabricating them.

## 7. Journal preparation
1. Follow the target publication's current official LaTeX class, manuscript structure and submission requirements.
2. Use accepted manuscripts as style references only; do not transfer their technical data or unsupported claims.
3. Review compiled output for equation width, figure path accuracy, labels, bibliography, page count and typography.

## 8. Paper-specific adaptations
Create a distinct file for each paper under a journal folder such as `IoT_Journal/`, `TWC/`, `TCOM/` or `TAES/`. State the exact working title, method, network scenario, reviewer constraints, allowed changes, evidentiary boundaries, page target and journal-specific reference policy. For a new manuscript, review and approve the adapted rules before substantial rewriting.

**Existing paper-specific rulebook:** [Adaptive Block SCA Writing Rules](IoT_Journal/Adaptive_Block_SCA_Writing_Rules.md).
