# Just-world hypothesis bias

## CLUSTER: We fill in characteristics from stereotypes, generalities, and prior histories

## 1. Context and Literature State of the Art

**Wikipedia:**
The just-world hypothesis or just-world fallacy is the cognitive bias that assumes that "people get what they deserve" – that actions will necessarily have morally fair and fitting consequences for the actor. For example, the assumptions that noble actions will eventually be rewarded and evil actions will eventually be punished fall under this hypothesis. In other words, the just-world hypothesis is the tendency to attribute consequences to—or expect consequences as the result of— either a universal force that restores moral balance or a universal connection between the nature of actions and their results. This belief generally implies the existence of cosmic justice, destiny, divine providence, desert, stability, order, or karma. It is often associated with a variety of fundamental fallacies, especially in regard to rationalizing suffering on the grounds that the sufferers "deserve" it
[Wikipedia Link](https://en.wikipedia.org/wiki/Just-world_hypothesis#cite_note-An_Overview-1)

**Reasearch paper:**
[Lerner, Melvin J.; Montada, Leo (1998). "An Overview: Advances in Belief in a Just World Theory and Methods". In Montada, L.; Lerner, M. J. (eds.). Responses to Victimizations and Belief in a Just World. Critical Issues in Social Justice. New York: Plenum. pp. 1–7.]
(https://link.springer.com/chapter/10.1007/978-1-4757-6418-5_1)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Just-world hypothesis"**

The "Just-world hypothesis" is a psychological and social cognitive bias that refers to the tendency of individuals to believe that the world is `inherently` fair and that people generally get what they `deserve`. According to this hypothesis, individuals tend to attribute outcomes, such as success or failure, to the inherent qualities and actions of individuals rather than acknowledging the influence of external factors or `random` chance. In other words, it suggests that people have a psychological need to believe that good actions are `rewarded` and bad actions are `punished`, which can lead to `victim-blaming` and a lack of empathy for those who experience unfortunate circumstances beyond their control. The concept of the just-world hypothesis has been widely studied in psychology and sociology to understand how people `perceive` and `interpret` the events around them.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Just-world hypothesis"**

Certainly, here are ten example scenarios that illustrate the "Moral Credential Effect":

1. **Unemployment:** A person loses their job due to company downsizing. Others might believe they must have done something wrong or lacked skills, rather than considering broader economic factors. 

2. **Health Issues:** A non-smoker develops lung cancer. People might assume they secretly smoked or engaged in some behavior that caused the illness, rather than considering genetic or environmental factors.

3. **Poverty:** Someone living in poverty is `assumed` to be lazy or unmotivated, `disregarding` the systemic inequalities and lack of opportunities they might face.

4. **Victim of a Crime:** If someone is a victim of a crime, others might `question` their actions or decisions that led to the situation, rather than `acknowledging` that crimes can happen `randomly`.

5. **Natural Disasters:** `Blaming` people for not preparing adequately for a natural disaster, without considering the `unpredictability` and severity of such events.
6. **Relationship Issues:** When a couple goes through a breakup, some might assume that one person must have been a bad partner, rather than recognizing the complexities of relationships.

7. **Bullying at School:** If a child is bullied at school, some might think they must have done something to provoke it, rather than addressing the behavior of the bully.

8. **Homelessness:** Assuming that all homeless individuals are responsible for their situation due to poor life choices, ignoring factors like mental illness, lack of social support, or economic downturns.

9. **Academic Success:** Believing that high-achieving students must always have a strong work ethic and intelligence, without considering other advantages they might have, such as access to resources or support.

10. **Injustice in Legal System:** Assuming that someone accused of a crime must be guilty, because the legal system is `perceived` as just and fair, even though wrongful convictions can occur.

In each of these scenarios, the just-world hypothesis can lead people to attribute outcomes primarily to individual actions or characteristics, overlooking the broader context and factors that contribute to those outcomes.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Victim of a Crime" and give me a small user story from it**

**User Story: Seeking Justice for a Stolen Bike**

As a concerned citizen, I observed a scenario that unfolded in my neighborhood, highlighting the `impact` of the just-world hypothesis. One sunny afternoon, I witnessed a young man named Alex becoming a victim of a crime. Alex was a diligent student who enjoyed riding his bike to school every day. He had earned his bike through months of hard work and saving up his allowance.

One day, as Alex was locking his bike outside the local library, a masked thief swiftly approached, forcibly grabbed the bike, and rode away. Shocked and distressed, Alex immediately reported the incident to the police and shared the security camera footage from the library's entrance.

In the aftermath, some members of the community `unintentionally` exhibited the just-world hypothesis in their reactions to the crime. Instead of `empathizing` with Alex's unfortunate situation, a few individuals `questioned` his actions. They wondered aloud why Alex hadn't used a stronger lock or chosen a more secure location to park his bike. They speculated that perhaps he had been careless or naive, `insinuating` that he could have prevented the theft if he had been more responsible.

However, as the investigation progressed, the security camera footage revealed that the thief had targeted Alex randomly and had been involved in a series of bike thefts in the area. It became evident that Alex's actions were not the `cause` of the crime; rather, he had been an unfortunate `victim` of a criminal's actions.

As the truth emerged, the community's `perspective` began to shift. People started to recognize that sometimes, bad things can happen to good individuals without any `fault` of their own. Empathy and support poured in for Alex, and the incident sparked conversations about crime prevention and neighborhood safety measures.

This user story highlights how the just-world hypothesis can initially `lead` people to question the victim's actions in a crime, but with a deeper `understanding` of the situation, `empathy` and a sense of `justice` prevailed. It also underscores the importance of considering the broader context and external factors when assessing such scenarios.


***We can now derive CQs from the user story***

* CQ1: What strategies can be employed to mitigate the negative impact of cognitive biases on decision-making processes, both at an individual level and within organizations?
* CQ2: How can individuals become more aware of their own biases and recognize when these biases might be influencing their thoughts, decisions, and interactions with others?
* CQ3: How do cultural and societal attitudes influences biases?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Just-world hypothesis", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **Just-WorldHypothesis:** The overarching concept representing the cognitive bias where individuals tend to believe that the world is inherently fair and that people generally get what they deserve.
3. **SocialImplications:** Explores the broader societal and interpersonal consequences of the just-world hypothesis, including victim-blaming, stigmatization, and empathy erosion.
4. **CognitiveMechanisms:**  Represents the underlying cognitive processes that contribute to the formation and reinforcement of the just-world hypothesis, such as cognitive dissonance, schema development, and heuristic thinking.
5. **CulturalVariations:** Examines how the just-world hypothesis manifests differently across cultures and societies, considering cultural norms, values, and belief systems.
6. **EthicalConsiderations:** Addresses the ethical dilemmas arising from the just-world hypothesis, including its role in social justice, discrimination, and the responsibility of institutions to address bias.

**Properties:**

1. **hasBeliefInJustice:** Relates an individual to their belief in the inherent fairness of the world.
2. **blameVictims:**  Indicates that a person or group attributes negative outcomes to the perceived actions or characteristics of the victims, rather than external factors.
3. **victimEmpathyReduction:** Describes the reduction in empathy toward individuals who experience unfortunate circumstances due to the belief in a just world.
4. **negativeOutcomeAttribution:** Connects a negative outcome to the assumed personal deficiencies or actions of an individual.
5. **positiveOutcomeAttribution:** Connects a positive outcome to the assumed personal qualities or actions of an individual.
6. **externalFactorsAwareness:** Reflects the extent to which an individual acknowledges and considers external factors influencing outcomes.
7. **contextualUnderstanding:** Represents an individual's ability to comprehend the broader context and systemic factors contributing to outcomes.
8. **beliefInMeritocracy:** Captures an individual's belief that success is directly tied to merit and effort.
9. **copingMechanisms:** Represents strategies individuals use to reconcile instances that challenge the just-world hypothesis, such as rationalization or denial.
10. **psychologicalDissonance:** Describes the discomfort experienced when encountering events that contradict the just-world hypothesis.

This ontology structure outlines specific classes and properties that characterize various aspects of the "Just-world hypothesis" bias, from belief patterns and attribution tendencies to external factors awareness and coping mechanisms. It provides a structured framework for analyzing and understanding the different dimensions of this cognitive bias.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Attribution Styles*

Class: Attribution Styles

Properties:

hasBeliefInJustice
blameVictims
negativeOutcomeAttribution
positiveOutcomeAttribution
Scenario: A group of researchers is conducting a study on attribution styles and the just-world hypothesis. They administer a series of hypothetical scenarios to participants and analyze their attributions for both positive and negative outcomes. Participants who strongly believe in a just world tend to attribute positive outcomes to personal qualities and negative outcomes to external factors or personal deficiencies. The researchers use this data to understand how the just-world hypothesis influences individuals' perceptions of causality.

*Example 2: Social Implications*

Class: Social Implications

Properties:

victimEmpathyReduction
stigmatization
mediaInfluence
ethicalConsiderations
Scenario: A team of social psychologists is investigating the social implications of the just-world hypothesis on crime victims. They analyze media coverage of criminal incidents and how it may contribute to victim-blaming and stigmatization. Through surveys and experiments, they also explore how belief in a just world affects public empathy toward victims and the ethical responsibilities of the media in shaping public opinion.

*Example 3: Interventions and Education*

Class: Interventions and Education

Properties:

copingMechanisms
counterexamplesAwareness
interventions
mediaInfluence
Scenario: A nonprofit organization focused on promoting empathy and reducing biases develops an educational program for schools. The program aims to teach students about cognitive biases, including the just-world hypothesis, and provides tools to recognize and challenge biased thinking. Students engage in discussions, case studies, and media analysis to better understand how biases can shape perceptions. The organization measures the program's effectiveness through pre- and post-program assessments of students' awareness of counterexamples and their ability to apply critical thinking to media messages.

These examples demonstrate how the classes and properties from the ontology can be applied in different contexts to study, analyze, and address various aspects of the "Just-world hypothesis" bias. The ontology provides a structured framework for organizing and understanding the complexity of this cognitive bias and its implications.