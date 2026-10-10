---
Title: "Reflections on Psychometrics and Psychological Geometry"
Author: "Zhuojun Gu"
Date: "2026-10-10"
---

# Reflections on psychometrics: From true scores to psychological geometry

*Plain-English discussion notes, 10 October 2026. These are research reflections and hypotheses, not a systematic review or evidence that a psychological manifold has already been established. For the broader neural-manifold reading list, see [README.md](README.md); for earlier geometric reflections, see [Reflections.md](Reflections.md).*

## 1. Three traditions answer different questions

One central lesson from our discussions is that **classical test theory (CTT), Thurstonian scaling, and Fechnerian scaling should not be treated as three competing ways to estimate the same thing**.

| Tradition | Plain-English question | Typical result | What it does not establish |
| --- | --- | --- | --- |
| **Classical test theory (true-score theory)** | How much can we trust an observed test score? | A total score and estimates of reliability and measurement error | The unique shape or distance structure of a psychological space |
| **Thurstonian scaling** | Where do stimuli, statements, or preferences fall on a psychological continuum? | Latent scale locations inferred from comparative judgments | A general metric for multidimensional psychological states |
| **Fechnerian scaling** | How can local, experienced differences between stimuli be accumulated into distances? | A relational distance structure among stimuli or states | The number, identity, or validity of psychological dimensions by itself |
| **Multidimensional scaling (MDS)** | Can relationships between objects be represented with a few coordinates? | A low-dimensional map of those relationships | That the map is an intrinsic, independently validated psychological manifold |

A simple example makes the differences clear. A depression questionnaire gives a person a score of 18. CTT asks whether this score is dependable and how much measurement error to expect. A Thurstonian approach might ask how statements reflecting different levels of severity should be placed along a latent severity scale. A Fechnerian approach might ask how psychologically far apart the underlying states are, using empirically meaningful differences. MDS could then provide coordinates for visualizing such distances.

These questions can complement each other. A scale can be highly reliable but geometrically misleading. A convincing spatial map can be reproducible but fail to measure depression. The scientific target determines which questions must be answered.

## 2. Why did true-score theory become so common?

**The short answer: ordinary psychological research needed dependable, inexpensive scores more urgently than it needed a reconstruction of psychological geometry.** But "CTT won because it was simple" is incomplete.

### 2.1 It was efficient at the level of the whole study

Thurstone's early methods were ambitious: build an attitude continuum using carefully assessed statements and judges. Likert (1932) offered an easier way to collect graded responses and combine them. In his original comparison, Likert reported evidence that his approach could obtain similar reliability with fewer items, or higher reliability with a comparable number of items.

This was not just less mathematics. It reduced item-development work, administration costs, and the burden of collecting additional judgments. It helped researchers study larger samples and many constructs. Yet Likert's findings were about the measurements he compared, not proof that a sum score always captures the true structure of an attitude.

### 2.2 It addressed the practical problem of measurement error

CTT separated an observed score conceptually into a true component and an error component. Researchers could then ask whether people differ reliably, whether scales agree with other indicators, and whether scores help predict meaningful outcomes. Cronbach (1951) made coefficient alpha part of the standard language of scale evaluation.

This is an attractive workflow in psychology: write items, collect responses, inspect score quality, and test associations with behavior or clinical outcomes. One does not first need to identify a metric space, solve a distance-reconstruction problem, or estimate a curved manifold.

**Important correction:** in CTT, "true score" means the expected result over a defined universe of repeated measurements under the theory. It is not automatically a true, physically existing amount of depression or any other psychological trait.

### 2.3 It fitted the growth of validity research

Cronbach and Meehl (1955) argued that psychological constructs require a network of theoretical and empirical evidence. Campbell and Fiske (1959) made convergent and discriminant validation more explicit. These developments allowed an applied research program to work with fallible scores while gathering external evidence for their interpretation.

The result was an effective institutional workflow: questionnaires, reliability coefficients, factor analyses, correlations, regression models, clinical norms, and replication across samples. CTT was part of that ecosystem, not its entire theoretical foundation.

### 2.4 It was usable with less demanding data and assumptions

Compared with many item response theory (IRT) models, basic CTT summaries generally impose fewer explicit item-response assumptions and are usable with modest samples. Hambleton and Jones (1993) explain both the practical attractions and the limitations of CTT.

A crucial nuance is that **CTT did not replace all other psychometrics**. Factor analysis, IRT, Rasch models, and modern latent-variable models are also major traditions. Likewise, Fechnerian scaling was never simply defeated in a direct historical competition with CTT: psychophysics and applied questionnaire measurement often pursued different tasks.

### 2.5 Teaching, software, and conventions reinforced adoption

Once summed ratings, alpha, and conventional validity analyses became routine, they were easy to teach, review, and reproduce. Borsboom (2006) argues that the dominance of CTT and operationalist habits helped create a gap between psychometric theory and everyday psychological practice.

This is a historical and sociological explanation, not a demonstration that the standard score is always the best scientific representation.

## 3. What did the popularity of CTT leave unresolved?

**A reliable score is not necessarily a psychologically meaningful coordinate.**

Two people may have the same depression total but very different patterns: one has marked sleep and appetite changes; another has loss of pleasure and suicidal thinking. If the same total score covers different psychological profiles, a line of summed scores may hide important variation.

Sijtsma (2009) cautions against treating Cronbach's alpha as proof of unidimensionality. Alpha alone does not establish that a test measures one coherent latent property. Tay and Jebb (2018) make a related, deeper argument: scale developers often spend more time selecting items than specifying what the full psychological continuum actually means, including its endpoints and the meaning of the positions in between.

Drasgow, Chernyshenko, and Stark (2010) revisit Thurstone and argue that some attitude or personality items are better explained by an **ideal-point** response process. A respondent may agree most with a statement close to their own position, rather than agreeing more as the supposed trait increases. The familiar dominance-response assumption can therefore be wrong for some instruments.

These points do **not** make summed ratings useless. They explain what a sum score cannot establish on its own: dimensionality, distances, item-response mechanisms, or the geometry of change.

## 4. Thurstonian versus Fechnerian scaling: similar data, different targets

Both approaches may use *pairs* of stimuli, but "pairwise data" do not define a unique scientific question.

**In a common Thurstonian comparison**, a person chooses which statement indicates more anxiety, which object is heavier, or which alternative is preferred. From many choices we estimate an ordered psychological location, often on a one-dimensional continuum. The classic model makes assumptions about judgment variability. Thurstonian models can be extended; classical one-dimensional scaling is not the entire family.

**In Fechnerian scaling**, the central input is how distinguishable or dissimilar stimuli are. The ambition is to combine local differences into meaningful distances between more distant points. In the continuous multidimensional theory of Dzhafarov and Colonius (2001), discrimination functions provide the local structure. Their 2023 general treatment extends this thinking to dissimilarity cumulation over chains of stimuli.

For example, pairwise questions of the form "Which of A and B is more severe?" are naturally about relative ordering. Questions of the form "How different do A and B feel?" or carefully designed same/different discrimination tasks are more directly relevant to distance construction. A pairwise comparison can contain either kind of information; the experimental design and response model determine what can be estimated.

**Neither method automatically discovers the psychological meaning of an axis.** Fechnerian scaling constructs distances; it does not simply output "one psychological dimension" or, by itself, the dimension count. Coordinate recovery (for example, with MDS) is a separate operation.

## 5. From Fechnerian distances to a psychological manifold

One possible workflow is:

**observations or discrimination judgments → a justified dissimilarity function → Fechnerian distance cumulation → low-dimensional embedding → independent psychological validation**.

This distinguishes *measurement*, *metric construction*, and *visualization*.

The 2023 Fechnerian scaling synthesis is especially important: for general discrete stimulus sets, dissimilarity cumulation can produce a distance construction. In suitable arc-connected spaces it can be understood through continuous paths. Under stronger smooth, locally Euclidean assumptions, the resulting geometry can be related to generalized Finsler geometry.

**Continuous numbers are not the same as a continuous psychological space.** A dataset with thousands or millions of sentence embeddings remains a finite sample. To argue that it approximates a smooth manifold, we need evidence of stable neighborhoods, intervening states, meaningful local directions, and geometry robust to sampling density and noise. There is no magic minimum sample count that proves continuity.

MDS can put pairwise relations on a two- or three-dimensional picture, but it does not validate a manifold. A statistical manifold also means something more specific than a scatterplot: in information geometry, each point stands for a probability distribution, not just a questionnaire respondent. A latent psychological state space, an observed-data embedding, and a family of probability distributions must not be silently identified with one another.

Shepard (1987) supplied a strong way to test the meaning of a psychological distance: see whether it predicts generalization behavior that was not used to construct the distance. Tversky (1977) showed that similarity judgments may be asymmetric and context-sensitive. Roads and Love (2024) explain why the relation between similarity and representation remains fundamental, but not automatically simple or metric.

A useful definition for this project is therefore:

> A *candidate psychological manifold* is a low-dimensional organization of psychological states or representations whose neighborhood structure, metric, and interpretation remain stable enough to predict independent psychological observations.

Existence of some representation is not equivalent to recovery of the correct representation. A mathematical existence theorem does not supply construct validity, unique identification, or measurement invariance.

## 6. Can cosine distances between therapy-turn embeddings provide Fechnerian input?

**Computationally, yes; psychometrically, only as an explicitly provisional proxy.**

One may compute pairwise cosine dissimilarities between utterance embeddings and then apply a dissimilarity-cumulation algorithm. This is an exploratory geometric construction. It is not automatically a Fechnerian *psychological* metric.

Why not?

- **The semantic similarity problem.** A language model was not necessarily trained to represent the experienced distance between psychological states. Different word choices may reflect speaker style, topic, language, context, or therapy technique rather than a difference in the target construct.
- **The measurement-target problem.** Distances from each therapy turn to Work Alliance Inventory (WAI) item embeddings may be useful alliance-related features, but they are not the same thing as distances *between* patient states. Goal, Task, and Bond labels are not automatically recovered manifold axes.
- **The metric problem.** One-minus-cosine is a dissimilarity, but generally not a mathematical metric: the triangle inequality need not hold. Constructing a path distance can repair some formal properties while introducing strong dependence on the sampled neighbor graph.
- **The sampling problem.** Sparse bridges, uneven density, transcription noise, and different speakers can create apparently long or short paths that have little clinical meaning.
- **The validation problem.** Good-looking clusters, an apparently smooth path, or agreement with a questionnaire used to define the embeddings can be circular evidence.

A responsible first comparison would retain simpler baselines: raw cosine dissimilarity, a symmetrized neighbor-graph distance, nonmetric MDS, and established symptom/alliance scores. The geometrical approach earns its place only if it preserves interpretable structure across resampling and predicts independent judgments or outcomes more effectively.

## 7. Why the Finsler/Randers idea is attractive—and difficult

The original motivation was not to add geometric machinery for its own sake. It was to ask whether **moving from a high-symptom state to a low-symptom state differs from moving back**. Ordinary symmetric distances cannot express that difference.

A Randers model offers an intuitive picture with two components:

- **A: the local landscape.** How movement differs across locations and directions before adding a preferred direction; the symmetric metric component.
- **B: a directional 'wind'.** How the cost of moving along a direction might differ from moving against it.

This picture is valuable because **the geometry of psychological differences and the dynamics of psychological change are not the same object**. A person's symptom position does not tell us how fast they are moving, why they move, or whether a therapist's intervention changes the next transition.

However, these attractive interpretations do not mean that A and B are identifiable from existing data.

### What the data cannot uniquely provide

1. **Symmetric cosine dissimilarities cannot identify a nonzero directional B.** If the only information is that turn X and turn Y have the same distance in both directions, a directional term has no empirical signature in that matrix.
2. **The order of therapy turns is not itself a directional transition cost.** Observed temporal order shows what happened, not what would have happened under the reverse movement, nor which costs are intrinsic rather than driven by context.
3. **Ordinal dissimilarities are not a unique cardinal Randers metric.** Additional scale, geometry, and regularity assumptions are needed.
4. **A and B cannot simply be 'read off' a Fechnerian distance matrix.** The R package `fechner` computes Fechnerian quantities; its oriented-distance outputs should not be relabeled as the Randers A and B parameters. An independent model and constraints are required.
5. **A fitted canonical model is not general recovery of the metric.** Dagès and colleagues' Finsler MDS (2025) studies asymmetric embeddings in a deliberately chosen canonical Finsler/Randers setting. Specifying or tuning a drift parameter does not estimate an arbitrary location-dependent A and B from symmetric input.

### Does predictive uncertainty provide B?

One discussed idea was to use epistemic uncertainty (limited model knowledge) plus aleatoric uncertainty (inherent unpredictability) from predicting the therapist's next response after a patient turn. This is a potentially interesting **predictor of uncertainty in the interaction**, but it is not automatically a directional one-form B.

Uncertainty may rise because of ambiguity, therapist style, unexpected language, topic changes, or weak model calibration. Adding epistemic and aleatoric terms requires a defined scale and calibration. To claim B represents the cost or ease of psychological change, one would need evidence that uncertainty predicts *direction-specific transitions* beyond these confounders. The same applies to other proposed choices for B.

The careful distinction is: **uncertainty may be a feature or mechanism in a transition model; it is not inherently the asymmetric metric itself**.

## 8. What would this mean for psychotherapy and COMPASS?

For an interpretable psychotherapy application, the suggested division of labor is:

**First, define and validate the psychological measurement space.** A COMPASS-style symptom/alliance trajectory may provide useful latent coordinates, but these should remain linked to independent clinical assessments, uncertainty estimates, and checks of construct validity. A geometry learned from language must not be described as clinical truth without validation.

**Second, estimate movement or transition patterns.** Repeated sessions allow a descriptive account of where the patient appears to be at successive times. If the data support it, a transition or state-space model can ask whether movement depends on prior state, therapist behavior, and context. Sparse time points, missing data, participant-specific differences, and rater error should be shown rather than hidden.

**Third, test whether asymmetry matters.** Compare a symmetric baseline to a directional model on held-out participants or independent outcomes. A directional model must add explanatory or predictive value; visualizing a 'wind' is not enough.

**Fourth, reserve a Randers interpretation for genuinely supported directional structure.** If the data do not identify a unique A and B, say so. A clinically interpretable velocity or transition model may be the stronger scientific result.

This suggests a practical ladder:

1. **Score quality:** Establish reliability and convergent/discriminant validity of the language-based constructs.
2. **Relational quality:** Test whether psychological judgments support a reproducible dissimilarity structure distinct from superficial text similarity.
3. **Geometric quality:** Compare raw distances, Fechnerian/path distances, and MDS; test stability of dimension and neighborhood structure.
4. **Dynamic quality:** Relate successive patient states to independently defined symptom or alliance change.
5. **Directional quality:** Only then evaluate whether asymmetric transitions require a directional geometric term and whether this improves held-out prediction.

Do not infer treatment efficacy or causal mechanisms merely from an observed trajectory. At most, the observational language provides hypotheses about change. The R `fechner` package's demonstration dataset `wish` provides stimulus judgments, not genuine psychotherapy timestamps; treating an ordering in that example as clinical time was a toy modeling assumption.

## 9. The central reflection

Psychometrics became widely useful by solving the problem of **trustworthy scores**. Classical psychophysics and scaling traditions asked a different problem: **what is the structure of psychological similarity, distance, and change?**

The resulting tension is productive:

- A reliable total score can be scientifically useful without representing a literal psychological distance.
- A Fechnerian distance can be mathematically valid without measuring the intended psychological construct.
- A low-dimensional embedding can be visually convincing without establishing a manifold.
- A trajectory can describe observed change without identifying its cause.
- An asymmetric geometric model can be mathematically possible without its A and B components being identifiable from the available observations.

**The most promising research contribution is not to replace CTT with a fashionable geometry. It is to show that validated geometric relationships reveal clinically or psychologically meaningful structure that well-constructed scores and standard trajectory models miss.**

---

## Influential and relevant papers

*Alphabetical by first author, following the [README.md](README.md) convention: numbered APA-style linked references with italicized notes. The notes distinguish published claims from the implications proposed for psychological manifolds.*

1. [Borsboom, D. (2006). The attack of the psychometricians. *Psychometrika, 71*(3), 425–440.](https://doi.org/10.1007/s11336-006-1447-6) <i>Explains the separation between modern psychometric theory and everyday psychology, including CTT's dominance. Useful for the institutional explanation of why conventional scoring practices persist; not evidence that geometry is inherently better.</i>
2. [Campbell, D. T., & Fiske, D. W. (1959). Convergent and discriminant validation by the multitrait-multimethod matrix. *Psychological Bulletin, 56*(2), 81–105.](https://doi.org/10.1037/h0046016) <i>Foundational account of validating constructs across traits and methods. A geometric representation needs independent convergent and discriminant evidence, not just internally consistent coordinates.</i>
3. [Cronbach, L. J. (1951). Coefficient alpha and the internal structure of tests. *Psychometrika, 16*(3), 297–334.](https://doi.org/10.1007/BF02310555) <i>Made coefficient alpha central to practical reliability assessment. The original formula should not be misread as proof of one-dimensional psychological geometry.</i>
4. [Cronbach, L. J., & Meehl, P. E. (1955). Construct validity in psychological tests. *Psychological Bulletin, 52*(4), 281–302.](https://doi.org/10.1037/h0040957) <i>The nomological-network approach shows why a test score—or a manifold coordinate—needs support from theory and independent observable relationships.</i>
5. [Dagès, T., Weber, S., Lin, Y.-W. E., Talmon, R., Cremers, D., Lindenbaum, M., Bruckstein, A. M., & Kimmel, R. (2025). Finsler multi-dimensional scaling: Manifold learning for asymmetric dimensionality reduction and embedding. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 25842–25853).](https://openaccess.thecvf.com/content/CVPR2025/html/Dages_Finsler_Multi-Dimensional_Scaling_Manifold_Learning_for_Asymmetric_Dimensionality_Reduction_and_CVPR_2025_paper.html) <i>A computational framework for embedding asymmetric dissimilarities in a canonical Finsler setting. It does not establish a turnkey estimator of arbitrary psychological Randers A and B from symmetric cosine distances.</i>
6. [Drasgow, F., Chernyshenko, O. S., & Stark, S. (2010). 75 years after Likert: Thurstone was right! *Industrial and Organizational Psychology, 3*(4), 465–476.](https://doi.org/10.1111/j.1754-9434.2010.01273.x) <i>Argues that ideal-point response models can fit some attitude/personality measurement processes better than conventional dominance assumptions, reopening a classical scaling debate.</i>
7. [Dzhafarov, E. N., & Colonius, H. (2001). Multidimensional Fechnerian scaling: Basics. *Journal of Mathematical Psychology, 45*(5), 670–719.](https://doi.org/10.1006/jmps.2000.1341) <i>Formal multidimensional construction of Fechnerian geometry from local psychometric discrimination functions. Demonstrates that Fechnerian scaling is not inherently one-dimensional.</i>
8. [Dzhafarov, E. N., & Colonius, H. (2023). Fechnerian scaling: Dissimilarity cumulation theory. In F. G. Ashby, H. Colonius, & E. N. Dzhafarov (Eds.), *New handbook of mathematical psychology* (Vol. 3, pp. 80–162). Cambridge University Press.](https://doi.org/10.1017/9781108902724.004) <i>The key modern synthesis: subjective dissimilarities can be cumulated over chains; with stronger connectedness and smoothness conditions this relates to path geometry and generalized Finsler geometry. It does not make arbitrary embedding cosine distances psychologically valid.</i>
9. [Hambleton, R. K., & Jones, R. W. (1993). Comparison of classical test theory and item response theory and their applications to test development. *Educational Measurement: Issues and Practice, 12*(3), 38–47.](https://doi.org/10.1111/j.1745-3992.1993.tb00543.x) <i>An influential practical comparison of CTT and IRT, explaining why CTT remains accessible while identifying its score- and sample-dependent limitations.</i>
10. [Likert, R. (1932). A technique for the measurement of attitudes. *Archives of Psychology, 22*(140), 1–55.](https://legacy.voteview.com/pdf/Likert_1932.pdf) <i>A historical turning point for efficient attitude-scale construction. Likert reported reliability advantages in his comparison with Thurstone, but efficiency does not prove a correct psychological distance scale.</i>
11. [Ramsay, J. O., Li, J., Wallmark, J., & Wiberg, M. (2025). An information manifold perspective for analyzing test data. *Applied Psychological Measurement, 49*(3), 90–108.](https://doi.org/10.1177/01466216241310600) <i>A modern example of explicitly geometric thinking about test information. Shows that psychometric measurement and manifold-based interpretations need not be isolated traditions; an information manifold is not automatically a patient's clinical state manifold.</i>
12. [Roads, B. D., & Love, B. C. (2024). Modeling similarity and psychological space. *Annual Review of Psychology, 75*, 215–240.](https://doi.org/10.1146/annurev-psych-040323-115131) <i>Highly relevant review linking similarity, representation, and psychological space. Helps frame what an embedding needs to mean beyond its visualization.</i>
13. [Shepard, R. N. (1987). Toward a universal law of generalization for psychological science. *Science, 237*(4820), 1317–1323.](https://doi.org/10.1126/science.3629243) <i>Foundational example of validating psychological distance against independent behavior: generalization probability. A stronger scientific target than merely obtaining a low-dimensional map.</i>
14. [Sijtsma, K. (2009). On the use, the misuse, and the very limited usefulness of Cronbach's alpha. *Psychometrika, 74*(1), 107–120.](https://doi.org/10.1007/s11336-008-9101-0) <i>Shows why alpha should not be interpreted as a measure of unidimensionality or as a comprehensive guarantee of reliability and structure.</i>
15. [Tay, L., & Jebb, A. T. (2018). Establishing construct continua in construct validation: The process of continuum specification. *Advances in Methods and Practices in Psychological Science, 1*(3), 375–388.](https://doi.org/10.1177/2515245918775707) <i>Argues that psychologists often underspecify what positions across an attribute continuum mean. Directly motivates renewed attention to the structure and interpretation of psychological scales.</i>
16. [Thurstone, L. L. (1927). A law of comparative judgment. *Psychological Review, 34*(4), 273–286.](https://doi.org/10.1037/h0070288) <i>Foundational psychophysical method for recovering scale locations from comparative choices. The ranking or latent-coordinate problem is distinct from building dissimilarity-based psychological distances.</i>
17. [Thurstone, L. L. (1928). Attitudes can be measured. *American Journal of Sociology, 33*(4), 529–554.](https://doi.org/10.1086/214483) <i>Early program for assigning statements and people to positions along an attitude continuum. Useful historical contrast to item sums that may lack explicitly specified psychological locations.</i>
18. [Tversky, A. (1977). Features of similarity. *Psychological Review, 84*(4), 327–352.](https://doi.org/10.1037/0033-295X.84.4.327) <i>Landmark demonstration that human similarity can be asymmetric and context dependent. Warns against equating every similarity score with a symmetric Euclidean psychological distance.</i>

## Open research questions

- Can psychological dissimilarity judgments about language-based clinical states be collected independently of the model that generated the embeddings?
- When do Fechnerian path distances improve on raw similarities or ordinary nonmetric MDS for predicting judgments, symptoms, or future state transitions?
- Can a shared latent representation preserve person-specific differences without imposing the same local metric on all patients?
- Does direction-sensitive modeling explain psychotherapy changes beyond measurement noise, therapist behavior, and ordinary state-space dynamics?
- What is the minimum empirical evidence required before calling a trajectory a *psychological manifold* rather than a sequence of model-derived scores?
