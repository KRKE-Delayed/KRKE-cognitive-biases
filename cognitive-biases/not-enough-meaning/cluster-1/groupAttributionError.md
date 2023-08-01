# Project documentation

In this documentation, we will outline all the phases that we will go through during the project of modeling two biases. The main goal is to create an ontology for semantic web technologies following the pattern-based ontology design method called 'eXtreme Design'.

# We fill in characteristics from stereotypes, generalities, and prior histories

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

Group attribution error, also known as group-serving bias or collective attribution error, refers to a `cognitive bias` in which individuals tend to attribute positive outcomes and successes of their group to internal factors such as talent, intelligence, or teamwork, while attributing negative outcomes or failures to external factors beyond their control. This bias often leads members of a group `to perceive` their collective as more favorable and competent `compared` to other groups.

The concept of group attribution error is closely related to the fundamental attribution error, which occurs at the individual level. The fundamental attribution error refers to the tendency to overemphasize dispositional (internal) factors and underestimate situational (external) factors when explaining the behavior of others.

In the context of group attribution error, people tend to `overemphasize` the positive qualities of their own group members and downplay their shortcomings, while simultaneously magnifying the negative qualities of other groups and attributing their failures to inherent flaws. This bias can lead to `intergroup` conflicts, `stereotypes`, and `prejudice`, as well as hinder objective analysis and `decision-making`.

Recognizing and understanding group attribution error can be essential in promoting `empathy`, reducing prejudice, and fostering better intergroup relations. It requires individuals to be more aware of their biases and to approach intergroup interactions with a more balanced and open-minded perspective.

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

As the conversation progressed, we realized that cultural misunderstandings can easily lead to misconceptions. We realized that our `preconceived notions` were unfounded, and we were actually quite similar in many ways.

This demonstrates how cultural understanding and `empathy` can break down `barriers` and foster meaningful connections among people from different backgrounds, learning the importance of addressing cultural misunderstandings proactively, embracing her identity while also recognizing the uniqueness of others.

To overcoming group attribution error is possible through genuine `communication` and `open-mindedness`, ultimately creating a more `inclusive` and harmonious environment.

*We can now derive CQs from the user story*

Following the XD procedure, we now need to analyze CQs in terms of classes and properties restrictions in order to be able to answer our questions. The goal is to use the CQs to divide a complex situation into already existing frames.

* CQ1: What are the awareness and prospects that allow to change preconceived notions in a social environment?
* CQ2: How stereotypical beliefs affect relational ties?
* CQ3: What beliefs create barriers between people from different group or contexts ?

***Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Group attribution error", what classes and properties would you create?**

*Classes:*
1. CognitiveBias: Represents various types of biases, including the status quo bias. This class serves as a superclass for specific types of biases, such as GenderBias, ConfirmationBias, or AvailabilityBias.
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

### 4. Words as frame semantic triggers

### 5. Ontoly visualization with Protégé