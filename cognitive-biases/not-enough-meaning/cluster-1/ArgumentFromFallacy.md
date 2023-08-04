# Argument from fallacy bias

## CLUSTER: We fill in characteristics from stereotypes, generalities, and prior histories

## 1. Context and Literature State of the Art

**Wikipedia:**
Argument from fallacy is the formal fallacy of analyzing an argument and inferring that, since it contains a fallacy, its conclusion must be false. It is also called argument to logic (argumentum ad logicam), the fallacy fallacy, the fallacist's fallacy, and the bad reasons fallacy. [Wikipedia Link](https://en.wikipedia.org/wiki/Argument_from_fallacy#:~:text=Argument%20from%20fallacy%20is%20the,and%20the%20bad%20reasons%20fallacy.)

**Reasearch paper:**
[K. S. Pope (2003). "Common Logical Fallacies in Psychology: 26 Types & Examples". Fallacies & Pitfalls in Psychology.](https://kspope.com/fallacies/fallacies.php)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Argument from fallacy"**

The "Argument from Fallacy" is a logical `fallacy` that occurs when someone argues that a conclusion must be `false` or `incorrect` solely because the `argument` supporting it contains a logical fallacy or error. In other words, it asserts that if the `reasoning` presented for a certain claim is flawed, then the `claim` itself must be untrue. However, this is not a `valid` way to evaluate the `truth` or `validity` of a statement, as even a `flawed` argument could potentially lead to a true `conclusion` by coincidence or other factors. It's important to address the specific claims and evidence rather than dismissing them solely based on the presence of a fallacy in the argument.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Argument from fallacy"**

Certainly, here are ten example scenarios that illustrate the "Argument from Fallacy" fallacy:

1. **Climate Change Skepticism:** A person argues that climate change is not a significant concern because they found a spelling mistake in a scientific paper discussing its effects. They claim that since the paper contains an error, its `conclusions` about climate change must be `false`.

2. **Health Advice:** Someone argues that a particular health remedy is effective because it's been used for centuries, and ancient civilizations must have known what they were doing. They dismiss criticisms of the remedy by pointing out that their critics made a grammatical `mistake` in their analysis.

3. **Political Candidate:** A voter rejects a political candidate's economic policy proposal because the candidate made a logical fallacy in their speech. The voter concludes that since the candidate's argument is flawed, their entire economic plan must be `wrong`.

4. **Historical Claims:** An author argues that a controversial historical event didn't happen because they found a minor `inconsistency` in a document that mentions it. They assert that the inconsistency proves the event is a fabrication.

5. **Evolution Debate:** A person `dismisses` the theory of evolution by pointing out a logical `error` in a presentation given by a biologist. They conclude that if the biologist can't present a perfect argument, then evolution must be false.

6. **Technology Assessment:** An individual `rejects` the idea that electric cars are more environmentally friendly based on a grammar mistake in an article advocating for their benefits. They assert that since the article contains an error, its claims about electric cars must be `inaccurate`.

7. **Dietary Advice:** Someone argues that a specific diet is `ineffective` for weight loss because they found a formatting issue in a research study promoting it. They claim that if the study has formatting problems, its findings must be `unreliable`.

8. **Legal Argument:** A lawyer disputes a legal precedent by highlighting a logical fallacy in the judge's ruling. They conclude that since the judge committed a fallacy, the precedent is legally `invalid`.

9. **Economic Policy:** An economist dismisses an economic theory due to a logical fallacy in a presentation by its proponents. They argue that if the proponents can't construct a perfect argument, then the theory must be `flawed`.

10. **Literary Analysis:** A literature student rejects a particular interpretation of a classic novel because they found an error in grammar within an article supporting that interpretation. They assert that if the article contains a grammatical mistake, its analysis of the novel must be `incorrect`.

In each of these scenarios, the "Argument from Fallacy" fallacy is committed when individuals dismiss a claim or argument based solely on the presence of a logical fallacy, without adequately addressing the substantive points or evidence underlying the claim.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Evolution Debate" and give me a small user story from it**

**User Story: A Biologist's Defense Against the Argument from Fallacy**

As a passionate evolutionary biologist, I found myself embroiled in a heated debate about the theory of evolution with a skeptic who was employing the "Argument from Fallacy" fallacy. The skeptic had pointed out what they believed was a logical error in a recent presentation I gave on the evidence supporting the theory of evolution.

In response, I took the opportunity to address the `skeptic`'s concerns while also highlighting the fallacy they were committing. I acknowledged the error they had identified in my presentation and explained that while the error was regrettable, it did not negate the overwhelming body of evidence that supports the theory of evolution.

I emphasized that the theory of evolution is not dependent on any single argument or presentation; rather, it is a well-established scientific framework built upon a vast array of observations, experiments, and research from multiple disciplines. I shared examples of other lines of evidence, such as fossil records, comparative anatomy, and molecular genetics, which collectively paint a robust picture of the evolutionary processes shaping life on Earth.

Furthermore, I pointed out that focusing on a single error in one presentation without addressing the broader scientific consensus and empirical support for evolution is an instance of the "Argument from Fallacy" fallacy. I encouraged the skeptic to engage with the full breadth of scientific literature and to critically evaluate the theory based on its comprehensive body of `evidence`.

By using this user story, we can see how an individual confronted the "Argument from Fallacy" fallacy in a discussion about evolution and demonstrated the importance of considering the broader context and evidence when evaluating scientific theories.


***We can now derive CQs from the user story***

* CQ1: How can individuals recognize how their biases influences their experience?
* CQ2: What negative factors build the bias?
* CQ3: In what way the bias oversimplify the nature of complex arguments?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Argument from fallacy", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **ArgumentfromFallacy:** The overarching concept representing the logical fallacy where a conclusion is rejected solely based on the presence of a fallacy in the argument supporting it.
3. **FallacyTaxonomy:** Subclass of "Argument from Fallacy" that categorizes and defines various types of logical fallacies, such as ad hominem, circular reasoning, false cause, and appeal to authority.
4. **LogicalReasoningSkills:** Represents the cognitive abilities and skills required to assess arguments, identify fallacies, and make informed judgments about the validity of conclusions.
5. **EffectiveDebateTechniques:** Explores the techniques and strategies used in debates and discussions to respond to instances of the "Argument from Fallacy" bias while maintaining a constructive and persuasive argument.
6. **IntellectualHumility:** Focuses on the trait of intellectual humility, which involves recognizing the limitations of one's own knowledge and being open to considering alternative viewpoints, including those with fallacies.
7. **Fallacy Detection Tools:** Explores the development of tools and technologies, such as software or algorithms, designed to automatically identify instances of logical fallacies, including the ArgumentfromFallacy bias, in text or speech.

**Properties:**

1. **hasFallacy:** Relates an argument to a specific fallacy present within it.
2. **fallacyType:** Describes the type of fallacy identified within the argument, such as ad hominem, appeal to ignorance, or hasty generalization.
3. **unjustifiedRejection:** Connects a conclusion to the act of rejecting it without proper evaluation of its merits due to the presence of a fallacy.
4. **overlooksEvidence:** Indicates that the fallacy-focused rejection ignores relevant evidence or supporting arguments for the conclusion.
5. **criticalThinking:** Illustrates the skill of analyzing an argument and its conclusion while considering fallacies but not relying solely on their presence for assessment.
6. **logicalFallacyAwareness:** Depicts an individual's recognition and understanding of various logical fallacies and their potential impact on reasoning.
7. **fallacyEducation:** Represents efforts to educate individuals about logical fallacies, promoting the ability to discern valid critiques from unjustified dismissals.
8. **debateEthics:** Addresses the ethical considerations involved in using the ArgumentfromFallacy" fallacy during debates or discussions.
9. **validityAssessment:** Relates an argument to the process of assessing its overall validity, including the examination of premises, evidence, and reasoning.

This ontology structure outlines specific classes and properties that characterize various aspects of the "Argument from Fallacy" fallacy, from the identification of fallacies to the critical evaluation of arguments and conclusions. It provides a structured framework for analyzing and understanding the complexities of this logical fallacy and its implications.


***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Logical Fallacy Education Program*

Class: Fallacy Taxonomy

Properties:

fallacyType
Scenario: A group of educators develops a curriculum to teach students about logical fallacies, including the "Argument from Fallacy." They categorize various fallacies, such as ad hominem and circular reasoning, and explain their characteristics and implications. By understanding different fallacy types, students become equipped to identify and critically evaluate arguments in real-world contexts.

*Example 2: Media Literacy Workshop*

Class: Media Literacy

Properties:

mediaInfluence
fallacyType
Scenario: A media literacy organization conducts a workshop aimed at helping participants recognize fallacious arguments in news articles and advertisements. Participants learn to identify instances of the "Argument from Fallacy" bias, where conclusions are dismissed solely due to the presence of logical errors. They practice analyzing media messages for both fallacies and substantive content, enhancing their critical thinking skills.

*Example 3: Ethical Debate Guidelines*

Class: Debate Ethics

Properties:

debateEthics
criticalThinking
Scenario: A debating club establishes ethical guidelines for its members to promote respectful and honest discussions. One guideline discourages the use of the "Argument from Fallacy" bias as a means to dismiss opponents' arguments without addressing their substance. Members are encouraged to engage in critical thinking and respond to fallacies by addressing both the fallacy and the core argument, fostering constructive debates.

These examples demonstrate how the classes and properties from the ontology can be applied in different contexts to educate individuals, enhance critical thinking skills, and promote ethical and informed discussions when dealing with instances of the "Argument from Fallacy" bias. The ontology provides a structured framework for understanding and addressing this logical fallacy.

## 3. Words as Frame Semantic Triggers

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

**- fallacy**
**- false**
**- reject**
**- flawed**

We cross our results with the ones obtained in FRED by putting the following scenario:

1. **Climate Change Skepticism:** A person argues that climate change is not a significant concern because they found a spelling mistake in a scientific paper discussing its effects. They claim that since the paper contains an error, its `conclusions` about climate change must be `false`.

By doing these two steps, we selected the following **frames**:

**- Correctness**
**- PointOfDispute**
**- Judgment**