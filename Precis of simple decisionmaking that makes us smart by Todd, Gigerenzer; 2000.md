## Components of a heuristic
#### System I vs System II
system II: 
linear regression
multiple linear regression
optimization problems

Laplace's 'superintelligence'

#### Example of a problem to be solved using a heuristic:
which chick does the bird parent feed first when it comes back from scavenging,
multiple chicks,
multiple dimension along which we can rate each chick (weight, hunger, volume, size, etc.)

Bird parent's question: Which one to feed first? (strategy presumably encoded evolutionarily)
Psychologists question: How to determine the strategy to decide which to feed (i.e. find a way to decide how you're going to decide decide :D = search for a heuristic)

#### Classes of heuristics:
1. Ignorance-based decision making
2. One-reason decision making
3. Elimination for multiple choice
4. Satisficing

## 1. Ignorance-based decision making (no concrete info)
#### dichotomous decision task: recognition heuristic
pick the version you recognize/are more familiar with
strong when: exposure is correlated with ranking along the decision criterion
e.g.: choice of food, choice of friends or allies, size of cities! (we hear about big ones more), stock picking (surprisingly, fame is a good predictor of investment viability), etc.
this causes a **less-is-more effect** -> if you are more knowledgeable the choices correlated less closely with the decision criterion, and more with knowledge itself

## 2. One-reason decision making (multiple dimensions, pick one)
#### dichotomous decision task: One-dimensional differentiator 
Stop looking for cues as soon as one is found that differentiates between the two options being considered.

Choose a (different) criterion > do the options differ on this scale?
yes (**stopping rule**) > pick the more desirable one (**decision rule**)
no > continue search for criterion which contrasts the two (**search rule**)

*a simple cue-based heuristic that sticks to present knowledge can outperform rules that attempt to predict an uncertain future, because it avoids the compounded noise that accumulates the further forward one strains to look.*

## 3. Elimination for multiple choice (multiple choices, multiple sparse dimensions)
in some situations, dimensions have less values than available choices (imagine a binary variable, i.e. employment status?)- making some of them equal to each other. When we cant differentiate between them with one dimension, we must utilize more than one. But how do we do this without incurring costly energy expenditure of System II?
Process. Of. Elimination.
narrowing down remaining options by eliminating them along the criterion of interest
strong when: pattern of data is a result of accretionary growth, fast classification by elimination

example: QuickEst (quick estimate)
*To estimate the criterion value of a particular object, the heuristic looks through the cues or features in this order until it comes to the first one that the object does not possess,*
*QuickEst then gives the “rounded” mean criterion value associated with the absence of that cue as its final estimate*
**No cue combination is necessary, and no adjustment from further cues is possible**

## 4. Satisficing (e.g., when to stop the search for alternatives)
#### Based on the work of Herbert Simon
a) setting an aspiration level for the given selection criterion (how high or low?)
b) **stopping the search when the aspiration level has been met or exceeded**


# *Ecological* rationality of heuristics
- they're not sophisticated, but in the right natural environment they work well enough
- -> necessary to MATCH to ENVIRONMENT (structure of information like criterion availability, choice paradigm, etc.)

so how do they not fall prey to **speed-accuracy trade-offs** (and are still accurate while being very fast)
because, they trade off **generality** and **specificity**

*different environments can have different specific fast and frugal heuristics that* ***exploit their particular information structure*** *to make adaptive decisions.*

*But specificity can also be a danger: if a different heuristic were required for every slightly different decision-making environment, we would need an unworkable multitude of heuristics to reason with, and we would not be able to generalize to previously unencountered environments. Fast and frugal heuristics avoid this trap by their very simplicity, which allows them to be robust when confronted by environmental change and enables them to generalize well to new situations.*

### Ecological rationality = heuristic x environment synergy
structure of the environment that can make heuristics ecologically rational
**Noncompensatory information**. The Take the Best heuristic equals or outperforms any linear decision strategy when information is noncompensatory, that is, when the potential contribution of each new cue falls off rapidly (Ch. 6). 
**Scarce information**. Take The Best outperforms a class of linear models on average when few cues are known relative to the number of objects (Ch. 6). 
**J-shaped distributions**. The QuickEst heuristic estimates quantities about as accurately as more complex information-demanding strategies when the criterion to be estimated follows a J-shaped distribution, that is, one with many small values and few high values (Ch. 10). 
**Decreasing populations.** In situations where the set of alternatives to choose from is constantly shrinking, such as in a seasonal mating pool, a satisficing heuristic that commits to an aspiration level quickly will outperform rules that sample many alternatives before setting an aspiration (Ch. 13). 
By matching these structures of information in the environment with the structure implicit in their building blocks, heuristics can be accurate without being too complex. In addition, by being simple, these heuristics can avoid being too closely matched to any particular environment – that is, they can escape the curse of overfitting, which often strikes more complex, parameter-laden models, as described next. This marriage of structure with simplicity produces the counterintuitive situations in which there is little trade-off between being fast and frugal and being accurate.

### On robustness:
Fast and frugal heuristics focus on the good predictors, while omitting the bad ones. They can be a better choice of model because they don't concern themselves with ALL the details. They literally avoid overfitting by not paying attention to bad predictors, which would only make them memorize the data. 

### On evaluation: 
usually human decision making is evaluated on *internal* ***coherence***
the authors propose evaluating it on ***correspondence*** *criteria*
*accuracy, frugality and speed*

## Heuristic building blocks:
#### Stopping rule
(a rule when the person stops a search)
e.g.:
- satisficing (Herbert Simon)  - first one that meets a set standard, if not met, lower standard and re-search

#### Decision rule
- when to decide a satisfactory value along a criterion has been reached

#### Search rule
**order in which to search cue dimensions**(each decision has multiple criteria to be judged on, this is the strategy determining which one to start with)

- **minimalist** (random order of options to cycle through)
- **take the best** (the one that has the highest validity - determined by counting accuracy of each heuristic for each of the decisions in the past)
- **take the last** (decision dimensions searched in order of reverse chronology)

-> Heuristics can be nested to produce more complex systems of evaluation and search

My contention: 
these heuristics are how we interact with cortical columns at varying levels of the cortical hierarchy when making choices!

they can be practically used to explain:

supermarket shopping choices
in overloaded choice architecture, people tend to abide by the simple rules, as making a quantified decision is nearly impossible
i.e. running a multilinear regression for all of the weights of all of the decision dimensions takes too much mental energy, so people choose based on familiarity (lowest level), or based on only one differentiating criterion that is desirable to them: like price, or conversely quality, or packaging, etc (level 2), or they choose the option that fulfills an above average number of criteria - ‘satisficing’ (level 3)


making choices in measurement in a survey
tired people ( i.e. almost anyone towards the end of the survey), and for whom the survey has no real consequences, will start making more and more ‘simplistic’ measurements within choice differentiation; especially when there are no easy answers


or when grading papers
another ‘choice’ architecture, where you have to find ways to differentiate between choices
the consequences of the grade can vary based on the teacher’s ideals about grading essays - a teacher who has a strong will to be fair for every single student will dedicate a large amount of cognitive effort to selecting the right grade; on the other hand a teacher who doesn’t care about the students, and how the grade might impact their personal lives, self-esteem or what have you, will dedicate less cognitive effort to the level of detail they put in the analysis of the students writing. Put shortly - the teachers use of multilinearity is determined by how internalised their ideals about fairness are, and whether they have resolved to be meticulous in trying to see the value in their students’ work



Feature binding:

in a way, the feature binding paradigm (which is mentioned in the Gigerenzer paper) is a good example of a vertical move up on the ordinal scale of complexity of heuristics. 

feature-binding is a process, where you go from 1 relevant dimension to 2 dimensions (color -> color and shape)
this requires more conscious effort (relative to the lower level 1-down) and thus is slower
is feature-binding an example of our ‘problem-solving capacity’ interacting with one of the lowest levels of the cognitive hierarchy

this interaction also exists on more abstract levels - e.g. the supermarket-shopping example (rating based on pragmatic criteria), or the test-grading example (rating based on abstract criteria)

these are three great examples in order of abstraction (just like the ‘cerebral gradient’ - excuse the jargonisation)
measurement of scale or duration (unmentioned as of yet) 
feature binding
supermarket shopping
answering a questionnaire
grading papers

the measurement of scale or duration is contentious, as I can't find an existing heuristic to base it on, but in a way the measurement is prone to errors that hint at the possibility that it is using the ‘structure of information’ (i.e. strength/size of the representation), rather than processing the full information content (actually measuring the span in the visual field, etc.).

Perhaps this is just a quirk of the actual measurement system, which is active in the alter heuristics in placing an item along a criterion scale, i.e. measuring how far along on the measurement axis it is. This doesn't make it a procedural heuristic like the others (the recognition heuristic also isn't procedural as it can exist with 1 criterion and 1+1alternative - much like the rating where we are rating something comparatively)


