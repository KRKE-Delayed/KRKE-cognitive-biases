# Project documentation

In this documentation, we will outline all the phases that we will go through during the project of modeling two biases. The main goal is to create an ontology for semantic web technologies following the pattern-based ontology design method called 'eXtreme Design'.

# We fill in characteristics from stereotypes, generalities, and prior histories

## Ultimate attribution error

### 1. Context and Literature State of the Art
To understand the context and to ensure that our ontology will be aligned with current understading and research in the field we provide a Wikipedia definition of the bias and a link to research papers about the topic.

**Wikipedia:**
The ultimate attribution error is a type of attribution error which describes how attributions of outgroup behavior are more negative than ingroup behavior. As a cognitive bias, the error results in negative outgroup behavior being more likely to be attributed to factors internal and specific to the actor, such as personality, and the attribution of negative ingroup behavior to external factors such as luck or circumstance. The bias reinforces negative stereotypes and prejudice about the outgroup and favouritism of the ingroup through positive stereotypes. The theory also extends to the bias that positive acts performed by ingroup members are more likely a result of their personality.
[Wikipedia Link](https://en.wikipedia.org/wiki/Ultimate_attribution_error)

**Reasearch paper:**
[Stangor, Charles; Jhangiani, Rajiv; Tarry, Hammond (2022). Principles of Social Psychology (1st international H5P ed.)](https://opentextbc.ca/socialpsychology/chapter/ingroup-favoritism-and-prejudice/)

### 2. Large Language Models (LLMs)
Powerful natural language processing models like ChatGPT-3.5 have the ability to generate human-like text. LLMs can assist in ontology development by providing suggestions, genereting ontological elements and aiding in the extraction of relevant information from textual sources.

***Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Ultimate attribution error"**

The Ultimate Attribution Error, also known as Ultimate Attribution Fallacy, is a psychological concept that refers to a `cognitive bias` in which `individuals` tend to attribute the `behavior` of members of other groups (`out-groups`) to their inherent traits or characteristics, while `attributing` the behavior of members of their own `group` (`in-group`) to external factors or situational influences.

In other words, when someone from our own group does something negative, we are more likely to attribute it to `external circumstances` that influenced their behavior. However, when someone from a different group does something negative, we are more inclined to attribute it to their personality, character, or inherent `traits`.

This bias can contribute to `stereotypes`, `prejudice`, and `discrimination`, as it can perpetuate negative `perceptions` and generalizations about out-groups while fostering a more forgiving view of the actions of our own group. The Ultimate Attribution Error can have significant social and intergroup consequences, affecting how individuals `perceive` and `interact` with members of different social, cultural, or ethnic `backgrounds`.

***Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Ultimate attribution error"**

Certainly! Here are ten example scenarios of the Ultimate Attribution Error:

1. The Uncooperative Employee: A manager believes that an employee from another department is uncooperative and difficult to work with because they inherently have a bad attitude, but when an employee from their own department behaves similarly, they attribute it to the stressful workload and external pressures.

2. Aggression on the Field: A sports fan blames a player from the opposing team for being aggressive and violent on the field, citing their personality as the cause. However, when a player from their favorite team displays similar behavior, they explain it away as the result of intense competition and the passion for the game.

3. Academic Underperformance: In a school setting, a teacher believes that students from a certain ethnic background are academically underperforming due to their lack of intelligence or effort. At the same time, the teacher attributes any underperformance among students from their own `ethnic background` to external factors like `family issues` or socioeconomic challenges.

4. Late Project Submissions: In a workplace, an individual perceives that members of a specific team are consistently late with project submissions because they are lazy and unorganized. However, when their own team experiences delays, they attribute it to unexpected hurdles and increased workload.

5. Corruption in Politics: During a political debate, a person argues that politicians from an opposing party are corrupt and self-serving because of their `character traits`, while defending the actions of politicians from their own party by pointing to the complex nature of governance and the challenges they face.

6. Regional Rudeness: A person believes that people from a certain region are naturally rude and impolite, as they've had negative `interactions` with a few individuals from that region. However, when someone from their own region behaves rudely, they attribute it to a bad day or personal stressors.

7. Religious Intolerance: An individual perceives that members of a particular religious group are intolerant and `close-minded` based on isolated incidents. On the other hand, they see any `intolerance` exhibited by members of their own religious group as a result of `misunderstandings` or `misinterpretations`.

8. Cultural Perceptions: In an international context, a person from one country generalizes that people from another country are lazy and unambitious, attributing this perceived trait to their `culture`. However, when people from their own country display similar behaviors, they attribute it to economic challenges and societal pressure.

9. Academic Struggles: A parent believes that their child's classmates are performing poorly in school because they are naturally unintelligent, but when their own child struggles academically, they blame it on ineffective teaching or distractions in the classroom.

10. Socioeconomic Bias: In a neighborhood, a resident perceives that members of a different `socioeconomic class` engage in criminal activities because they are inherently immoral. Conversely, they explain any criminal behavior exhibited by individuals within their own socioeconomic group as a result of difficult life circumstances or desperation.

These scenarios illustrate how the Ultimate Attribution Error can influence individuals' perceptions and judgments about others based on group membership, leading to biased attributions and potential reinforcement of stereotypes.

***Let's ask for some user story and competency questions***

**Consider the scenario "Religious Intolerance" and give me a small user story from it**

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