---
abstract: "Scientific inquiry often hinges on selecting models that adequately
capture the phenomena under investigation, by employing different
strategies and toolkits based on modeling purposes and contexts of
analysis. Within this landscape, the theory of model selection has
been broadly constructed around two primary focuses. On the one hand,
philosophers of science emphasize the conceptual integrity of models
\citep[e.g.,][]{grune-yanoffModelingModelSelection2018,tielemanModelTransferUniversal2022},
that is how well a model\textquoteright s structure aligns with theoretical
frameworks or explanatory aims. On the other hand, econometricians
focus on output adequacy measured through criteria such as predictive
performance, hypothesis testing, and information criteria \citep[e.g.,][]{hotellingStatisticalMethodPhilosophy1958,boxRobustnessStrategyScientific1979,myungImportanceComplexityModel2000,spanosPhilosophyEconometrics2021}.
Striking a balance between these perspectives remains a central challenge,
with both practical and theoretical implications. In fact, while most
models are usually scrutinized separately in their theoretical consistency
and empirical performance, the prerequisite for enacting the latter
\emph{vis a vis} the former, that is the unambigous distinction among
different families of models on the same phenomenon, remains unfulfilled.
This paper aims at elucidating such necessary prerequisites and proposes
a unified framework for model selection that leverages Utility Theory
as the central criterion, integrating both conceptual and statistical
evaluations into a single decision-making process. In doing so, the
framework relies and enhances the analogical understanding within
the field of model theory \citep{barthaParallelReasoningConstruction2010,knuuttilaModellingIndirectRepresentation2017}.

In this framework, each candidate model $m$ from a set $M$ is evaluated
by a total utility function $U\left(m\right)$ composed of two distinct
components: a conceptual utility $U\_{C}\left(m\right)$ and a statistical
utility $U\_{S}(m\mid\mathcal{D})$, where $\mathcal{D}$ represents
the observed data. The overall model selection process then amounts
to choosing the model that maximizes the sum of these utilities:
\[
m^{*}=\arg\max\_{m\in M}\left\{ U\_{C}(m)+U\_{S}(m\mid\mathcal{D})\right\} .
\]

At the conceptual level, model selection is set as guided by analogical
reasoning that compares the origin structure of a model with a target
phenomenon. This evaluation is performed relatively to a benchmark
$B$, which may be a model template or an ideal theoretical reference.
Distinct utility functions may capture this analogical reasoning.
First, the \emph{Global Similarity Utility} $U\_{G}(m)$ assesses the
overall resemblance between the structure $S(m)$ and that of the
benchmark $B$, considering all the features of the model. In a hypothetical
quantitative formulation, one might assign ranks and weights to each
feature of $\ensuremath{S\left(m\right)}$, yielding an expression
such as
\[
U\_{G}(m)=\sum\_{i\in F}w\_{i}\,\rho\_{i}(m,B),
\]
where $F$ is the full set of features, $\rho\_{i}$ represents a qualitative
rank, and $w\_{i}$ is the weight assigned to feature $i$. However,
in practice, this evaluation remains largely qualitative, allowing
for considerable degrees of freedom.

The second function, the \emph{Relevance-Based Utility} $U\_{R}(m)$,
is confined to a subset $C\subset F$ of core features deemed essential
for capturing the phenomenon. Here, only the \textquotedblleft core\textquotedblright{}
elements are evaluated:
\[
U\_{R}(m)=\sum\_{i\in C}v\_{i}\,\sigma\_{i}(m,B),
\]
with $\sigma\_{i}$ representing a qualitative rank for the core feature
$i$ and $v\_{i}$ its corresponding weight. It is important to note
that $U\_{R}(m)$ and $U\_{G}(m)$ are not aggregated into a single
metric because they serve distinct evaluative purposes: global similarity
considers all aspects of a model\textquoteright s structure, while
relevance-based similarity is restricted to those components critical
to the theoretical framework. Moreover, models are intrinsically ranked
according to the provisioned utility function, which may include further
properties such as simplicity and parsimony \citep{falkParsimonyModelSelection2021,bargaglistoffiSimpleModelsComplex2022}.

These conceptual evaluations also allow the identification of \emph{families
of models}. Models that differ only in minimal, distinct ways, that
is where the differences are both distinct and countable, are grouped
into the same model family. This grouping clarifies the conceptual
space and permits systematic comparison among closely related models
by emphasizing their direct differences.

At the statistical level, model selection is based on the model outputs
derived from observed data $\mathcal{D}$. The statistical utility
$U\_{S}(m\mid\mathcal{D})$ reflects empirical performance, often approximated
through measures such as likelihood, predictive accuracy, and information
criteria (e.g., AIC or BIC). Techniques such as hypothesis testing
are also employed; however, it is critical to recognize that hypothesis
testing serves as a condition for pairwise selection rather than providing
a complete ranking across multiple models. Provided that, $U\_{S}(m\mid\mathcal{D})$
is expressed as the utility based on the data, $U\_{S}(m\mid\mathcal{D})$.

By combining these two facets\textemdash the qualitative, analogical
conceptual evaluation and the quantitative, data-driven statistical
evaluation\textemdash we arrive at an integrated utility function
that guides the selection of an optimal model. This approach unifies
the conceptual and empirical dimensions of model selection under a
clearly defined two-stage evaluative framework, ensuring that the
trade-offs between theoretical coherence and empirical adequacy are
made explicit.

The paper is structured as follows. Sect. 1 reviews the existing philosophical
and econometric frameworks of model selection and it makes a case
for the use of the concept of utility as a comprehensive theoretical
framework. Sect. 2 provides a detailed description of the framework
as well as the necessary conditions for its deployment. Sect. 3 delves
into critical issues, such as \emph{stability} and \emph{univocity}
in defining models and model families, and the potential extension
of the model to accommodate the comparisons across fundamentally different
families. Moreover, it deals with the limitations in providing a quantitative
expression for conceptual evaluations, and the consequences of the
unchecked use of qualitative evaluations with multiple degrees of
freedom."
all_day: true
authors:
- Massimo Rusconi
- admin
date: "2025-09-17"
date_end: "2025-09-19"
event: "17th Biennal Conference of the International Network for Economic Method (INEM 2025)"
event_url: "https://www.phil.uni-bayreuth.de/en/events/Workshops/INEM17th/index.html"
featured: false
image:
  caption: ''
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/rfl_seri
location: Bayreuth, Germany
math: true
projects:
- ""
publishDate: "2025-01-01T00:00:00Z"
slides: ""
summary: "International conference"
tags:
- Econometrics
- Philosophy
title: "On the Utility of Models: Bridging the Theoretical and Analytical Sides of Model Selection"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
