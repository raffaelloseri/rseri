---
abstract: "Persistent technological trajectories are commonly analyzed, in evolutionary and Schumpeterian economics, as the outcome of cumulative learning, increasing returns, and decentralized selection within specific techno-economic regimes. In this perspective, the endurance of incumbent technologies is often interpreted as an emergent property of market competition and capability accumulation: technologies persist because they coordinate expectations, exploit complementarities, and benefit from path-dependent diffusion.

Yet, in many historical and sectoral contexts, technological persistence appears to depend not only on techno-economic performance, but also on the strategic capacity of organized actors to stabilize specific patterns of innovation. These stabilization forces do not necessarily override market mechanisms; rather, they can operate by shaping the selection environment in which technologies compete and diffuse—through standards, regulatory thresholds, access to complementary assets, and the structure of financing and research infrastructures. This is not an external “political add-on” to the Schumpeterian perspective. Notoriously, in Capitalism, Socialism and Democracy, democratic practice is presented as historically intertwined with the capitalist process: “modern democracy rose along with capitalism,” and the democratic method “presided over” the institutional reconstruction through which the bourgeois order reshaped the preceding political structure (see Schumpeter and Swedberg, 2013, p. 297). Moreover, Schumpeter’s discussion of bourgeois democracy explicitly links capitalist development to the practical problem of delimiting “the sphere of political decision,” i.e., the manageable scope of what is made subject to political contention and leadership competition (Schumpeter and Swedberg, 2013, p. 297). Even where he cautions against overestimating the political power of big business, he draws attention to the observable behavior of capitalist interests when facing direct political attack (Schumpeter and Swedberg, 2013, p. 161).

The modelling difficulty is that most formal accounts of innovation, also within the evolutionary family, either treat these influence channels as exogenous constraints or absorb their effects into purely techno-economic mechanisms (learning, returns to adoption, concentration). In both cases, the same limitation emerges: the model can generate persistence, but it struggles to represent endogenously the hetero-determination of innovation patterns, i.e., the possibility that incumbency is actively produced and maintained by coalitions operating inside a given technological environment. The present paper addresses this limitation by focusing on how such mechanisms can be transliterated within agent-based models (ABM) of innovation, without collapsing socio-political influence into an external policy layer.

From a modelling standpoint, the issue cuts across standard typologies of innovation regimes. The Mark I / Mark II distinction (e.g., Malerba and Orsenigo, 1997) captures important differences in innovative agency, appropriability, and concentration, but it does not exhaust the space of admissible dynamics once collective influence is allowed to interact endogenously with technological change. In both regimes, actors may share an interest in preserving a given technological configuration, not simply because it performs well, but because it secures rents, complementarities, organizational routines, and even lobbying activities. Incumbent stabilization, in this sense, is not equivalent to monopoly power or market concentration alone; it is a meso-level coordination phenomenon that reshapes the effective selection environment by altering viability thresholds, redirecting innovative effort, and filtering diffusion pathways.

A growing body of work in agent-based macroeconomics and evolutionary modelling has delivered increasingly articulated representations of innovation, structural change, and regime dynamics. Within this literature, ABMs have been used to study innovation-led growth and divergence patterns, distributional dynamics co-evolving with directed technical change, as well as multi-system transitions where macroeconomic trajectories interact with environmental constraints (e.g., Lamperti et al., 2018; Dosi et al., 2019; Mellacher and Scheuer, 2021; Dosi et al., 2022; Lackner et al., 2025). The current works is therefore divided into two parts. In the first one, a review on the major current families of models in the fields is conducted. In doing so, the paper clafiries key modelling choices that have become central in ABM representations of innovation and structural change, and to motivate an extension in which endogenous innovation dynamics are studied jointly with mechanisms shaping the selection environment. The aim is to reconstruct a set of modelling commitments about heterogeneity, interaction, and the generation of structural change, that define a plausible space for endogenizing influence alongside innovation.

On this basis, the second part of the work introduces the dystopian version of the Freeburg model (D-Freeburg) as a first attempt to operationalize the coupling between endogenous innovation and endogenous influence. D-Freeburg is a modular ABM designed around three requirements. First, innovation patterns must be generated endogenously by distinct loci—research centers and firms—so that novelty is not reduced to a single representative process and so that the division of innovative labor becomes part of the model’s explanatory structure. Second, the government sector can be activated to implement alternative policy configurations aimed at fostering innovation dynamics. Third, the selection environment—e.g., standards, access to complementary assets, and adoption conditions—must be endogenously shapeable by coalitions: influence is treated as an emergent, parametrically activated mechanism arising from interaction, with feedback effects on diffusion, adoption, and the direction of search. In this context, the “dystopian” qualifier does not express a normative judgement; it signals the exploration of a parameter region in which influence is sufficiently effective to become analytically visible as a stabilizing mechanism, thus allowing it to be analytically separated from more familiar sources of persistence (learning, increasing returns, market structure).

The model is used to run comparative simulation experiments in which the influence mechanism is activated under alternative configurations (lobbying mode, target definition, coordination size, and effectiveness) and contrasted with baseline runs where the selection environment is not affected by coalition-driven pressure. The analysis tracks how these configurations reshape incumbency persistence and turnover, diffusion and adoption trajectories, and the allocation of innovative effort across incumbent-compatible and competing directions.

Taken together, the contribution of the paper is twofold. Substantively, it clarifies the main challenges modelling the political sphere endogenously to economics ABM, while undermining its relevance whenever firms are understood as political actors. Methodologically, it proposes a first modelling strategy, implemented in D-Freeburg, for treating innovation and influence as jointly endogenous within an ABM architecture, without collapsing socio-political mediation into an external “context.”


**References**


Giovanni Dosi, Andrea Roventini, and Emanuele Russo. Endogenous growth and global divergence in a multi-country agent-based model. *Journal of Economic Dynamics and Control*, 101:101–129, April 2019. ISSN 01651889. doi: 10.1016/j.jedc.2019.02.005.

Giovanni Dosi, Marcelo C. Pereira, Andrea Roventini, and Maria Enrica Virgillito. Technological paradigms, labour creation and destruction in a multi-sector agent-based model. *Research Policy*, 51(10):104565, December 2022. doi: 10.1016/j.respol.2022.104565.

Teresa Lackner, Luca E. Fierro, and Patrick Mellacher. Opinion dynamics meet agent-based climate economics: An integrated analysis of carbon taxation. *Journal of Economic Behavior & Organization*, 229:106816, January 2025. ISSN 01672681. doi: 10.1016/j.jebo.2024.106816.

Francesco Lamperti, Giovanni Dosi, Mauro Napoletano, Andrea Roventini, and Alessandro Sapio. Faraway, So Close: Coupled Climate and Economic Dynamics in an Agent-based Integrated Assessment Model. *Ecological Economics*, 150:315–339, August 2018. ISSN 09218009. doi: 10.1016/j.ecolecon.2018.03.023.

F. Malerba and L. Orsenigo. Technological Regimes and Sectoral Patterns of Innovative Activities. *Industrial and Corporate Change*, 6(1):83–118, January 1997. ISSN 0960-6491, 1464-3650. doi: 10.1093/icc/6.1.83.

Patrick Mellacher and Timon Scheuer. Wage Inequality, Labor Market Polarization and Skill-Biased Technological Change: An Evolutionary (Agent-Based) Approach. *Computational Economics*, 58(2):233–278, August 2021. ISSN 0927-7099, 1572-9974. doi: 10.1007/s10614-020-10026-0.

Joseph A. Schumpeter and Richard Swedberg. *Capitalism, Socialism and Democracy*. Routledge, London New York, 2013. ISBN 978-0-203-20205-0. doi: 10.4324/9780203202050."
all_day: true
authors:
- Massimo Rusconi
- admin
date: "2026-07-01"
date_end: "2026-07-04"
event: "ISS2026 (International Schumpeter Society) 'Capitalism and Democracy: Paradigm Shifts and Creative Transformations'"
event_url: "https://iss2026.sciencesconf.org/?lang=en"
featured: false
image:
  caption: ''
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/rfl_seri
location: Strasbourg, France
math: true
projects:
- ""
publishDate: "2026-02-12T00:00:00Z"
slides: ""
summary: "International conference"
tags:
- Econometrics
- Philosophy
title: "Innovation Dynamics under Endogenous Influence: An Agent-Based Modeling Perspective"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
