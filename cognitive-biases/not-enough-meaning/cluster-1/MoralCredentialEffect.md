# Moral Credential Effect bias

## 1. Context and Literature State of the Art

**Wikipedia:**
The Moral credential effect, is a bias that occurs when a person's track record as a good egalitarian establishes in them an unconscious ethical certification, endorsement, or license that increases the likelihood of less egalitarian decisions later. This effect occurs even when the audience or moral peer group is unaware of the affected person's previously established moral credential. For example, individuals who had the opportunity to recruit a woman or Black person in one setting were more likely to say later, in a different setting, that a job would be better suited for a man or a white person. Similar effects also appear to occur when a person observes another person from a group they identify with making an egalitarian decision.
[Wikipedia Link](https://en.wikipedia.org/wiki/Self-licensing#:~:text=A%20large%20subset%20of%20this,of%20less%20egalitarian%20decisions%20later.)

**Reasearch paper:**
[Kouchaki, M. (2011). "Vicarious moral licensing: The influence of others' past moral actions on moral behavior". Journal of Personality and Social Psychology. 101 (4): 702–715.]
(https://psycnet.apa.org/doiLanding?doi=10.1037%2Fa0024552)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Moral credential effect"**

The "Moral Credential Effect" refers to a psychological bias where individuals, after performing a positive `moral` act or demonstrating a `commitment` to certain `values`, feel psychologically licensed or `justified` to subsequently engage in `behaviors` that might be considered morally questionable or `inconsistent` with those values. This bias can lead people to `perceive` themselves as less `prejudiced` or more `virtuous` than they actually are, allowing them to rationalize or `excuse` behaviors that might otherwise be seen as `contradictory`.
It's worth noting that the term "Moral Credential Effect" is often used in the context of social psychology and behavioral economics to explain how individuals navigate and rationalize their moral and `ethical` `decisions`.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Moral credential effect"**

Certainly, here are ten example scenarios that illustrate the "Moral Credential Effect":

1. **Charitable Donation**: A person donates a significant amount of money to a charitable organization and subsequently feels `justified` in making `insensitive` or `discriminatory` remarks about a particular group, believing their donation demonstrates their overall moral `character`.

2. **Environmental Activism**: An individual who actively participates in environmental conservation projects uses their past involvement as a reason to avoid practicing sustainable habits in their personal life, such as excessive use of single-use plastic.

3. **Hiring Decisions**: An employer hires a candidate from an underrepresented background and then makes subsequent hiring decisions that `discriminate` against other candidates from similar backgrounds, thinking that their previous diverse hire balances out any potential bias.

4. **Political Affiliation**: A politician advocates for progressive policies on one issue, but uses that stance to `justify` `regressive` or `prejudiced` views on a different issue, assuming that their previous support for a socially just cause `absolves` them of their biased opinions.

5. **Public Apologies**: A celebrity publicly apologizes for a past mistake or offensive comment, and then uses their apology as a shield to engage in further offensive `behavior`, believing that their `willingness` to apologize grants them moral `immunity`.

6. **Parenting**: A parent who volunteers at their child's school believes that their volunteer `efforts` make up for neglecting quality time with their child at home, justifying their `lack` of involvement in other aspects of their child's life.

7. **Corporate Social Responsibility**: A company promotes its philanthropic efforts, such as donating to charities, while simultaneously engaging in environmentally harmful practices, using their charitable actions as a moral credential to downplay their negative impact.

8. **Gender Equality**: An organization appoints a woman to a leadership position and then continues to maintain a predominantly male leadership team, citing the appointment of the female leader as evidence of their commitment to gender equality.

9. **Personal Relationships**: A person who supports LGBTQ+ rights uses this stance to excuse making derogatory comments about a colleague's appearance, believing that their open-minded views counterbalance their `insensitive` behavior.

10. **Academic Achievement**: A student who performs exceptionally well on one assignment or exam feels justified in subsequently plagiarizing or `cheating` on another assignment, considering their previous success as proof of their academic `integrity`.

These scenarios illustrate how individuals might use their past positive actions as a moral credential to rationalize or excuse subsequent behaviors that are inconsistent with their professed values.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Political Affiliation" and give me a small user story from it**

**User Story: Balancing Acts**

Alex, a politically engaged individual, had always been an advocate for social justice and equality. They had campaigned tirelessly for various progressive causes, from gender equality to climate action. Their commitment and activism had earned them a `reputation` as a dedicated champion of positive change.

One day, a contentious issue arose in the political landscape. A public debate was raging over a proposal to reform immigration policies. The proposal was receiving significant backlash due to its potential negative impact on immigrant communities. Alex found themselves torn on this issue. While they had previously championed inclusivity and compassion, they were now faced with a `conflicting` perspective.

Despite their reservations, Alex decided to support the immigration reform proposal, arguing that it was necessary for economic stability and national security. In conversations with friends who `questioned` their stance, Alex frequently referenced their past activism for other causes as a way to legitimize their position. They believed that their track record of fighting for justice should allow them the flexibility to take a stance that seemed `contradictory` to their usual `values`.

Over time, Alex noticed that they were using their history of activism as a sort of moral credential. They had begun to feel that their past actions gave them `permission` to `support` a policy that seemed to `contradict` their previously held beliefs. They realized that they were experiencing the moral credential effect, where their positive actions in one domain were `influencing` their behavior in another, allowing them to justify a stance that might otherwise be seen as inconsistent.

As Alex reflected on this `internal conflict`, they came to understand the complexity of moral `decision-making` and the subtle ways in which our past actions can influence our present `choices`. This realization motivated Alex to reevaluate their position, engage in deeper `introspection`, and strive for greater `consistency` in their political affiliations, irrespective of their past contributions to other causes.


***We can now derive CQs from the user story***

* CQ1: What strategies can be employed at an individual level to mitigate the influence of the moral credential effect and promote more consistent ethical decision-making over time?
* CQ2: How can organizations or institutions hold individuals accountable for their actions, discouraging the use of moral credentialing to excuse biased or contradictory behaviors?
* CQ3: What are the potential long-term consequences of repeatedly succumbing to the moral credential effect, both for individuals and for society at large? 
* CQ4: How might individuals actively work toward personal growth and consistency in their moral and ethical behaviors
---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Moral credential effect", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **MoralCredential:** Represents a positive moral action or behavior that an individual uses as a form of justification or validation for subsequent actions, even if those subsequent actions are contradictory or biased.
3. **ConfirmationBias:** The tendency to search for, interpret, and remember information in a way that confirms one's preexisting beliefs or values, potentially leading to the selection of moral actions that align with desired self-perceptions.
4. **SelectiveMoralMemory:** The bias that involves remembering and emphasizing past moral actions that support one's desired self-image while downplaying or forgetting instances of conflicting behavior influenced by the moral credential effect.
5. **ConsequentialDiscounting:** The bias where individuals assign less importance or significance to the negative consequences of biased behaviors when they believe their past moral actions compensate for or balance out those behaviors.
6. **NormativeInconsistency:** The cognitive dissonance that arises when an individual's actions diverge from their professed moral values, prompting them to rely on their moral credentials to rationalize or justify the inconsistency.
7. **AttributionShifting:** The bias involving the shifting of attribution for one's behavior from internal moral values to external factors or circumstances, allowing individuals to avoid personal responsibility for biased actions.

**Properties:**

1. **hasMoralCredential:** Relates an Agent to a MoralAction, indicating that the agent has engaged in a positive moral action.
2. **describesAction:** Relates a MoralCredential to a specific positive action that an individual has taken, explaining the source of the moral credential.
3. **justifiesBehavior:** Relates a MoralCredential to a BiasInstance, indicating that the individual is using the past positive action to justify or rationalize biased behavior.
4. **influencesBias:** Relates a MoralCredential to a BiasInstance, highlighting the influence of the moral credential on subsequent biased behavior.
5. **compartmentalizesValues:**  Relates an Agent to a Context, indicating that the agent tends to compartmentalize their moral values, leading to inconsistencies.
6. **attributesValueToAction:** Relates a MoralValue to a MoralAction, showing how a specific action reflects or embodies the moral value.
7. **comparesWithOthers:** Relates a BiasInstance to other BiasInstances, indicating instances where an individual compares their own behavior to that of others to justify their actions.
8. **realizesInconsistency:** Relates an Agent to a DelayedConscience instance, representing the point at which an individual realizes the inconsistency between their past actions and their current behavior.

These classes and properties will provide a solid foundation for modeling the system justification bias in various scenarios and contexts. The ontology can be expanded further with specific instances and relationships, enabling a comprehensive understanding of how the bias operates and influences decision-making processes.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Confirmation Bias and Biased Behavior Justification*

Agent: Emily
Moral Action: Volunteered at a homeless shelter
Context: Local community outreach event

Emily volunteered at a homeless shelter, contributing positively to her community. Later, when she made a biased comment about a different marginalized group, she used her past volunteering as a "moral credential" to justify her biased behavior. The ontology can represent this as follows:

Emily: hasMoralCredential -> Volunteering at homeless shelter
Emily: justifiesWithCredential -> Biased comment
Volunteering at homeless shelter: leadsToBehavior -> Biased comment

*Example 2: Selective Moral Memory and Comparative Ethics*

Agent: David
Moral Action: Donated to a disaster relief fund
Context: International humanitarian crisis

David had donated to a disaster relief fund, contributing to a worthy cause. However, he later made an insensitive comment about a different social issue. He justified his comment by comparing it to more extreme cases he had heard about, selectively recalling his donation as a moral credential to defend his biased behavior:

David: hasMoralCredential -> Donation to disaster relief
David: justifiesWithCredential -> Insensitive comment
Donation to disaster relief: leadsToBehavior -> Insensitive comment
Insensitive comment: comparesWithOthers -> Other extreme cases

*Example 3: Ethical Compartmentalization and Context Influence*

Agent: Sarah
Moral Action: Participated in an environmental clean-up event
Context: Local park restoration

Sarah participated in an environmental clean-up event, displaying her commitment to ecological preservation. However, in a separate context, she engaged in behavior that was environmentally harmful. She justified her behavior by compartmentalizing her values, considering her past participation in the clean-up event as a moral credential that allowed for inconsistent behavior:

Sarah: hasMoralCredential -> Environmental clean-up event
Sarah: justifiesWithCredential -> Environmentally harmful behavior
Environmental clean-up event: leadsToBehavior -> Environmentally harmful behavior
Sarah: compartmentalizesValues -> Environmental clean-up event

These examples illustrate how the classes and properties in the ontology can be used to model and understand instances of the "Moral Credential Effect" in various real-world scenarios