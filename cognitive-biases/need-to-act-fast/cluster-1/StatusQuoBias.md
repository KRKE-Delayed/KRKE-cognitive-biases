# Status quo bias

*## CLUSTER: To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions*

## 1. Context and Literature State of the Art

**Wikipedia:**
Status quo bias is an emotional bias; a preference for the maintenance of one's current or previous state of affairs, or a preference to not undertake any action to change this current or previous state. The current baseline (or status quo) is taken as a reference point, and any change from that baseline is perceived as a loss or gain. Corresponding to different alternatives, this current baseline or default option is perceived and evaluated by individuals as a positive. [Wikipedia Link](https://en.wikipedia.org/wiki/Status_quo_bias)

**Reasearch paper:**
[Samuelson, W., Zeckhauser, R., 1988. Status quo bias in decision making. J. Risk Uncertain. 1, 7–59.](https://scholar.harvard.edu/files/rzeckhauser/files/status_quo_bias_in_decision_making.pdf)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Status quo bias"**

"Status quo bias" refers to the tendency of individuals to prefer the `current` or existing state of affairs over potential `changes` or alternatives. It is a `cognitive bias` that influences `decision-making`, often leading to a `resistance` or reluctance to make changes even when they may be beneficial.

People with status quo bias tend to perceive the current situation as more comfortable, `familiar`, and less risky than potential alternatives. They may exhibit a preference for maintaining the current state, even when objectively better options are available. This bias can arise due to various factors, including fear of `uncertainty`, aversion to potential losses, and a desire to avoid the effort or disruption associated with change.

Status quo bias can impact various areas of life, including personal choices, organizational decision-making, public policy, and even societal norms. It can hinder progress, innovation, and adaptation to new circumstances. Recognizing and understanding status quo bias is important in order to make informed decisions and consider alternative possibilities that might lead to positive change.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Status quo bias"**

1. **Company Decision-Making:** A company has been following outdated practices for years, but employees `resist` implementing `new` technologies or processes because they `prefer` the `familiar` way of doing things.

2. **Political Elections:** Voters tend to favor incumbent candidates over `new` contenders, even if the incumbent's performance has been unsatisfactory, due to a perceived sense of `stability` and `fear` of the `unknown`.

3. **Investment Strategies:** Investors stick to `traditional` investment options and are reluctant to explore `new`, potentially more profitable opportunities, as they `prefer` the stability and `familiarity` of their current investments.

4. **Organizational Change:** Employees `resist` changes in organizational structure or policies, fearing the disruption and `uncertainty` that may come with the proposed changes, despite potential benefits.

5. **Personal Relationships:** Individuals stay in unhealthy or unfulfilling relationships due to a `fear` of being alone or the `uncertainty` of starting anew, even if leaving might lead to better long-term outcomes.

6. **Technology Adoption:** People may hesitate to adopt `new` technologies, such as switching from `traditional` banking to online banking, because they feel more comfortable with their current methods, despite potential advantages.

7. **Environmental Conservation:** Despite evidence of the negative impact of certain behaviors on the environment, individuals may be resistant to change their habits or reduce consumption due to the `comfort` and `convenience` of the status quo.

8. **Healthcare Decision-Making:** Patients may reject alternative treatment options or innovative therapies due to a `preference` for `traditional` or `familiar` medical approaches, even if the `new` options offer better outcomes.

9. **Educational Systems:** Resistance to educational reforms, such as implementing `new` teaching methods or curriculum changes, can stem from the `preference` for maintaining established practices, even if they are outdated.

10. **Social Norms:** Society may `resist` changes in social norms, such as gender roles or cultural `traditions`, due to a `preference` for preserving existing customs, even if those norms perpetuate inequality or outdated beliefs.

These scenarios highlight how status quo bias can influence decision-making across various domains, hindering progress and potential improvements in favor of maintaining the current state of affairs.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Social Norms" and give me a small user story from it**

**User Story: Challenging Gender Stereotypes**

As a socially conscious individual, I want to challenge gender `stereotypes` and promote equality in my community. I aim to break free from `traditional` social norms and make a positive impact by advocating for inclusivity and diversity.

By initiating conversations, supporting initiatives, educating myself, and encouraging open-mindedness, I will actively `challenge the existing` gender norms. I will engage with media critically, support marginalized voices, and actively participate in discussions promoting gender equality. I will reflect on my own behavior, avoiding perpetuating stereotypes, and fostering an environment of respect and understanding.

Ultimately, I seek to contribute to a more inclusive society by challenging and dismantling gender `stereotypes`, fostering equal opportunities, and promoting individual expression beyond societal expectations.

***We can now derive CQs from the user story***

* CQ1: What are the characteristics of entities that challenge existing norms in a specific context?
* CQ2: How can we represent the concept of "traditional" norms and their influence on entities' decisions and actions?
* CQ3: What actions or initiatives are taken by entities to challenge and change existing norms?
* CQ4: What are the potential consequences of perpetuating biases, and how can we represent them?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Status quo bias", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the status quo bias. This class serves as a superclass for specific types of biases, such as GenderBias, ConfirmationBias, or AvailabilityBias.
2. **StatusQuoBias:** The main class representing the status quo bias itself.
3. **DecisionMaker:** Represents individuals or entities who make decisions influenced by biases, including the status quo bias. Subclasses of DecisionMaker can be used to represent different types of decision-makers, such as Individuals, Organizations, or Governments.
4. **Norm:** Represents societal norms, including traditional norms, that influence entities' decisions and actions. Subclasses can be created to represent different types of norms, such as GenderNorm, CulturalNorm, or LegalNorm.
5. **Alternative:** Represents the potential options or alternatives that are being considered in a decision-making process.
6. **Change:** Represents the concept of making a change or deviating from the current state of affairs.
7. **Factor:** Represents the factors that contribute to the perpetuation of biases. Subclasses can represent various types of factors, such as SocialFactors, CognitiveFactors, or EnvironmentalFactors.
8. **Consequence:** Represents the potential outcomes or consequences of perpetuating biases. Subclasses can represent different types of consequences, such as SocialConsequence, EconomicConsequence, or PsychologicalConsequence.

**Properties:**

1. **hasStatusQuoBias:** Indicates that a DecisionMaker is influenced by the status quo bias.
2. **prefersStatusQuo:** Indicates the preference of a DecisionMaker for the current state of affairs.
3. **considersAlternative:** Relates a DecisionMaker to an Alternative being considered.
4. **influencedByNorm:** Relates a DecisionMaker to a Norm that influences their decisions and actions.
5. **evaluatesConsequences:** Represents the evaluation of the consequences or potential outcomes associated with an Alternative.
6. **contributesToBias:** Relates a Factor to a specific type of Bias it contributes to, such as ConfirmationBias or AvailabilityBias.
7. **leadsToConsequence:** Relates a Bias to a Consequence it may lead to, such as SocialConsequence or EconomicConsequence.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Decision-Making in a Workplace*

Entities: John (Individual), XYZ Corporation (Organization)
Class: DecisionMaker
Property: hasStatusQuoBias true (for John)

Description: John works at XYZ Corporation and is responsible for making decisions regarding project assignments. He tends to favor the current team structure, often opting for the status quo, even if alternative team compositions could lead to better outcomes. The ontology can represent John as a DecisionMaker with the status quo bias (hasStatusQuoBias true). It can also capture the alternatives considered for team compositions (Alternative class) and how John evaluates the potential outcomes (evaluatesConsequences) when making these decisions.

*Example 2: Challenging Gender Stereotypes Initiative*

Entities: Sarah (Individual), Diverse Voices NGO (Organization)
Classes: DecisionMaker, Alternative, Change
Properties: considersAlternative, takesAction

Description: Sarah is an advocate for gender equality and works with the Diverse Voices NGO. She launches an initiative to challenge gender stereotypes in media portrayals. The ontology can represent Sarah as a DecisionMaker and the initiative as an Alternative she is considering (considersAlternative). Additionally, it can capture the action Sarah takes by leading the initiative (takesAction) to promote positive change (Change class) in media representation, aiming to reduce the perpetuation of gender biases (CognitiveBias class).

*Example 3: Cultural Norms and Gender Biases*

Entities: USA (Country), Masculinity Norm (Norm)
Classes: Norm, Bias
Properties: influencesDecisionMaker, contributesToBias

Description: In the USA, there exists a strong cultural norm of masculinity, which influences decision-makers, including those in the entertainment industry. This norm perpetuates gender biases in character portrayals and storylines. The ontology can represent the Norm class, with instances such as "Masculinity Norm," influencing decision-makers in the entertainment industry (influencesDecisionMaker). It can also capture how this norm contributes to the perpetuation of gender biases (contributesToBias), such as gender stereotypes and the status quo bias in character development.

These examples demonstrate how the classes and properties of the ontology can be used to represent specific instances and relationships related to biases, decision-making, norms, actions, and consequences in various scenarios. By utilizing the ontology, you can effectively capture, organize, and reason about the data and knowledge within the domain of cognitive biases, enabling more insightful analysis and understanding of how biases influence decision-making and societal outcomes.

## 3. Lexical Units (LUs) to evoque frames from Framster

For this bias we tried with these LUs:
tradition
costum
preserve
norm
current

The resulting frames are:
        "https://w3id.org/framester/data/framestercore/Containing", 
        "https://w3id.org/framester/data/framestercore/Custom", 
        "https://w3id.org/framester/data/framestercore/Inclusion", 
        "https://w3id.org/framester/data/framestercore/ActivityOngoing", 
        "https://w3id.org/framester/data/framestercore/ActivityPrepare", 
        "https://w3id.org/framester/data/framestercore/ActivityStop", 
        "https://w3id.org/framester/data/framestercore/CauseToContinue", 
        "https://w3id.org/framester/data/framestercore/CauseToStart", 
        "https://w3id.org/framester/data/framestercore/ComingUpWith", 
        "https://w3id.org/framester/data/framestercore/Compliance", 
        "https://w3id.org/framester/data/framestercore/CookingCreation", 
        "https://w3id.org/framester/data/framestercore/Creating", 
        "https://w3id.org/framester/data/framestercore/Defend", 
        "https://w3id.org/framester/data/framestercore/Employing", 
        "https://w3id.org/framester/data/framestercore/Food", 
        "https://w3id.org/framester/data/framestercore/Motion", 
        "https://w3id.org/framester/data/framestercore/People", 
        "https://w3id.org/framester/data/framestercore/PoliticalLocales", 
        "https://w3id.org/framester/data/framestercore/Possession", 
        "https://w3id.org/framester/data/framestercore/ProcessContinue", 
        "https://w3id.org/framester/data/framestercore/ProcessStop", 
        "https://w3id.org/framester/data/framestercore/Protecting", 
        "https://w3id.org/framester/data/framestercore/SelfMotion", 
        "https://w3id.org/framester/data/framestercore/TakingSides", 
        "https://w3id.org/framester/data/framestercore/Travel", 
        "https://w3id.org/framester/data/framestercore/Building", 
        "https://w3id.org/framester/data/framestercore/IntentionallyCreate", 
        "https://w3id.org/framester/data/framestercore/Preserving", 
        "https://w3id.org/framester/data/framestercore/StateOfEntity", 
        "https://w3id.org/framester/data/framestercore/Accomplishment", 
        "https://w3id.org/framester/data/framestercore/AmountingTo", 
        "https://w3id.org/framester/data/framestercore/Cogitation", 
        "https://w3id.org/framester/data/framestercore/PerformersAndRoles", 
        "https://w3id.org/framester/data/framestercore/SuccessOrFailure", 
        "https://w3id.org/framester/data/framestercore/Quantity", 
        "https://w3id.org/framester/data/framestercore/SuccessfulAction", 
        "https://w3id.org/framester/data/framestercore/Arranging", 
        "https://w3id.org/framester/data/framestercore/Event", 
        "https://w3id.org/framester/data/framestercore/TemporalCollocation", 
        "https://w3id.org/framester/data/framestercore/Quantity", 
        "https://w3id.org/framester/data/framestercore/Sequence", 
        "https://w3id.org/framester/data/framestercore/Electricity"

While putting a scenario in FRED we obtain:

Society may resist changes in social norms, such as gender roles or cultural traditions, due to a preference for preserving existing customs, even if those norms perpetuate inequality or outdated beliefs.


Output format: 
Turtle
 
Result
<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_142_146_even>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "even"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "142"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "146"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#RB> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#custom_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#ExistingCustom> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Existing> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Norm>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_37_42_norms>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "norms"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_1> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_2> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Norm> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "37"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "42"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_49_51_as>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "as"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#As> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "49"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "51"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#perpetuate_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perpetuate> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#agent>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_2> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#patient>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#inequality_1> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#belief_1> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#hasModality>
                <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#Possible> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#entails>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#resist_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#union>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#outdate_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Existing>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/TimeVector> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-existing-adjectivesatellite-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_157_159_or>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "or"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Union> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "157"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "159"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#CC> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_77_87_traditions>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "traditions"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#tradition_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tradition> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "77"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "87"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perpetuate>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> , <https://w3id.org/framester/data/framestercore/ActivityOngoing> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-perpetuate-verb-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Inequality>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#Characteristic> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_attribute> , <https://w3id.org/framester/data/framestercore/Similarity> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-inequality-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_65_67_or>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "or"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Union> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "65"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "67"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#CC> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_173_183_inequality>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "inequality"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#inequality_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Inequality> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "173"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "183"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_98_108_preference>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "preference"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preference_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preference> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "98"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "108"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_59_64_roles>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "roles"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Role> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "59"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "64"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#resist_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Resist> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#agent>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Society> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#patient>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#change_1> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#hasModality>
                <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#Possible> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#dueTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preference_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_133_140_customs>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "customs"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#custom_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Custom> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "133"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "140"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preference>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_feeling> , <https://w3id.org/framester/data/framestercore/Inclination> , <http://www.ontologydesignpatterns.org/ont/d0.owl#CognitiveEntity> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-preference-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#outdate_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Outdate> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#patient>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#belief_1> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#hasModality>
                <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#Possible> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_2>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Norm> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#those> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#SocialNorm> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Social> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_124_132_existing>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "existing"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Existing> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "124"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "132"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#tradition_1>
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preference_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preference> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#a> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Custom>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Society>
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#possibleType>
                <http://www.w3.org/2002/07/owl#Thing> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_147_149_if>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "if"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Entails> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "147"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "149"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_89_92_due>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "due"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "89"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "92"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_162_172_perpetuate>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "perpetuate"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#perpetuate_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perpetuate> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "162"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "172"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VBP> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_12_18_resist>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "resist"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#resist_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Resist> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "12"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "18"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VB> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_52_58_gender>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "gender"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#gender_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Gender> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "52"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "58"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#change_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Change> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#as>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#in>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preserve>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/Preserving> , <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> , <https://w3id.org/framester/data/framestercore/Possession> , <https://w3id.org/framester/data/framestercore/IntentionallyCreate> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.ontologydesignpatterns.org/ont/vn/data/Preserve_85000000> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-inequality-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "lack of equality; \"the growing inequality between rich and poor\""@en-us .

<http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_196_203_beliefs>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "beliefs"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#belief_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Belief> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "196"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "203"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#in>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_113_123_preserving>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "preserving"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preserve_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preserve> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "113"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "123"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VBG> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#entails>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_19_26_changes>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "changes"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#change_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Change> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "19"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "26"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_187_195_outdated>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "outdated"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#outdate_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Outdate> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "187"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "195"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VBN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Outdate>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#disjunct_2>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Disjunct> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#involves>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Cultural> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tradition> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preserve_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Preserve> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#hasModality>
                <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#Possible> ;
        <http://www.ontologydesignpatterns.org/ont/vn/abox/role/Agent>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#preference_1> ;
        <http://www.ontologydesignpatterns.org/ont/vn/abox/role/Theme>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#custom_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Social>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/SocialInteractionEvaluation> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-social-adjective-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_93_95_to>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "to"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#To> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "93"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "95"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#TO> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Role>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#union>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_27_29_in>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "in"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#In> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "27"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "29"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_68_76_cultural>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "cultural"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Cultural> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "68"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "76"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#GenderRole> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#CulturalTradition> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Cultural> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_0_7_Society>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "Society"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Society> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "0"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "7"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNP> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#dueTo>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#belief_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Belief> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Gender>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Organism> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_communication> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-gender-noun-1> .

<http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse>
        a       <http://www.essepuntato.it/2008/12/earmark#StringDocuverse> ;
        <http://www.essepuntato.it/2008/12/earmark#hasContent>
                "Society may resist changes in social norms, such as gender roles or cultural traditions, due to a preference for preserving existing customs, even if those norms perpetuate inequality or outdated beliefs."^^<http://www.w3.org/2001/XMLSchema#string> .

<http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#associatedWith>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#hasModality>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#gender_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Gender> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#associatedWith>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#such> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_30_36_social>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "social"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Social> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "30"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "36"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#agent>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Resist>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-defy-verb-2> .

<http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tradition>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#as>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_150_161_those+norms>
        <http://www.ontologydesignpatterns.org/ont/cnlp/coref.owl#coref>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#norm_2> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#possibleType>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-even-adjective-1> .

<http://www.essepuntato.it/2008/12/earmark#refersTo>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.essepuntato.it/2008/12/earmark#ends>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.essepuntato.it/2008/12/earmark#hasContent>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2002/07/owl#equivalentClass>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#disjunct_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Disjunct> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#involves>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Role> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#role_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#union>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#disjunct_2> .

<http://www.essepuntato.it/2008/12/earmark#begins>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#inequality_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Inequality> .

<http://www.ontologydesignpatterns.org/ont/vn/abox/role/Theme>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#CulturalTradition>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tradition> .

<http://www.ontologydesignpatterns.org/ont/vn/abox/role/Agent>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/cnlp/coref.owl#coref>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#patient>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#GenderRole>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Role> .

<http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-gender-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "a grammatical category in inflected languages governing the agreement between nouns and pronouns and adjectives; in some languages it is quite arbitrary but in Indo-European languages it is usually based on sex or animateness"@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Cultural>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-cultural-adjectivesatellite-2> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#SocialNorm>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Norm> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Change>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#ExistingCustom>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Custom> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#involves>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Belief>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.w3.org/2000/01/rdf-schema#subClassOf>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-preference-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "a strong liking; \"my own preference is for good literature\"; \"the Irish have a penchant for blarney\""@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> .

By doing these two steps we see that for example the frame "Preserving" is evoqued in both cases. And checking with our definition we see that also "Preserving" and "Custom" can be useful.

