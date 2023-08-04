# Automation bias

## CLUSTER: We fill in characteristics from stereotypes, generalities, and prior histories

## 1. Context and Literature State of the Art

**Wikipedia:**
Automation bias is the propensity for humans to favor suggestions from automated decision-making systems and to ignore contradictory information made without automation, even if it is correct. Automation bias stems from the social psychology literature that found a bias in human-human interaction that showed that people assign more positive evaluations to decisions made by humans than to a neutral object. The same type of positivity bias has been found for human-automation interaction, where the automated decisions are rated more positively than neutral. This has become a growing problem for decision making as intensive care units, nuclear power plants, and aircraft cockpits have increasingly integrated computerized system monitors and decision aids to mostly factor out possible human error. Errors of automation bias tend to occur when decision-making is dependent on computers or other automated aids and the human is in an observatory role but able to make decisions. Examples of automation bias range from urgent matters like flying a plane on automatic pilot to such mundane matters as the use of spell-checking programs. [Wikipedia Link](https://en.wikipedia.org/wiki/Automation_bias)

**Reasearch paper:**
[Cummings, Mary (2004). "Automation Bias in Intelligent Time Critical Decision Support Systems" (PDF). AIAA 1st Intelligent Systems Technical Conference.](https://arc.aiaa.org/doi/10.2514/6.2004-6313)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Automation bias"**

"Automation bias" refers to a cognitive phenomenon in which individuals place an undue degree of `trust` or `reliance` on automated systems, `technology`, or algorithms, often leading to a decreased level of `critical` thinking and decision-making. This bias can cause individuals to unquestioningly accept the output or recommendations of automated systems, even when those outputs may be `incorrect`, `inappropriate`, or biased. Automation bias can emerge in situations where individuals perceive automated systems as `infallible` or superior, potentially leading to errors or overlooking critical information that requires human `judgment` and intervention.
---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Automation bias"**

Certainly, here are ten example scenarios that illustrate the "Automation Bias":

1. **Autopilot Dependence:** A pilot becomes overly reliant on an aircraft's autopilot system, assuming that it will consistently make correct decisions. When the system encounters a rare and complex situation, the pilot delays taking manual `control`, leading to a critical safety issue.

2. **Medical Diagnosis:** A physician heavily relies on a diagnostic algorithm to determine a patient's condition, overlooking important clinical cues and symptoms that may not align with the algorithm's `prediction`.

3. **Financial Investment:** An investor places complete trust in an automated trading algorithm to manage their portfolio. The algorithm makes a series of high-risk trades without human intervention, resulting in significant financial losses.

4. **Navigation Systems:** A driver follows a GPS navigation system's instructions without questioning its `accuracy`. The system leads them to an incorrect location, as it failed to account for recent road closures.

5. **Security Screening:** Airport security personnel rely solely on automated screening systems to identify potential threats in luggage. A prohibited item goes unnoticed due to the staff's `unquestioning` reliance on the technology.

6. **Language Translation:** A professional translator uses an automated translation tool to quickly convert a document into another language. The tool mistranslates a crucial legal term, leading to a misunderstanding in the translated document.

7. **Manufacturing Quality Control:** Factory workers trust automated quality control systems to detect defects in products. A flawed item passes inspection due to an oversight in the system's `programming`.

8. **Customer Service Chatbots:** Customers interact with a company's chatbot for support. The chatbot consistently provides inaccurate or irrelevant answers, yet customers continue to follow its `suggestions`.

9. **Social Media `Recommendations`:** Users allow algorithms on social media platforms to curate their news feed. The algorithms reinforce their existing beliefs, leading to a narrow and biased perspective.

10. **Autonomous Vehicles:** A driver of an autonomous vehicle becomes complacent and disengaged, assuming the vehicle will handle all driving tasks. When faced with a sudden obstacle, the driver fails to react in time to prevent a collision.

In each of these scenarios, the "Automation Bias" leads individuals to rely excessively on automated systems, technology, or algorithms, often resulting in errors, oversights, or inappropriate actions due to the failure to critically assess the output or recommendations provided by the automation.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Security Screening" and give me a small user story from it**

**User Story: Mitigating Automation Bias in Security Screening**

As a security supervisor at a busy international airport, I encountered a situation that emphasized the importance of mitigating the "Automation Bias" in our security screening procedures. Our team had recently `implemented` an advanced automated scanning system for inspecting passengers' luggage.

One day, a passenger's bag triggered an alert on the automated scanner. The system indicated a potential prohibited item within the bag. As per our protocol, our security staff was required to conduct a manual inspection of the bag to confirm the nature of the item.

However, I noticed that some of the security personnel appeared to be overly `reliant on` the automated alert. Instead of conducting a thorough manual inspection, a few staff members began to question the necessity of further examination, assuming that the automated system wouldn't make an error.

Recognizing the potential for automation bias, I immediately intervened. I reminded the team about the importance of human judgment in security screening and the possibility of false positives or technical glitches. I emphasized that our `responsibility` was to ensure the safety of passengers and that a thorough `manual` inspection was crucial.

We proceeded to follow protocol and thoroughly inspected the bag, discovering a small electronic device that had triggered the alert. While it turned out to be a harmless personal item, this incident served as a valuable reminder to the team about the need to `balance` automation with human judgment.

After the incident, I organized a training session on automation bias, discussing the risks and potential consequences of `blindly` trusting automated alerts. We practiced scenarios that involved both automated systems and manual inspections to help staff members develop a more critical and balanced approach to security screening.

This user story demonstrates how awareness of automation bias prompted a security supervisor to intervene, ensuring that security personnel `critically` assessed the situation and conducted a thorough inspection. It also highlights the importance of ongoing training to mitigate the effects of the "Automation Bias" in security procedures.

***We can now derive CQs from the user story***

* CQ1: What strategies can be employed to strike a balance between leveraging the benefits of automation while ensuring that human judgment remains a crucial component in decision-making processes?
* CQ2: How can individuals assess the accuracy and reliability of outputs from automated systems to prevent unwarranted trust and mitigate potential errors caused by automation bias?
* CQ3: What role do education and training programs play in raising awareness about automation bias among professionals who rely on automated systems, and how can these programs effectively promote critical thinking and vigilance?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Automation bias", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **AutomationBias:** The overarching concept representing the cognitive bias where individuals excessively trust or rely on automated systems, technology, or algorithms, leading to decreased critical thinking and decision-making.
3. **TechnologicalDependence:** Examines the broader societal implications of automation bias, including the potential consequences of excessive dependence on technology and automation.
4. **EthicsofAutomationDevelopment:** Addresses the ethical considerations involved in designing and developing automated systems to minimize biases and promote responsible automation.
5. **LearningfromAutomationErrors:** Explores how organizations can learn from instances where automation bias led to errors, promoting continuous improvement and error prevention.
6. **CulturalandContextualInfluences:** Investigates how cultural norms, societal context, and individual attitudes shape the manifestation and impact of automation bias.
7. **AutomationTransparency:** Focuses on the transparency of automated systems, including the availability of explanations for their decisions to help users understand and question outputs.
8. **Human-CenteredDesign:** Reflects on the principles of designing automated systems that prioritize human needs, decision-making processes, and cognitive biases.

**Properties:**

1. **hasAutomationBias:** Indicates that a DecisionMaker is influenced by the automation bias.
2. **automatedSystemTrust:** Relates an individual to their level of trust or reliance on an automated system's output or recommendations.
3. **humanJudgmentBalance:** Connects individuals to their ability to balance the benefits of automation with the importance of human judgment in decision-making.
4. **criticalEvaluation:** Represents the process of critically assessing automated outputs before accepting or acting upon them.
5. **errorRecognition:**  Illustrates an individual's capacity to recognize errors or inconsistencies in automated outputs and their willingness to question the system's accuracy.
6. **overrelianceAwareness:** Relates an individual to their awareness of the potential for overreliance on automation and its consequences.
7. **cognitiveBiasesInteraction:** Connects the automation bias to the interaction with other cognitive biases, emphasizing the need to consider multiple biases in decision-making.
8. **automationEthics:** Focuses on the ethical considerations related to automation bias, including the responsibility of designers and developers to minimize bias in automated systems.
9. **technologicalAdvancement:** Reflects the impact of technological advancements on the prevalence and implications of automation bias.
10. **decisionSupportSystems:** Represents the role of decision support systems that aim to provide guidance without displacing human judgment entirely.


This ontology structure outlines specific classes and properties that characterize various aspects of the "Automation Bias," from trust in automated systems to critical evaluation, ethical considerations, and the role of education. It provides a structured framework for analyzing and understanding the complexities of this cognitive bias and its implications.

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Bias Mitigation Strategies in Autonomous Vehicles*

Class: Bias Mitigation Strategies

Properties:

automatedSystemTrust
cognitiveBiasesInteraction
decisionMakingResilience
Scenario: Developers of autonomous vehicles are working to mitigate automation bias in their systems. They incorporate strategies to balance passengers' trust in the automated driving system while addressing cognitive biases that might arise, such as complacency. The vehicles are designed to provide alerts and prompts to encourage drivers to remain attentive and ready to take control, promoting a resilient decision-making process that combines automation with human judgment.

*Example 2: Ethical Considerations in Automated Hiring Systems*

Class: Ethics of Automation Development

Properties:

automationEthics
biasInDataAndAlgorithms
transparency
Scenario: A company is developing an automated system to screen job applicants. The development team focuses on minimizing bias by regularly auditing and refining the algorithms to ensure fairness. They also prioritize transparency by providing clear explanations of how the system makes decisions. Additionally, they offer training to hiring managers on recognizing the potential for automation bias and critically evaluating the system's recommendations.

*Example 3: Human-Automation Collaboration in Medical Diagnostics*

Class: Human-Automation Collaboration

Properties:

humanJudgmentBalance
expertiseInAutomationUse
realTimeDecisionAdaptation
Scenario: Doctors are using AI-powered diagnostic tools to aid in medical diagnoses. The medical community emphasizes the importance of maintaining a balance between the expertise of the physician and the AI's recommendations. Physicians are trained to critically evaluate the AI's suggestions and adapt their decisions in real-time based on their clinical judgment and patient context, enhancing the quality of medical care provided.

These examples demonstrate how the classes and properties from the ontology can be applied in various contexts, from mitigating bias in autonomous vehicles to addressing ethical concerns in hiring systems and fostering effective collaboration between humans and automated systems in medical diagnostics. The ontology provides a structured framework for understanding and addressing the complexities of the "Automation Bias" and its implications.

## 3. Words as Frame Semantic Triggers

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

**- technology**
**- judgment**
**- reliance**
**- programming**

We cross our results with the ones obtained in FRED by putting the following scenario:

7. **Manufacturing Quality Control:** Factory workers trust automated quality control systems to detect defects in products. A flawed item passes inspection due to an oversight in the system's `programming`.

By doing these two steps, we selected the following **frames**:

**- Gizmo**
**- Certainty**
**- Trust**
**- Reliance**