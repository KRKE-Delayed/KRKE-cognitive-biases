# Project documentation

In this documentation, we will outline all the phases that we will go through during the project of modeling two biases. The main goal is to create an ontology for semantic web technologies following the pattern-based ontology design method called 'eXtreme Design'.

# To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions

## Status quo bias

### 1. Context and Literature State of the Art
To understand the context and to ensure that our ontology will be aligned with current understading and research in the field we provide a Wikipedia definition of the bias and a link to research papers about the topic.

**Wikipedia:**
Status quo bias is an emotional bias; a preference for the maintenance of one's current or previous state of affairs, or a preference to not undertake any action to change this current or previous state. The current baseline (or status quo) is taken as a reference point, and any change from that baseline is perceived as a loss or gain. Corresponding to different alternatives, this current baseline or default option is perceived and evaluated by individuals as a positive. [Wikipedia Link](https://en.wikipedia.org/wiki/Status_quo_bias)

**Reasearch paper:**
[Samuelson, W., Zeckhauser, R., 1988. Status quo bias in decision making. J. Risk Uncertain. 1, 7–59.](https://scholar.harvard.edu/files/rzeckhauser/files/status_quo_bias_in_decision_making.pdf)

### 2. Large Language Models (LLMs)
Powerful natural language processing models like ChatGPT-3.5 have the ability to generate human-like text. LLMs can assist in ontology development by providing suggestions, genereting ontological elements and aiding in the extraction of relevant information from textual sources.

***Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Status quo bias"**

Status quo bias refers to the tendency of individuals to prefer the current or existing state of affairs over potential changes or alternatives. It is a `cognitive bias` that influences `decision-making`, often leading to a `resistance or reluctance to make changes` even when they may be beneficial.

People with status quo bias tend to perceive the current situation as more comfortable, familiar, and less risky than potential alternatives. They may exhibit a preference for maintaining the current state, even when objectively better options are available. This bias can arise due to various factors, including fear of uncertainty, aversion to potential losses, and a desire to avoid the effort or disruption associated with change.

Status quo bias can impact various areas of life, including personal choices, organizational decision-making, public policy, and even societal norms. It can hinder progress, innovation, and adaptation to new circumstances. Recognizing and understanding status quo bias is important in order to make informed decisions and consider alternative possibilities that might lead to positive change.

***Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios od "Status quo bias"**

Certainly! Here are ten example scenarios that illustrate the presence of status quo bias:

1. Company `Decision-Making`: A company has been following outdated practices for years, but employees `resist` implementing `new` technologies or processes because they `prefer` the `familiar` way of doing things.

2. Political Elections: Voters tend to favor incumbent candidates over `new` contenders, even if the incumbent's performance has been unsatisfactory, due to a perceived sense of `stability` and `fear` of the `unknown`.

3. Investment Strategies: Investors stick to `traditional` investment options and are reluctant to explore `new`, potentially more profitable opportunities, as they `prefer` the stability and `familiarity` of their current investments.

4. Organizational Change: Employees `resist` changes in organizational structure or policies, fearing the disruption and `uncertainty` that may come with the proposed changes, despite potential benefits.

5. Personal Relationships: Individuals stay in unhealthy or unfulfilling relationships due to a `fear` of being alone or the `uncertainty` of starting anew, even if leaving might lead to better long-term outcomes.

6. Technology Adoption: People may hesitate to adopt `new` technologies, such as switching from `traditional` banking to online banking, because they feel more comfortable with their current methods, despite potential advantages.

7. Environmental Conservation: Despite evidence of the negative impact of certain behaviors on the environment, individuals may be resistant to change their habits or reduce consumption due to the `comfort` and `convenience` of the status quo.

8. Healthcare Decision-Making: Patients may reject alternative treatment options or innovative therapies due to a `preference` for `traditional` or `familiar` medical approaches, even if the `new` options offer better outcomes.

9. Educational Systems: Resistance to educational reforms, such as implementing `new` teaching methods or curriculum changes, can stem from the `preference` for maintaining established practices, even if they are outdated.

10. Social Norms: Society may `resist` changes in social norms, such as gender roles or cultural `traditions`, due to a `preference` for preserving existing customs, even if those norms perpetuate inequality or outdated beliefs.

These scenarios highlight how status quo bias can influence decision-making across various domains, hindering progress and potential improvements in favor of maintaining the current state of affairs.

***Let's ask for some user story and competency questions***

**Consider the scenario "Social Norms" and give me a small user story from it**

User Story: Challenging Gender Stereotypes

As a socially conscious individual, I want to challenge gender `stereotypes` and promote equality in my community. I aim to break free from `traditional` social norms and make a positive impact by advocating for inclusivity and diversity.

By initiating conversations, supporting initiatives, educating myself, and encouraging open-mindedness, I will actively `challenge the existing` gender norms. I will engage with media critically, support marginalized voices, and actively participate in discussions promoting gender equality. I will reflect on my own behavior, avoiding perpetuating stereotypes, and fostering an environment of respect and understanding.

Ultimately, I seek to contribute to a more inclusive society by challenging and dismantling gender `stereotypes`, fostering equal opportunities, and promoting individual expression beyond societal expectations.

*We can now derive CQs from the user story*

Following the XD procedure, we now need to analyze CQs in terms of classes and properties restrictions in order to be able to answer our questions. The goal is to use the CQs to divide a complex situation into already existing frames.

* CQ1: What are the characteristics of entities that challenge existing norms in a specific context?
* CQ2: How can we represent the concept of "traditional" norms and their influence on entities' decisions and actions?
* CQ3: What actions or initiatives are taken by entities to challenge and change existing norms?
* CQ4: What are the potential consequences of perpetuating biases

***Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Status quo bias", what classes and properties would you create?**

*Classes:*
1. CongnitiveBias: Represents various types of biases, including the status quo bias. This class serves as a superclass for specific types of biases, such as GenderBias, ConfirmationBias, or AvailabilityBias.
2. StatusQuoBias: The main class representing the status quo bias itself.
3. DecisionMaker: Represents individuals or entities who make decisions influenced by biases, including the status quo bias. Subclasses of DecisionMaker can be used to represent different types of decision-makers, such as Individuals, Organizations, or Governments.
4. Norm: Represents individuals or entities who make decisions influenced by biases, including the status quo bias. Subclasses of DecisionMaker can be used to represent different types of decision-makers, such as Individuals, Organizations, or Governments.
5. Alternative: Represents the potential options or alternatives that are being considered in a decision-making process.
6. Change: Represents the concept of making a change or deviating from the current state of affairs.
7. Factor: Represents the factors that contribute to the perpetuation of biases. Subclasses can represent various types of factors, such as SocialFactors, CognitiveFactors, or EnvironmentalFactors.
8. Consequence: Represents the potential outcomes or consequences of perpetuating biases. Subclasses can represent different types of consequences, such as SocialConsequence, EconomicConsequence, or PsychologicalConsequence.

*Properties:*
1. hasStatusQuoBias: Indicates that a DecisionMaker is influenced by the status quo bias.
2. prefersStatusQuo: Indicates the preference of a DecisionMaker for the current state of affairs.
3. considersAlternative: Relates a DecisionMaker to an Alternative being considered.
4. influencedByNorm: Relates a DecisionMaker to a Norm that influences their decisions and actions.
5. evaluatesConsequences: Represents the evaluation of the consequences or potential outcomes associated with an Alternative.
6. contributesToBias: Relates a Factor to a specific type of Bias it contributes to, such as ConfirmationBias or AvailabilityBias.
7. leadsToConsequence: Relates a Bias to a Consequence it may lead to, such as SocialConsequence or EconomicConsequence.

**Let's ask for some example of usage of the ontology**

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

### 3. Ontology Design Patterns

We have two ways to do this: one is putting the user story on Fred and see which concepts are in Framester:

Example
User story: Voters tend to favor incumbent candidates over new contenders, even if the incumbent's performance has been unsatisfactory, due to a perceived sense of stability and fear of the unknown.
Result with Fred:
<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#%27sPerformance>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Performance> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tend>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/Likelihood> , <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-tend-verb-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_143_148_sense>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "sense"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#sense_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Sense> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "143"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "148"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/TemporalCollocation> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-incumbent-adjectivesatellite-3> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Performance>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#Activity> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_communication> , <https://w3id.org/framester/data/framestercore/PerformingArts> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-performance-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_152_161_stability>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "stability"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#stability_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Stability> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "152"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "161"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Contender>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse>
        a       <http://www.essepuntato.it/2008/12/earmark#StringDocuverse> ;
        <http://www.essepuntato.it/2008/12/earmark#hasContent>
                "Voters tend to favor incumbent candidates over new contenders, even if the incumbent's performance has been unsatisfactory, due to a perceived sense of stability and fear of the unknown."^^<http://www.w3.org/2001/XMLSchema#string> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_133_142_perceived>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "perceived"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#perceive_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perceive> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "133"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "142"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VBN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unknown>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#Location> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_location> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-unknown-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Favor>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/Preference> , <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> , <https://w3id.org/framester/data/framestercore/Partiality> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-prefer-verb-3> , <http://www.ontologydesignpatterns.org/ont/vn/data/Favor_31020000> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Sense>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#CognitiveEntity> , <https://w3id.org/framester/data/framestercore/PerceptionExperience> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_cognition> , <https://w3id.org/framester/data/framestercore/Awareness> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-sense-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_124_127_due>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "due"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "124"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "127"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_87_98_performance>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "performance"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#performance_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Performance> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "87"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "98"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_178_185_unknown>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "unknown"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#unknown_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unknown> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "178"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "185"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_149_151_of>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "of"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Of> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "149"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "151"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-unknown-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "an unknown and unexplored region; \"they came like angels out the unknown\""@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_63_67_even>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "even"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "63"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "67"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#RB> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_84_86_%27s>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "'s"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#%27s> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "84"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "86"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#POS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_47_50_new>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "new"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#New> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "47"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "50"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_31_41_candidates>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "candidates"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#candidate_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Candidate> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "31"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "41"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_166_170_fear>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "fear"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#fear_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Fear> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "166"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "170"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#favor_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Favor> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#over>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#contender_1> ;
        <http://www.ontologydesignpatterns.org/ont/vn/abox/role/Experiencer>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#voter_1> ;
        <http://www.ontologydesignpatterns.org/ont/vn/abox/role/Theme>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#candidate_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perceive>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/BecomingAware> , <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#Event> , <https://w3id.org/framester/data/framestercore/Categorization> , <https://w3id.org/framester/data/framestercore/PerceptionExperience> , <https://w3id.org/framester/data/framestercore/Perception> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#v> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.ontologydesignpatterns.org/ont/vn/data/Perceive_30020000> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#entails>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#performance_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent%27sPerformance> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#%27s> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unsatisfactory> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#the> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_118_120_to>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "to"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#To> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "118"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "120"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#TO> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#NewContender>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Contender> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_21_30_incumbent>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "incumbent"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "21"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "30"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Stability>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#Characteristic> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_attribute> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-stability-noun-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unsatisfactory>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-unsatisfactory-adjective-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_7_11_tend>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "tend"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#tend_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tend> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "7"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "11"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VBP> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_108_122_unsatisfactory>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "unsatisfactory"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unsatisfactory> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "108"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "122"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#JJ> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#situation_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Situation> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#involves>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#performance_1> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#to>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#sense_1> , <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#fear_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_51_61_contenders>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "contenders"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#contender_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Contender> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "51"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "61"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_75_84_incumbent>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "Incumbent"^^<http://www.w3.org/2001/XMLSchema#string> , "incumbent"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "75"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "84"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#candidate_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#IncumbentCandidate> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#IncumbentCandidate>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Candidate> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_171_173_of>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "of"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Of> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "171"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "173"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_0_6_Voters>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "Voters"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#voter_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Voter> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "0"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "6"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#NNS> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_68_70_if>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "if"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Entails> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "68"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "70"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#%27s>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> .

<http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#New>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <https://w3id.org/framester/data/framestercore/Familiarity> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-new-adjective-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Fear>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/d0.owl#CognitiveEntity> , <https://w3id.org/framester/data/framestercore/Fear> , <http://www.w3.org/2006/03/wn/wn30/instances/supersense-noun_feeling> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-fear-noun-1> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#agent>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_42_46_over>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "over"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Over> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "42"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "46"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#IN> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#offset_15_20_favor>
        a       <http://www.essepuntato.it/2008/12/earmark#PointerRange> ;
        <http://www.w3.org/2000/01/rdf-schema#label>
                "favor"^^<http://www.w3.org/2001/XMLSchema#string> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#denotes>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#favor_1> ;
        <http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Favor> ;
        <http://www.essepuntato.it/2008/12/earmark#begins>
                "15"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#ends>
                "20"^^<http://www.w3.org/2001/XMLSchema#nonNegativeInteger> ;
        <http://www.essepuntato.it/2008/12/earmark#refersTo>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#docuverse> ;
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#VB> .

<http://www.ontologydesignpatterns.org/ont/fred/pos.owl#pennpos>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/vn/abox/role/Experiencer>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#perceive_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Perceive> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#entails>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#favor_1> ;
        <http://www.ontologydesignpatterns.org/ont/vn/abox/role/Stimulus>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#sense_1> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-performance-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "a dramatic or musical entertainment; \"they listened to ten different performances\"; \"the play ran for 100 performances\"; \"the frequent performances of the symphony testify to its popularity\""@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Due>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-due-adjective-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Even>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#a> ;
        <http://www.w3.org/2002/07/owl#equivalentClass>
                <http://www.w3.org/2006/03/wn/wn30/instances/synset-even-adjective-1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#sense_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Sense> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#senseOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#stability_1> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#a> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#contender_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#NewContender> ;
        <http://www.ontologydesignpatterns.org/ont/dul/DUL.owl#hasQuality>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#New> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.essepuntato.it/2008/12/earmark#refersTo>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.essepuntato.it/2008/12/earmark#ends>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Voter>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.essepuntato.it/2008/12/earmark#hasContent>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#fear_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Fear> ;
        <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#fearOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#unknown_1> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#unknown_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Unknown> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#the> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#voter_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Voter> ;
        <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
                <http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#multiple> .

<http://www.w3.org/2002/07/owl#equivalentClass>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasDeterminer>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#tend_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Tend> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#agent>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#voter_1> ;
        <http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#theme>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#favor_1> .

<http://www.essepuntato.it/2008/12/earmark#begins>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#stability_1>
        a       <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Stability> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-fear-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "an emotion experienced in anticipation of some specific pain or danger (usually accompanied by a desire to flee or fight)"@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#fearOf>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/vn/abox/role/Theme>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/boxer/boxer.owl#theme>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Incumbent%27sPerformance>
        <http://www.w3.org/2000/01/rdf-schema#subClassOf>
                <http://www.ontologydesignpatterns.org/ont/fred/domain.owl#%27sPerformance> .

<http://www.ontologydesignpatterns.org/ont/fred/quantifiers.owl#hasQuantifier>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://ontologydesignpatterns.org/cp/owl/semiotics.owl#hasInterpretant>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-stability-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "the quality or attribute of being firm and steadfast"@en-us .

<http://www.ontologydesignpatterns.org/ont/boxer/boxing.owl#involves>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2006/03/wn/wn30/instances/synset-sense-noun-1>
        <http://www.w3.org/2006/03/wn/wn30/schema/gloss>
                "a general conscious awareness; \"a sense of security\"; \"a sense of happiness\"; \"a sense of danger\"; \"a sense of self\""@en-us .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#Candidate>
        <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#boxerpos>
                <http://www.ontologydesignpatterns.org/ont/fred/pos.owl#n> .

<http://www.ontologydesignpatterns.org/ont/vn/abox/role/Stimulus>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#senseOf>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.w3.org/2000/01/rdf-schema#subClassOf>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#to>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

<http://www.ontologydesignpatterns.org/ont/fred/domain.owl#over>
        a       <http://www.w3.org/2002/07/owl#ObjectProperty> .

Second way is using the QUOKKA tool "Concepts Extractor" we search for Lexical Unit (words) that we highlighted during our exploration of the bias and we search for already existing frames from Framester.



### 4. Words as frame semantic triggers

### 5. Ontoly visualization with Protégé