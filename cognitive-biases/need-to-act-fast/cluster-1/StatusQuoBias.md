# Status quo bias

## CLUSTER: To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions

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

## 3. Words as Frame Semantic Triggers

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

**- tradition**
**- costum**
**- preserve**
**- norm**
**- current**

We cross our results with the ones obtained in FRED by putting the following scenario:

10. **Social Norms:** Society may `resist` changes in social norms, such as gender roles or cultural `traditions`, due to a `preference` for preserving existing customs, even if those norms perpetuate inequality or outdated beliefs.

By doing these two steps, we selected the following **frames**:

**- Cogitation**
**- Custom**
**- Preserving**
**- Choosing**