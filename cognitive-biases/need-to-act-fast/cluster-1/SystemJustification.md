# System Justification

## 1. Context and Literature State of the Art

**Wikipedia:**
System justification theory (SJT) is a theory within social psychology that system-justifying beliefs serve a psychologically palliative function. It proposes that people have several underlying needs, which vary from individual to individual, that can be satisfied by the defense and justification of the status quo, even when the system may be disadvantageous to certain people. People have epistemic, existential, and relational needs that are met by and manifest as ideological support for the prevailing structure of social, economic, and political norms. Need for order and stability, and thus resistance to change or alternatives, for example, can be a motivator for individuals to see the status quo as good, legitimate, and even desirable.

According to system justification theory, people desire not only to hold favorable attitudes about themselves (ego-justification) and the groups to which they belong (group-justification), but also to hold positive attitudes about the overarching social structure in which they are entwined and find themselves obligated to (system-justification). This system-justifying motive sometimes produces the phenomenon known as out-group favoritism, an acceptance of inferiority among low-status groups and a positive image of relatively higher status groups. Thus, the notion that individuals are simultaneously supporters and victims of the system-instilled norms is a central idea in system justification theory. Additionally, the passive ease of supporting the current structure, when compared to the potential price (material, social, psychological) of acting out against the status quo, leads to a shared environment in which the existing social, economic, and political arrangements tend to be preferred. Alternatives to the status quo tend to be disparaged, and inequality tends to perpetuate. [Wikipedia Link](https://en.wikipedia.org/wiki/System_justification)

**Reasearch paper:**
[Jost, John & Toorn, Jojanneke. (2012). System justification theory. 10.4135/9781446249222.n42.](https://www.researchgate.net/publication/293346215_System_justification_theory)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "System justification"**

System justification bias is a cognitive bias that leads individuals to defend and rationalize the status quo or existing social, economic, and political systems, even if they may be unjust or unfair. It involves the tendency to justify and support the prevailing order, often by accepting and internalizing ideologies that promote inequality or disadvantage certain groups.

Individuals exhibiting system justification bias may downplay or dismiss evidence of systemic flaws, inequality, or discrimination, believing that the current system is legitimate and should be maintained. This bias can play a role in shaping attitudes, behaviors, and decision-making, contributing to the perpetuation of existing social structures and inequalities.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "System justification"**

1. **Gender Wage Gap:** Despite evidence of a gender wage gap in a company, some employees may justify the pay disparity by attributing it to perceived differences in skills or experience between genders, rather than acknowledging potential biases in the hiring and promotion processes.

2. **Racial Discrimination:** In a society with a history of racial discrimination, individuals may justify the existing racial disparities by believing that certain racial groups are naturally inferior or that historical events are not relevant to the present situation.

3. **Income Inequality:** Some individuals may rationalize income inequality as a result of personal choices and merit, ignoring the influence of systemic barriers and lack of equal opportunities for economic advancement.

4. **Political Party Loyalty:** Individuals may staunchly support and defend the policies of their preferred political party, even in the face of evidence showing negative consequences, due to their loyalty and identification with the party.

5. **Corporate Accountability:** Despite evidence of unethical practices by a company, some stakeholders may justify the company's actions, believing that it is essential for the company's success and the overall economy.

6. **Criminal Justice System:** People may defend the actions of the criminal justice system, even when confronted with evidence of racial biases in arrests, sentencing, and incarceration rates, to maintain faith in the system's fairness and legitimacy.

7. **Social Class Mobility:** Individuals from privileged backgrounds may attribute their success to personal merit and hard work, while downplaying the impact of social advantages and privileges they have received.

8. **Educational Opportunities:** In a society with unequal access to quality education, individuals may justify the disparities in educational opportunities by suggesting that certain groups are less capable or motivated to succeed academically.

9. **Healthcare Disparities:** Despite evidence of healthcare disparities affecting marginalized communities, some individuals may justify the unequal access to healthcare by attributing it to individual responsibility and lifestyle choices.

10. **Environmental Policies:** People may support environmentally harmful policies and practices to maintain economic growth and job opportunities, downplaying the long-term consequences of such decisions on the environment and future generations.

These scenarios demonstrate how system justification bias can manifest in various contexts and contribute to the perpetuation of existing social structures and inequalities by rationalizing and defending the status quo.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Advertising Overload" and give me a small user story from it**

**User Story: Resisting Advertising Overload**

**User Story: Addressing the Gender Wage Gap**

As a young professional working in a reputable company, I become aware of the gender wage gap issue through conversations with colleagues and media reports. I notice that female employees, despite having similar qualifications and experience as their male counterparts, are being paid less for equivalent positions.

Motivated to address this inequality, I decide to gather data and evidence to understand the extent of the gender wage gap within the company. I conduct a thorough analysis of salaries, considering factors such as job roles, years of experience, and performance metrics.

Upon discovering the substantial wage disparities, I feel compelled to advocate for change. I approach the human resources department with my findings, presenting a comprehensive report that highlights the wage discrepancies based on gender. I emphasize the importance of creating a fair and equitable pay structure for all employees, regardless of gender.

At first, some colleagues respond defensively, citing various reasons for the disparities. However, I persist in my efforts and collaborate with like-minded coworkers who share the same passion for workplace equality. Together, we form an internal diversity and inclusion committee, aiming to bring attention to the gender wage gap issue and advocate for meaningful changes.

Through our collective efforts and persistence, the company begins to acknowledge the existence of the gender wage gap and takes active steps to address it. They implement measures such as salary reviews, transparent pay scales, and diversity training to ensure fair compensation practices.

Over time, the company achieves significant progress in narrowing the gender wage gap. Female employees feel more valued and empowered, leading to improved morale and overall job satisfaction. The success of our initiative inspires other organizations to also review their pay structures and make necessary adjustments to create a more equitable workplace for everyone.

As a result of our dedication and commitment, we contribute to reducing the gender wage gap not only within our company but also in the broader business community. Our actions demonstrate the importance of challenging and dismantling system justification bias, promoting equality, and fostering a workplace that values diversity and fairness.

***We can now derive CQs from the user story***

* CQ1: What are the primary factors that contribute to disparities in compensation or treatment within diverse contexts?
* How do individual perceptions and biases about specific attributes influence decision-making processes in various scenarios?
* CQ3: What strategies and interventions can be utilized to address and mitigate bias-related disparities effectively?
* CQ4: How does systemic bias and discrimination perpetuate unequal treatment or outcomes across different domains?
---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "System justification", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **SystemJustificationBias:** The main class representing the system justification bias itself. Instances of this class will represent the specific instances of the bias encountered in different scenarios.
3. **DecisionMaker:** Represents individuals or entities who make decisions influenced by biases, including the system justification bias. Subclasses of DecisionMaker can be used to represent different types of decision-makers, such as individuals, organizations, or governments.
4. **Context:** Represents the specific situations or contexts in which the system justification bias may occur. Instances of this class will represent various scenarios where decision-makers may exhibit the bias.
5. **Influence:** Represents the factors or entities that influence decision-makers and contribute to the perpetuation of biases. Subclasses can represent various types of influences, such as social influence, cultural influence, or media influence.
6. **Consequence:** Represents the outcomes or consequences of decision-making influenced by the system justification bias. Subclasses can represent different types of consequences, such as social consequences, economic consequences, or political consequences.

**Properties:**

1. **hasSystemJustificationBias:** Indicates that a DecisionMaker is influenced by the system justification bias.
2. **occursInContext:** Relates instances of the SystemJustificationBias class to the specific Context in which the bias occurs.
3. **influencesDecisionMaker:** Relates instances of the Influence class to DecisionMakers to indicate the factors or entities that influence their decisions and actions.
4. **contributesToBias:** Relates instances of the Influence class to a specific type of Bias (e.g., SystemJustificationBias) it contributes to.
5. **leadsToConsequence:** Relates instances of the Bias class (e.g., SystemJustificationBias) to a Consequence it may lead to (e.g., social consequences).

These classes and properties will provide a solid foundation for modeling the system justification bias in various scenarios and contexts. The ontology can be expanded further with specific instances and relationships, enabling a comprehensive understanding of how the bias operates and influences decision-making processes.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Decision-Making in a Workplace*

Entities: Sarah (Individual), ABC Corporation (Organization)
Classes: DecisionMaker, SystemJustificationBias, Context, Influence, Consequence
Properties: hasSystemJustificationBias true (for Sarah), occursInContext (relates SystemJustificationBias to DecisionMaker), influencesDecisionMaker (relates Influence to DecisionMaker), contributesToBias (relates Influence to SystemJustificationBias), leadsToConsequence (relates SystemJustificationBias to Consequence)

Description: Sarah works at ABC Corporation and is involved in critical decisions related to resource allocation and budget planning. She exhibits the system justification bias, often favoring decisions that maintain the existing hierarchical structure and resource distribution, even if alternative approaches could lead to more equitable outcomes. The ontology can represent Sarah as a DecisionMaker with the system justification bias (hasSystemJustificationBias true). It can also capture the specific context in which the bias occurs (Context class), such as resource allocation meetings or budget planning sessions. Additionally, the ontology can model various influences (Influence class), such as organizational culture, peer pressure, or leadership norms, that contribute to Sarah's bias (contributesToBias). These influences may perpetuate a belief that maintaining the status quo is necessary for organizational stability. The ontology can also capture the potential consequences (Consequence class) of such decisions influenced by the system justification bias, including potential disparities in resource distribution and reduced opportunities for innovation and growth (leadsToConsequence).

*Example 2: Political Decision-Making*

Entities: Government A (Organization), Bill (Individual)
Classes: DecisionMaker, SystemJustificationBias, Context, Influence, Consequence
Properties: hasSystemJustificationBias true (for Government A), occursInContext (relates SystemJustificationBias to DecisionMaker), influencesDecisionMaker (relates Influence to DecisionMaker), contributesToBias (relates Influence to SystemJustificationBias), leadsToConsequence (relates SystemJustificationBias to Consequence)

Description: Government A faces critical policy decisions that affect various social and economic aspects of the country. The government exhibits the system justification bias, often leaning towards maintaining established policies and practices to uphold stability and public order, even if alternative policies could bring positive changes. The ontology can represent Government A as a DecisionMaker with the system justification bias (hasSystemJustificationBias true). It can also capture the specific contexts in which the bias occurs, such as policy-making sessions or strategic planning meetings (Context class). Various influences, such as public opinion, historical precedents, or vested interests (Influence class), may contribute to the government's bias (contributesToBias). These influences may lead decision-makers to justify existing policies, regardless of their effectiveness or relevance to the current societal needs. The ontology can further model the potential consequences (Consequence class) of such decisions influenced by the system justification bias, such as stagnation in policy innovation and possible societal inequalities (leadsToConsequence).

*Example 3: Education System Assessment*

Entities: Education Department (Organization), Evaluation Committee (Group)
Classes: DecisionMaker, SystemJustificationBias, Context, Influence, Consequence
Properties: hasSystemJustificationBias true (for Education Department), occursInContext (relates SystemJustificationBias to DecisionMaker), influencesDecisionMaker (relates Influence to DecisionMaker), contributesToBias (relates Influence to SystemJustificationBias), leadsToConsequence (relates SystemJustificationBias to Consequence)

Description: The Education Department is tasked with assessing the effectiveness of the current education system and potential reforms to enhance learning outcomes. The department exhibits the system justification bias, often favoring the continuation of traditional education models, even if alternative approaches could yield better results. The ontology can represent the Education Department as a DecisionMaker with the system justification bias (hasSystemJustificationBias true). It can also capture the specific context of decision-making, such as curriculum evaluation or teacher training (Context class). Various influences, such as educational norms, political pressures, or historical perceptions of schooling (Influence class), may contribute to the department's bias (contributesToBias). These influences may lead decision-makers to adhere to established educational practices without fully considering alternative strategies. The ontology can also model the potential consequences (Consequence class) of such decisions influenced by the system justification bias, such as missed opportunities for educational innovation and improvements in student learning outcomes (leadsToConsequence).

These examples demonstrate how the ontology can be applied to different scenarios, capturing decision-making processes influenced by the system justification bias and the factors contributing to its perpetuation, as well as potential consequences arising from such decisions. The generic classes and properties allow for flexible representation and analysis of the bias in diverse contexts.