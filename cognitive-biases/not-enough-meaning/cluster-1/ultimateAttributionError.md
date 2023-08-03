# UltimateAttributionErrorBias

## 1. Context and Literature State of the Art
To understand the context and to ensure that our ontology will be aligned with current understading and research in the field we provide a Wikipedia definition of the bias and a link to research papers about the topic.

**Wikipedia:**
The ultimate attribution error is a type of attribution error which describes how attributions of outgroup behavior are more negative than ingroup behavior. As a cognitive bias, the error results in negative outgroup behavior being more likely to be attributed to factors internal and specific to the actor, such as personality, and the attribution of negative ingroup behavior to external factors such as luck or circumstance. The bias reinforces negative stereotypes and prejudice about the outgroup and favouritism of the ingroup through positive stereotypes. The theory also extends to the bias that positive acts performed by ingroup members are more likely a result of their personality.
[Wikipedia Link](https://en.wikipedia.org/wiki/Ultimate_attribution_error)

**Reasearch paper:**
[Stangor, Charles; Jhangiani, Rajiv; Tarry, Hammond (2022). Principles of Social Psychology (1st international H5P ed.)](https://opentextbc.ca/socialpsychology/chapter/ingroup-favoritism-and-prejudice/)

## 2. Large Language Models (LLMs)
Powerful natural language processing models like ChatGPT-3.5 have the ability to generate human-like text. LLMs can assist in ontology development by providing suggestions, genereting ontological elements and aiding in the extraction of relevant information from textual sources.

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Ultimate attribution error bias"**

The Ultimate Attribution Error, also known as Ultimate Attribution Fallacy, is a psychological concept that refers to a `cognitive bias` in which `individuals` tend to attribute the `behavior` of members of other groups (`out-groups`) to their inherent traits or characteristics, while `attributing` the behavior of members of their own `group` (`in-group`) to external factors or situational influences.

In other words, when someone from our own group does something negative, we are more likely to attribute it to `external circumstances` that influenced their behavior. However, when someone from a different group does something negative, we are more inclined to attribute it to their personality, character, or inherent `traits`.

This bias can contribute to `stereotypes`, `prejudice`, and `discrimination`, as it can perpetuate negative `perceptions` and generalizations about out-groups while fostering a more forgiving view of the actions of our own group. The Ultimate Attribution Error can have significant social and intergroup consequences, affecting how individuals `perceive` and `interact` with members of different social, cultural, or ethnic `backgrounds`.

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Ultimate attribution error"**

Certainly, here are 10 examples of scenarios that illustrate the ultimate attribution error:

1. **Sports Rivalry**: A fan of Team A believes that their team's victory is due to their players' exceptional skills and teamwork (`internal attribution`), while attributing Team B's loss to their lack of effort or incompetence (internal attribution). However, if Team A loses, the fan might attribute it to bad luck or unfavorable circumstances (`external attribution`).

2. **Workplace Dynamics**: An employee from Department X believes that the successful completion of a project was due to their team's hard work and intelligence (internal attribution), while attributing any failures to Department Y as a lack of coordination or commitment (internal attribution).

3. **Academic Performance**: A student from School A who performs well on a test credits their success to their dedication and study habits (internal attribution), but if a student from School B performs poorly, the first student may attribute it to the exam being difficult or unfair (external attribution).

4. **Ethnic or Cultural Bias**: A person belonging to Ethnic Group A believes that members of their `group` excel academically due to their `inherent` intelligence (internal attribution), while attributing any academic struggles of Ethnic Group B to their lack of intellectual ability (internal attribution).

5. **Political Affiliation**: A supporter of Party X views positive actions taken by their party as a result of their leaders' competence and good intentions (internal attribution), while attributing negative actions by Party Y to their leaders' corrupt motives or lack of understanding (internal attribution).

6. **Interpersonal Relationships**: Someone in a close-knit `social circle` may attribute a friend's success to their personal `qualities` (internal attribution), while attributing a friend's `mistakes` or failures to external factors like stress or unfortunate `events` (external attribution).

7. **Religious Beliefs**: A follower of Religion A may view their `community`'s charitable deeds as a sign of their moral superiority (internal attribution), while attributing negative actions by members of Religion B to flaws within that religion's doctrine (internal attribution).

8. **Gender Stereotypes**: An individual might believe that their own `gender` tends to excel in leadership roles due to their innate qualities (internal attribution), while `attributing` the underrepresentation of the opposite gender in such roles to their supposed `lack` of leadership `skills` (internal attribution).

9. **National Pride**: Citizens of Country A may attribute their nation's economic `success` to their collective work ethic and ingenuity (internal attribution), while explaining any economic troubles in Country B as a result of their citizens' laziness or mismanagement (internal attribution).

10. **Generational Differences**: An older `generation` might attribute their accomplishments to hard work and discipline (internal attribution), while attributing younger generations' struggles to laziness and a lack of `values` (internal attribution).

These scenarios demonstrate how the ultimate attribution error can lead individuals to assign different causes to the actions and outcomes of their own group compared to other groups, often reflecting positively on their in-group and negatively on out-groups.

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Interpersonal Relationships" and give me a small user story from it**

User Story: Enhancing Interpersonal Understanding

As a product designer, I want to create a mobile app that helps individuals gain insights into their `interpersonal dynamics`, promoting `empathy` and reducing the impact of the `ultimate attribution error`.

Acceptance Criteria:

As a user, I should be able to create a profile and answer a set of questions about my relationships, focusing on both `in-group` and `out-group` `interactions`. The app should use a data-driven algorithm to analyze the user's responses and identify instances of ultimate attribution error in their thinking. The app will provide personalized feedback to the user, highlighting specific scenarios where they might be prone to making attribution errors.
Users will receive actionable tips and suggestions on how to approach situations with more balanced attributions, fostering better understanding and empathy. The app will offer interactive scenarios and role-playing exercises that simulate real-life interpersonal interactions, helping users practice avoiding attribution errors.
Users can track their progress over time, observing changes in their thought patterns and behaviors related to attribution. The app's interface should be user-friendly, visually appealing, and accessible to a diverse range of users. User data and responses will be kept strictly confidential and anonymized for research purposes, with the option for users to opt out of data collection. The app should have a support section with additional resources on interpersonal communication, cognitive biases, and strategies for improving relationships.

Stretch Goals:

Integration with social media platforms to share progress and insights with friends and family, fostering a culture of `awareness`. Collaborations with psychologists and relationship experts to enhance the app's effectiveness and credibility. Localization and customization options to tailor the app's content to different cultural contexts and relationship dynamics. Regular updates and improvements based on user feedback and emerging research in psychology and cognitive biases.  By creating this app, users will have a practical tool to identify and address the ultimate attribution error in their interpersonal relationships. This will contribute to healthier interactions, reduced misunderstandings, and improved empathy between individuals of different social groups.

***We can now derive CQs from the user story***

Following the XD procedure, we now need to analyze CQs in terms of classes and properties restrictions in order to be able to answer our questions. The goal is to use the CQs to divide a complex situation into already existing frames.

* CQ1: What are the factors through which it is possible to identify this cognitive bias?
* CQ2: What are the behaviors that can solve these prejudices?
* CQ3: What social contexts are fertile ground for finding these behaviors?

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Ultimate attribution error", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias**: Represents various types of biases, including the status quo bias. This class serves as a superclass for specific types of biases, such as GenderBias, ConfirmationBias, or AvailabilityBias.
2. **UltimateAttributionError**: Represents the cognitive bias itself.
3. **AttributionFactors**: Represents the factors that influence attributions made by individuals, such as internal traits, external circumstances, and cultural influences.
4. **AttributionType**: Represents the type of attribution made in different situations, such as internal attribution (positive actions of in-group) and external attribution (negative actions of out-group).
5. **SocialGroups**: Represents the different social, cultural, or ethnic groups involved in the attribution process, including in-groups and out-groups
6. **Behavior**: Describes the actions, responses, or decision-making influenced by the UltimateAttributionErrorBias.
7. **Impact**: Represents the effects or consequences of the UltimateAttributionErrorBias on individuals, groups, or situations.
8. **PositiveBehavior**: Represents positive actions, achievements, or outcomes exhibited by individuals or groups.
9. **NegativeBehavior**: Represents negative actions, failures, or mistakes exhibited by individuals or groups.
10. **Stereotype**: Represents a generalization or belief about a group that may or may not be accurate.
11. **Prejudice**: Represents a biased attitude or judgment towards a group or its members.

**Properties:**

1. **hasAttributionType**: Relates a cognitive bias instance to the type of attribution made (internal or external).
2. **hasAttributionFactors**: Relates an attribution to the factors that influenced it, such as internal traits or external circumstances.
3. **involvesSocialGroup**: Relates an attribution to the social group to which the attributed individual or group belongs.
4. **exhibitsPositiveBehavior**: Relates a social group or individual to positive actions or successes.
5. **exhibitsNegativeBehavior**: Relates a social group or individual to negative actions or failures..
6. **isInGroup**: Relates an individual or social group to an in-group.
7. **isOutGroup**: Relates an individual or social group to an out-group.
8. **hasExampleScenario**: Relates the cognitive bias to real-world scenarios illustrating the ultimate attribution error.
9. **hasCulturalContext**: Relates the cognitive bias to its manifestation in different cultural contexts.
10. **isLinkedToOtherBiases**: Relates the cognitive bias to other related cognitive biases that may interact or influence each other.

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

Certainly! Here are three examples of how the classes and properties from the ontology of the Ultimate Attribution Error could be used:

*Example 1: Attribution in Sports Commentary*

Scenario: A sports commentator is analyzing a recent soccer match between two teams, Team A and Team B.

Attribution Type: The commentator discusses how fans of Team A tend to attribute their team's victory to internal factors like skill and teamwork (internal attribution), while attributing Team B's loss to factors such as lack of effort or individual player mistakes (internal attribution).

Attribution Factors: The commentator highlights that fans of Team A often emphasize the strong bond between their players and their consistent practice regimen as reasons for their success, whereas they emphasize external factors like injuries or referee decisions to explain Team B's loss.

Positive Behavior and Social Groups: The commentator mentions that fans of Team A celebrate the goals scored by their team by attributing them to their players' exceptional skills (positive behavior exhibited by in-group). However, when Team B scores a goal, fans of Team A might attribute it to luck or a defensive error on the part of Team B (negative behavior attributed to out-group).

*Example 2: Workplace Dynamics*

Scenario: A manager is reviewing performance evaluations for two departments, Department X and Department Y.

Attribution Type: The manager notices that when Department X achieves its targets, employees attribute their success to their collective effort and effective communication (internal attribution), while attributing Department Y's missed targets to their lack of dedication or focus (internal attribution).

Attribution Factors: The manager observes that Department X employees point to their strong team dynamics and collaborative problem-solving as reasons for their success, whereas they tend to attribute Department Y's failures to a lack of motivation or insufficient preparation.

Positive and Negative Behavior: The manager acknowledges that Department X's achievements are often praised by its members as a result of their skills (positive behavior exhibited by in-group). In contrast, when Department Y faces challenges, employees from Department X might attribute it to their supposed lack of expertise or ineffective decision-making (negative behavior attributed to out-group).

*Example 3: Cross-Cultural Comparison*

Scenario: Researchers are studying cross-cultural differences in attributions for academic achievements.

Attribution Type and Cultural Context: The researchers find that in Culture A, students attribute their academic success to their personal effort and effective study strategies (internal attribution), while attributing failures to external factors like difficult exams (external attribution). In Culture B, students attribute success to external luck or support (external attribution), and failures to personal shortcomings (internal attribution).

Attribution Factors: The researchers identify that in Culture A, students emphasize their diligence and dedication as factors contributing to their success, while in Culture B, students often highlight family support and blessings from external forces.

Positive and Negative Behavior: In Culture A, students congratulate each other for good grades, attributing them to hard work (positive behavior exhibited by in-group). However, when students from Culture B struggle, they might be met with comments suggesting they didn't try hard enough (negative behavior attributed to out-group).

These examples demonstrate how the ontology's classes and properties can be used to analyze and explain instances of the Ultimate Attribution Error in different contexts, such as sports commentary, workplace evaluations, and cross-cultural comparisons of academic achievements.

### 3. Ontology Design Patterns

### 4. Words as frame semantic triggers

### 5. Ontoly visualization with Protégé