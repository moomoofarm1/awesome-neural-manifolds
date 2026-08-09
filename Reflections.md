# Levels of manifolds in psychology (Psychological geometry)
According to the paper ([Roads, & Love, 2024a](https://www.annualreviews.org/content/journals/10.1146/annurev-psych-040323-115131), and [Roads, & Love, 2024b]()), the manifold/psychological space could exist on multiple levels, one from the observed data (stimulus, neural & behavioral data), and another from the hierarchical higher-older from the one got from these data.
Therefore, by referring to the paper on the neural-manifold hypothesis ([Lei et al., 2020](https://www.sciencedirect.com/science/article/pii/S2095809919302279)), one can have three levels of manifolds in psychology, or the geometry of psychology.

Psychological geometry can be conceptualized at multiple levels. These levels differ primarily in **what constitutes a point**, **what relations define the geometry**, and **what psychological process the geometry represents**.

A useful distinction is between three levels: **data manifolds**, **statistical manifolds**, and **decision manifolds**.

## 1. Data Manifold

At the most concrete level, psychological and neuroscientific observations may occupy a lower-dimensional manifold embedded within a high-dimensional measurement space.

Examples include:

- **Neural manifolds**, where each point represents a neural population state;
- **Behavioral manifolds**, where each point represents an observed behavioral state or response;
- **Stimulus manifolds**, where each point represents a stimulus or stimulus configuration.

Formally,

\[
x \in \mathcal{M}_{\text{data}} \subseteq \mathbb{R}^{D},
\]

where \(x\) is an observation and \(\mathcal{M}_{\text{data}}\) represents the intrinsic structure underlying high-dimensional observed data.

Thus, at this level:

> **A point is an observation or observed state.**

The geometry describes relationships among observations—for example, similarity, neighborhood structure, trajectories, or transitions between neural or behavioral states.

---

## 2. Statistical Manifold

A statistical manifold operates at a different level of description. Instead of representing individual observations, each point represents an entire **probability distribution or statistical model**.

For example,

\[
\mathcal{M}_{\text{stat}}
=
\{p(x\mid\theta):\theta\in\Theta\}.
\]

Two points on this manifold might therefore correspond to

\[
p(x\mid\theta_1)
\qquad\text{and}\qquad
p(x\mid\theta_2),
\]

rather than to two individual observations.

The geometry of this space can be investigated using **information geometry**, for example through the Fisher–Rao metric.

Thus:

> **A point is a probability distribution or probabilistic state.**

Importantly, the statistical manifold should not be understood as literally contained inside the data manifold. Rather, the two are linked through a **generative relationship**:

\[
\mathcal{M}_{\text{stat}}
\longrightarrow
p(x)
\longrightarrow
x\in\mathcal{M}_{\text{data}}.
\]

In psychological terms, a latent psychological state may define a probability distribution over possible behavioral, neural, or stimulus-related observations.

---

## 3. Decision Manifold

The third level concerns the **geometry of psychological decision making**.

Human decision making is often naturally represented as a branching process:

\[
\text{state}
\rightarrow
\text{choice}
\rightarrow
\text{new state}
\rightarrow
\text{choice}
\rightarrow
\cdots
\]

A decision tree therefore provides a useful discrete approximation to the structure of such a process. Different branches represent alternative decisions, while successive levels represent increasingly specific states, hypotheses, interpretations, or actions.

Because tree-like structures expand approximately exponentially with depth, **hyperbolic geometry** is particularly suitable for representing them.

Formally, the decision structure can be represented as a graph \(G\) embedded within a hyperbolic manifold:

\[
G_{\text{decision}}
\hookrightarrow
\mathbb{H}^{n}.
\]

Strictly speaking, the branching decision tree itself need not be a smooth mathematical manifold. Rather, the **decision manifold** refers to the continuous geometric representational space in which this tree-like decision structure is embedded.

Thus:

> **A point represents a decision state, hypothesis, interpretation, or action state, while trajectories through the space represent decision-making processes.**

For example:

\[
\text{uncertain situation}
\rightarrow
\begin{cases}
\text{interpretation A}
\rightarrow
\text{action A}_1,\text{ action A}_2\\
\text{interpretation B}
\rightarrow
\text{action B}_1,\text{ action B}_2
\end{cases}
\]

can be interpreted geometrically as movement through a branching region of a negatively curved space.

The term **decision manifold** is therefore intentional: the aim is not simply to represent a hierarchy of psychological constructs, but to represent the **branching structure and trajectories of human decision making geometrically**.

---

# A Three-Level Framework

The resulting framework can be summarized as:

\[
\boxed{
\begin{array}{c}
\textbf{Level 3: Decision manifold}\\
\text{point = decision / hypothesis / action state}\\
\text{structure = branching trajectories}\\
\text{candidate geometry = hyperbolic geometry}
\\[10pt]
\uparrow\;\text{inference / abstraction / decision}
\\[10pt]
\textbf{Level 2: Statistical manifold}\\
\text{point = probability distribution}\\
\text{structure = relations among probabilistic states}\\
\text{geometry = information geometry}
\\[10pt]
\downarrow\;\text{probabilistic generation}
\\[10pt]
\textbf{Level 1: Data manifold}\\
\text{point = observation}\\
\text{structure = empirical relationships among observations}\\
\text{examples = neural, behavioral, and stimulus manifolds}
\end{array}
}
\]

The three levels therefore answer three different questions:

| Level | What is a point? | What does the geometry describe? |
|---|---|---|
| **Data manifold** | Observation | Structure among observed neural, behavioral, or stimulus states |
| **Statistical manifold** | Probability distribution | Structure among possible probabilistic or latent states |
| **Decision manifold** | Decision state | Branching structure and trajectories of psychological decision making |

The central proposal is therefore not that these three objects are mathematically identical kinds of manifolds, but that **geometric representations can operate at three progressively more abstract levels of psychological organization**:

\[
\boxed{
\text{observations}
\rightarrow
\text{probabilistic states}
\rightarrow
\text{decision trajectories}
}
\]

This formulation also makes the role of the third level clearer: **hyperbolic geometry is proposed not merely because psychological concepts can be hierarchical, but because human decision making itself can generate branching, tree-like trajectories whose geometry may be represented efficiently in negatively curved space.**
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
