# Project documentation

In this documentation, we will outline all the phases that we will go through during the project of modeling two biases. The main goal is to create an ontology for semantic web technologies following the pattern-based ontology design method called 'eXtreme Design'.

# To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions

## Status quo bias

### 1. Context adn Literature State of the Art
To understand the context and to ensure that our ontology will be aligned with current understading and research in the field we provide a Wikipedia definition of the bias and a link to research papers about the topic.

**Wikipedia:**
Status quo bias is an emotional bias; a preference for the maintenance of one's current or previous state of affairs, or a preference to not undertake any action to change this current or previous state. The current baseline (or status quo) is taken as a reference point, and any change from that baseline is perceived as a loss or gain. Corresponding to different alternatives, this current baseline or default option is perceived and evaluated by individuals as a positive.[Link](https://en.wikipedia.org/wiki/Status_quo_bias)

**Reasearch paper:**
[Samuelson, W., Zeckhauser, R., 1988. Status quo bias in decision making. J. Risk Uncertain. 1, 7–59.](https://scholar.harvard.edu/files/rzeckhauser/files/status_quo_bias_in_decision_making.pdf)

### 2. Large Language Models (LLMs)
Powerful natural language processing models like ChatGPT-3.5 have the ability to generate human-like text. LLMs can assist in ontology development by providing suggestions, genereting ontological elements and aiding in the extraction of relevant information from textual sources.

*Let's ask ChatGPT for a generic definition, just to get an idea of the domain.*

**Give me a definition of "Status quo bias"**

Status quo bias refers to the tendency of individuals to prefer the current or existing state of affairs over potential changes or alternatives. It is a `cognitive bias` that influences `decision-making`, often leading to a `resistance or reluctance to make changes` even when they may be beneficial.

People with status quo bias tend to perceive the current situation as more comfortable, familiar, and less risky than potential alternatives. They may exhibit a preference for maintaining the current state, even when objectively better options are available. This bias can arise due to various factors, including fear of uncertainty, aversion to potential losses, and a desire to avoid the effort or disruption associated with change.

Status quo bias can impact various areas of life, including personal choices, organizational decision-making, public policy, and even societal norms. It can hinder progress, innovation, and adaptation to new circumstances. Recognizing and understanding status quo bias is important in order to make informed decisions and consider alternative possibilities that might lead to positive change.

*Let's ask to give us some examples of possible scenarios to better understand the context*

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

*Let's ask for some user story and competency questions*

**Consider the scenario "Social Norms" and give me a small user story from it**

User Story: Challenging Gender Stereotypes

As a socially conscious individual, I want to challenge gender `stereotypes` and promote equality in my community. I aim to break free from `traditional` social norms and make a positive impact by advocating for inclusivity and diversity.

By initiating conversations, supporting initiatives, educating myself, and encouraging open-mindedness, I will actively `challenge the existing` gender norms. I will engage with media critically, support marginalized voices, and actively participate in discussions promoting gender equality. I will reflect on my own behavior, avoiding perpetuating stereotypes, and fostering an environment of respect and understanding.

Ultimately, I seek to contribute to a more inclusive society by challenging and dismantling gender `stereotypes`, fostering equal opportunities, and promoting individual expression beyond societal expectations.

*Let's now ask about modeling this bias for an ontology*

**If you should make an ontology of the "Status quo bias", what classes and properties would you create?**

Classes:
1. StatusQuoBias: The main class representing the status quo bias itself.
2. DecisionMaker: Represents individuals or entities making decisions influenced by the status quo bias.
3. Alternative: Represents the potential options or alternatives that are being considered in a decision-making process.
4. Change: Represents the concept of making a change or deviating from the current state of affairs.

Properties:
1. hasStatusQuoBias: Indicates that a DecisionMaker is influenced by the status quo bias.
2. prefersStatusQuo: Indicates the preference of a DecisionMaker for the current state of affairs.
3. considersAlternative: Relates a DecisionMaker to an Alternative being considered.
4. resistsChange: Indicates the resistance or reluctance of a DecisionMaker to making changes.
5. evaluatesConsequences: Represents the evaluation of the consequences or potential outcomes associated with an Alternative.
6. overvaluesFamiliarity: Indicates the tendency of a DecisionMaker to place higher value on familiarity or the existing state.

**Let's ask for some example of usage of the ontology**

Example 1:
Instance: Jane (DecisionMaker)
Property: hasStatusQuoBias true

Explanation: The ontology captures that Jane is a decision-maker who exhibits the status quo bias. This information can be used to analyze Jane's decision-making processes and understand how the bias influences her preferences and choices.

Example 2:
Instance: John (DecisionMaker)
Property: prefersStatusQuo true

Explanation: The ontology indicates that John has a preference for the current state of affairs. This information can be utilized to assess the likelihood of John resisting change or being less receptive to alternative options due to his inclination towards the status quo.

Example 3:
Instance: Jane (DecisionMaker)
Property: considersAlternative "Option A"

Explanation: The ontology reflects that Jane is considering "Option A" as an alternative to the existing situation. This information can be used to analyze her decision-making process, evaluate the potential consequences of the alternative, and identify whether the status quo bias influences her assessment of the available options.

Example 4:
Instance: John (DecisionMaker)
Property: resistsChange true

Explanation: The ontology captures that John exhibits resistance or reluctance towards making changes. This information, in conjunction with other data, can help identify the influence of the status quo bias on John's decision-making behavior and explore strategies to mitigate its impact.

Example 5:
Instance: Jane (DecisionMaker)
Property: evaluatesConsequences "Option A" positive

Explanation: The ontology indicates that Jane evaluates the consequences of "Option A" positively. This information can be used to analyze her decision-making process, understand how the assessment of potential outcomes affects her biases, and identify the interplay between the status quo bias and the evaluation of alternative options.

These examples demonstrate how the ontology's classes and properties can be utilized to represent and reason about instances of decision-makers, their biases, preferences, consideration of alternatives, resistance to change, and evaluation of consequences. The ontology provides a structured framework for capturing and analyzing information related to the status quo bias in decision-making scenarios.