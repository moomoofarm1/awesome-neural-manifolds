# Career goal on psychomaths

Or mathematical psychology: using geometry and dynamics as a common language across psychological measurement, cognition, behavior, and neural population activity.

## From psychophysics to psychological manifolds (1860–Now[2026])

Psychological manifolds can be understood as a modern continuation of psychophysics. The line begins slightly before Wundt: Weber and Fechner asked whether subjective sensation could be measured as a lawful function of physical stimulation. Fechner's *Elemente der Psychophysik* (1860) formalized this program. Wundt then made controlled measurement central to experimental psychology and founded the Leipzig laboratory in 1879. The first problem was therefore geometric in a simple sense: how does a physical axis map onto a subjective axis?

The next step was to infer hidden psychological coordinates rather than assume them. Thurstone's comparative judgment, Stevens's direct scaling, and the Mel scale treated perception as a latent scale. Torgerson, Shepard, and Kruskal then developed multidimensional scaling (MDS), which reversed the problem: start from similarity or dissimilarity judgments and reconstruct the psychological space that could have generated them. Work on color, pitch, timbre, affect, and faces showed that psychological structure can be multidimensional, circular, anisotropic, or otherwise different from the physical stimulus coordinates.

This also exposed an important limit. Tversky showed that human similarity can be asymmetric and context dependent, so ordinary Euclidean distance is not a universal psychological law. Nosofsky further showed that attention can stretch or compress dimensions according to the task. A psychological geometry therefore cannot simply be assumed; its metric and invariances must be tested.

Shepard's 1987 universal law of generalization supplied a crucial validation principle: distance in an appropriate psychological space should predict an independent behavior—generalization. Later work on face space and representational similarity analysis made relational geometry a shared language for behavior, cognition, brain activity, and computational models. The core object gradually shifted from a single psychophysical scale to the full pattern of relations among representations.

Since 2020, this program has moved to naturalistic, high-dimensional stimuli. Large behavioral datasets can recover interpretable object spaces; psychophysical scaling can reveal nonlinear memory geometry; and modern studies explicitly test dimensionality, curvature, hierarchy, and cross-system alignment. Work from Hebart and colleagues, Waraich and Victor, Marjieh and colleagues, Roads and Love, Mahner and colleagues, Muttenthaler and colleagues, and Seiler and colleagues shows a continuous path from classical psychophysics to present-day psychological representation geometry.

The historical sequence is therefore:

**physical stimulus → subjective scale → psychological distance → multidimensional psychological space → representational geometry → candidate psychological manifold**

The word *manifold* should be used more strictly than *embedding* or *psychological space*. An MDS, PCA, or UMAP plot alone does not establish a manifold. A strong psychological-manifold claim should test at least some of the following: intrinsic dimension, local metric, curvature, topology or connectivity, stability across measurements and tasks, and prediction of behavior not used to construct the space.

This suggests a practical working definition:

> A **candidate psychological manifold** is a low-dimensional, possibly curved organization of psychological states or representations recovered from behavior and validated by independent behavioral, cognitive, or neural evidence.

This definition keeps the historical link to psychophysics while avoiding the stronger claim that every psychological embedding is already a neural manifold.

## Cross-level working hypothesis

Psychological functions may be modeled as geometric structures that emerge from neural population dynamics and appear, through different measurement maps, in cognition, language, behavior, symptoms, and psychometric data. The central scientific problem is not merely to find low-dimensional plots, but to test whether geometries recovered at different levels are stable, predictive, and partially alignable.

A useful research program therefore has three stages: recover a geometry from observations; validate its psychological distances and dynamics with independent outcomes; then test whether corresponding structure can be aligned across behavioral and neural levels. This turns the neural-manifold idea into a falsifiable program of geometric psychology rather than a purely metaphorical analogy.

## Model chain and spatial scale

> The spatial ranges are approximate modelling scales, not fixed properties of the equations.

| Level | Model | Main description | Approximate brain scale |
|---|---|---|---|
| 1 | **Hodgkin–Huxley network** | Models ion channels, membrane potentials, spikes, and synaptic interactions between individual neurons | **Micrometres to below 1 mm** |
| 2 | **Spatial McKean–Vlasov–Fokker–Planck equation** | Replaces many interacting HH neurons with a probability-density field over neuronal states | **Approximately 0.1–1 mm** |
| 3 | **Random continuous-attractor neural field** | Models collective neural activity and low-dimensional attractor coordinates across neural tissue | **Several millimetres to centimetres** |
| 4 | **Multidimensional drift-diffusion model** | Models attractor coordinates as noisy evidence variables moving toward behavioral decision boundaries | **Behavioral level; no fixed anatomical size** |

$$
\text{HH network} \rightarrow \text{spatial McKean–Vlasov–Fokker–Planck equation} \rightarrow \text{random continuous-attractor neural field} \rightarrow \text{multidimensional DDM}
$$

The chain moves from microscopic neuronal dynamics to local population distributions, large-scale neural attractors, and finally behavioral decision dynamics.

## Mathematical meaning

This chain resembles [Hilbert's sixth problem](https://royalsocietypublishing.org/doi/10.1098/rsta.2017.0238): deriving macroscopic continuum and probabilistic laws from microscopic dynamics. In the proposed neuroscience chain, the analogous goal is to connect neuron-level dynamics to population fields and then to low-dimensional behavioral variables without assuming that the levels are identical.

It also gives a concrete interpretation of P. W. Anderson's [“More Is Different”](https://doi.org/10.1126/science.177.4047.393): collective variables, attractors, symmetries, and behavioral laws can emerge when many microscopic units interact.

## Core references for the model chain

- [Hodgkin and Huxley: membrane dynamics](https://pmc.ncbi.nlm.nih.gov/articles/PMC1392413/)
- [Mean-field limit of Hodgkin–Huxley networks](https://arxiv.org/abs/1110.4294)
- [Continuous-attractor neural networks](https://pmc.ncbi.nlm.nih.gov/articles/PMC4752021/)
- [Stochastic motion of attractor bumps](https://arxiv.org/abs/1205.3072)
- [Drift-diffusion dynamics from neuronal competition](https://pmc.ncbi.nlm.nih.gov/articles/PMC6609930/)

The historical papers behind the psychophysics-to-manifold argument are collected in the README subsection **“Psychological manifolds originated from psychophysics.”**
