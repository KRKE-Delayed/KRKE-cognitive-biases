# Project documentation

In this documentation, we will outline all the phases that we will go through during the project of modeling two biases. The main goal is to create an ontology for semantic web technologies following the pattern-based ontology design method called 'eXtreme Design'.

# To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions

## Group attribution error

### 1. Context and Literature State of the Art
To understand the context and to ensure that our ontology will be aligned with current understading and research in the field we provide a Wikipedia definition of the bias and a link to research papers about the topic.

**Wikipedia:**
The group attribution error refers to people's tendency to believe either

  1. the characteristics of an individual group member are reflective of the group as a whole, or
  2. a group's decision outcome must reflect the preferences of individual group members, even when external information is available suggesting otherwise. [Wikipedia Link](https://en.wikipedia.org/wiki/Group_attribution_error)

**Reasearch paper:**
[Allison, Scott T; Messick, David M (1985). "The group attribution error". Journal of Experimental Social Psychology. 21 (6): 563–579.](https://www.sciencedirect.com/science/article/abs/pii/0022103185900253?via%3Dihub)

### 2. Large Language Models (LLMs)
Powerful natural language processing models like ChatGPT-3.5 have the ability to generate human-like text. LLMs can assist in ontology development by providing suggestions, genereting ontological elements and aiding in the extraction of relevant information from textual sources.

***Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Group attribution error"**

Group attribution error, also known as group-serving bias or collective attribution error, refers to a `cognitive bias` in which individuals tend to attribute positive outcomes and successes of their group to internal factors such as talent, intelligence, or teamwork, while attributing negative outcomes or failures to external factors beyond their control. This bias often leads members of a group `to perceive` their collective as more favorable and competent `compared to other groups`.

The concept of group attribution error is closely related to the fundamental attribution error, which occurs at the individual level. The fundamental attribution error refers to the tendency to overemphasize dispositional (internal) factors and underestimate situational (external) factors when explaining the behavior of others.

In the context of group attribution error, people tend to `overemphasize the positive qualities of their own group members` and downplay their shortcomings, while simultaneously `magnifying the negative qualities of other groups` and attributing their failures to inherent flaws. This bias can lead to intergroup conflicts, stereotypes, and prejudice, as well as hinder objective analysis and decision-making.

Recognizing and understanding group attribution error can be essential in promoting `empathy, reducing prejudice, and fostering better intergroup relations`. It requires individuals to be more aware of their biases and to approach intergroup interactions with a more balanced and open-minded perspective.

***Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Group attribution error"**

Certainly! Here are ten example scenarios of group attribution error:

1. Workplace Stereotyping: An employee assumes that all members of a certain department in their company are lazy and unproductive based on a few negative `experiences` with a couple of individuals from that department.

2. Ethnic Generalization: A person believes that all individuals from a particular `ethnicity` are inherently good at math and science, assuming that intelligence is uniformly distributed within that group.

3. Sports Fan Rivalry: Fans of one sports team often `stereotype` the fans of a rival team, assuming they are all aggressive and unruly, `disregarding` the fact that both groups include diverse `individuals`.

4. Political Group Bias: A person from one political party `perceives` members of the opposing party as all being close-minded and ignorant, while they believe that everyone within their own party is open-minded and well-informed.

5. Religious Stereotyping: An individual assumes that all followers of a certain religion are conservative and intolerant, disregarding the diverse beliefs and practices within that religious group.

6. Nationality Prejudice: People may stereotype individuals from a particular country as being rude or arrogant based on a `negative` encounter with a few individuals, `ignoring` the fact that cultural attitudes can vary widely within a nation.

7. Academic Major Bias: A student from one academic major may believe that students from another major are all nerdy and socially awkward, failing to recognize the `variety` of `personalities` within each major.

8. Age Group Generalization: Older adults might assume that all teenagers are lazy and uninterested in important issues, while teenagers may stereotype older adults as being out of touch and technologically illiterate.

9. Economic Class Perception: Individuals from different economic `classes` may stereotype each other, with some assuming that wealthy people are all snobbish and out of touch, while others assume that people from lower-income backgrounds are all lazy and unmotivated.

10. Cultural Misunderstanding: A tourist visiting a `foreign` country may mistakenly believe that all locals share the same customs and `values`, leading to `misunderstandings` and potential `offense` due to cultural `differences`.

These scenarios illustrate how group attribution error can occur across various contexts and can lead to harmful assumptions and prejudices about different social groups. Overcoming this bias requires awareness, empathy, and a willingness to recognize and appreciate the diversity and individuality present in all groups.


***Let's ask for some user story and competency questions***

**Consider the scenario "Cultural Misunderstanding" and give me a small user story from it**

User Story: Bridging Cultural Misunderstanding

As an international student, I arrived in a foreign country to pursue my higher education. Being from a Middle Eastern background, I carried with me the customs and traditions that were deeply ingrained in my `upbringing`. However, I quickly realized that my new environment was quite different from what I was accustomed to.

While attending a class, a fellow student approached me to start a conversation and he seemed hesitant and distant. I attributed this behavior to the assumption that he might have `stereotypical beliefs` about people from my region. However, instead of letting this `misunderstanding` persist, I decided to take the initiative `to bridge the gap` sharing some information about my home country, its rich cultural heritage, and the warm hospitality we offer to guests.

As the conversation progressed, we realized that cultural misunderstandings can easily lead to misconceptions. We realized that our `preconceived notions were unfounded`, and we were actually quite similar in many ways.

This demonstrates how cultural understanding and `empathy` can break down `barriers` and foster meaningful connections among people from different backgrounds, learning the importance of addressing cultural misunderstandings proactively, embracing her identity while also recognizing the uniqueness of others.

To overcoming group attribution error is possible through `genuine communication` and `open-mindedness`, ultimately creating a more `inclusive and harmonious environment`.

*We can now derive CQs from the user story*

Following the XD procedure, we now need to analyze CQs in terms of classes and properties restrictions in order to be able to answer our questions. The goal is to use the CQs to divide a complex situation into already existing frames.

* CQ1: What are the awareness and prospects that allow to change preconceived notions in a social environment?
* CQ2: How stereotypical beliefs affect relational ties?
* CQ3: What beliefs create barriers between people from different group or contexts ?

***Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Group attribution error", what classes and properties would you create?**

*Classes:*
1. CongnitiveBias: Represents various types of biases, including the status quo bias. This class serves as a superclass for specific types of biases, such as GenderBias, ConfirmationBias, or AvailabilityBias.
2. GroupAttributionErrorBias: Represents the specific type of bias known as the GroupAttributionErrorBias
3. Group: Represents a social, cultural, demographic, or any other type of group.
4. Context: Describes the specific situations, contexts, or scenarios in which the GroupAttributionErrorBias is observed or relevant.
5. SocialGroup: Represents a group of individuals who share common social or cultural characteristics.
6. Behavior: Describes the actions, responses, or decision-making influenced by the GroupAttributionErrorBias.
7. Impact: Represents the effects or consequences of the GroupAttributionErrorBias on individuals, groups, or situations.
8. MitigationStrategy: Describes the strategies or approaches suggested to mitigate the negative effects of the GroupAttributionErrorBias.
9. RecognitionStrategy: Represents the methods or approaches used by individuals to recognize and identify the GroupAttributionErrorBias.
10. Stereotype: Represents a generalization or belief about a group that may or may not be accurate.
11. Prejudice: Represents a biased attitude or judgment towards a group or its members.

*Properties:*
1. hasTrait: Relates a person to a specific trait, capturing individual attributes.
2. belongsToGroup: Relates a person to a group, defining ingroup-outgroup distinctions.
3. influencesBehavior: Represents the impact of the bias on behavior, decision-making, or perceptions.
4. hasImpact: Represents the impact of the bias observed or experienced by the Observer.
5. relatesToInGroup: Indicates the connection of the bias to the In-Group of the Observer.
6. occursInContext: Indicates the specific context or situation in which the GroupAttributionErrorBias was observed or relevant.
7. holdsStereotype: Relates a group to a stereotype, specifying beliefs attributed to the group.
8. exhibitsPrejudice: Relates a person to a prejudice, representing biased attitudes towards a group.

**Let's ask for some example of usage of the ontology**


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