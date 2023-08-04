# Authority bias

## CLUSTER: We fill in characteristics from stereotypes, generalities, and prior histories

## 1. Context and Literature State of the Art

**Wikipedia:**
Authority bias is the tendency to attribute greater accuracy to the opinion of an authority figure (unrelated to its content) and be more influenced by that opinion. An individual is more influenced by the opinion of this authority figure, believing their views to be more credible, and hence place greater emphasis on the authority figure's viewpoint and are more likely to obey them. This concept is considered one of the social cognitive biases or collective cognitive biases.
[Wikipedia Link](https://en.wikipedia.org/wiki/Authority_bias)

**Reasearch paper:**
[Milgram, Stanley (1963). "Behavioral study of obedience". The Journal of Abnormal and Social Psychology. 67 (4): 371–378.]
(https://psycnet.apa.org/doiLanding?doi=10.1037%2Fh0040525)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Authority bias"**

"Authority bias", also known as "argument from authority," refers to a cognitive bias in which an individual attributes greater `accuracy` or `credibility` to a statement or belief based solely on the perceived `authority`, `expertise`, or `reputation` of the person or source presenting the information. This bias leads people to `accept` or `trust` information without critically `evaluating` its `validity` or `evidence`, simply because it comes from a figure of authority or someone perceived as `knowledgeable` in a particular field. While `relying` on experts and credible sources is often rational, the authority bias becomes problematic when it leads individuals to `uncritically` accept information without independent verification or `critical analysis`.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Authority bias"**

Certainly, here are ten example scenarios that illustrate the "Authority bias":

1. **Medical Advice:** A person follows a health `recommendation` simply because a celebrity endorses a particular supplement, without considering scientific evidence or consulting a healthcare professional.

2. **Educational Beliefs:** Students in a class blindly accept a teacher's explanation of a complex topic as accurate without questioning it, `assuming` that the teacher's expertise makes them infallible.

3. **News Sources:** Individuals believe a news article to be true solely because it's published by a well-known and respected news outlet, without assessing the `accuracy` of the information presented.

4. **Parental Influence:** Children accept their parents' opinions on political or societal issues without seeking `alternative` viewpoints, assuming that their parents' wisdom ensures `correctness`.

5. **Expert Witnesses:** Jurors in a trial give more weight to the testimony of an expert witness, even if their claims lack substantial evidence, solely because of the witness's professional credentials.

6. **Quoting Famous Individuals:** People share and promote quotes attributed to historical figures on social media without verifying their `authenticity`, assuming that well-known figures must have valuable insights.

7. **Investment Decisions:** An individual invests money in a company's stock based solely on a financial analyst's recommendation, without conducting their own research.

8. **Dietary Choices:** Someone adopts a specific diet endorsed by a popular influencer without considering their individual nutritional needs, assuming that the influencer's appearance validates the diet's effectiveness.

9. **Political Endorsements:** Voters support a political candidate solely because a well-known public figure endorses them, without evaluating the candidate's policies or qualifications.

10. **Scientific Claims:** People accept a scientific claim as fact simply because a scientist or researcher asserts it, without critically `examining` the methodology or peer-reviewed studies supporting the claim.

In each of these scenarios, the authority bias leads individuals to accept or trust information based on the perceived authority or credibility of the source, often bypassing critical analysis or `independent` `verification`.


---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "News Sources" and give me a small user story from it**

**User Story: Evaluating News Sources and Overcoming Authority Bias**

As an avid news consumer, I encountered a situation that highlighted the importance of `critically` `evaluating` news `sources` and avoiding the authority bias. One day, I came across an article shared on social media from a `well-known` and respected news outlet. The headline claimed a groundbreaking discovery in medical research that seemed both fascinating and potentially life-changing.

Initially, I was inclined to accept the information as accurate due to the authority of the news outlet. However, I reminded myself of the potential `influence` of the authority bias and decided to investigate further. I began by reading the article carefully, paying `attention` to the sources cited, the level of detail provided, and the quality of evidence presented.

In the article, the discovery was attributed to a single unnamed researcher without any `references` to peer-reviewed studies or scientific institutions. This lack of specific information raised a red flag for me. I conducted a quick online search to find additional sources corroborating the information. To my surprise, the only references to the discovery were on a handful of websites with dubious `credibility`.

Realizing that the initial news article lacked sufficient `verification` and `authoritative` sources, I took a more `cautious` approach. I reached out to a friend who was a medical researcher and asked for their opinion on the matter. They pointed out that a groundbreaking discovery of this magnitude would likely be covered by multiple reputable scientific journals and institutions.

Armed with this `insight`, I decided not to share the article further or accept the information as accurate until more reliable sources could confirm the discovery. This experience served as a reminder of the need to overcome the authority bias and to critically assess the credibility and evidence behind news claims, even when they come from seemingly authoritative sources.

This user story illustrates how an individual's awareness of the authority bias prompted them to critically evaluate a news article, seek additional sources, and consult an expert before accepting the information as true. It highlights the importance of independent verification and the role of critical thinking in overcoming cognitive biases.


***We can now derive CQs from the user story***

* CQ1: Why is it important to not automatically accept information and ideas solely based on superficial notions or the judgement of someone else?
* CQ2: How can you strike a balance between respecting the expertise of authorities and maintaining a healthy skepticism to ensure you're making well-informed decisions?
* CQ3: How personal experience and independent judgement influence bias?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Authority bias", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **AuthorityBias:** The overarching concept representing the cognitive bias where individuals attribute greater accuracy or credibility to information based solely on the perceived authority, expertise, or reputation of the source.
3. **SourceCredibility:** Subclass of AuthorityBias that delves deeper into the factors that contribute to the perceived credibility of a source, including qualifications, reputation, and consistency.
4. **ExpertiseRecognition:** Explores the cognitive processes involved in recognizing and assessing genuine expertise, including the ability to differentiate between authentic authorities and pseudo-experts.
5. **DiversityofPerspectives:** Focuses on the value of seeking information from a diverse range of sources and perspectives to mitigate the effects of the authority bias.
6. **EthicalConsiderations:** Examines the ethical implications of relying solely on authority in decision-making, including potential consequences for intellectual independence and integrity.
7. **SocialInfluence:**  Explores how the authority bias is influenced by social factors such as peer pressure, group dynamics, and societal norms.
8. **CriticalEvaluationStrategies:** Addresses specific techniques individuals can employ to critically evaluate information from authoritative sources, promoting a more discerning approach.

**Properties:**

1. **hasAuthorityBias:** Indicates that a DecisionMaker is influenced by the authority bias.
2. **perceivedAuthority:** Relates information to the perceived authority or expertise of the source presenting it.
3. **credibilityAssessment:** Connects individuals to their process of evaluating the credibility of a source before accepting information.
4. **unquestionedAcceptance:**  Indicates that an individual accepts information without critical evaluation due to the influence of the authority bias.
5. **evidenceEvaluation:** Represents the act of critically assessing the evidence and reasoning behind information, irrespective of the source's authority.
6. **expertiseRecognition:** Relates an individual to their ability to recognize genuine expertise and credentials in a particular field.
7. **criticalThinking:** Illustrates the skill of questioning and analyzing information, even if it comes from an authoritative source.
8. **independentVerification:** Depicts the practice of seeking additional sources or evidence to corroborate information before accepting it.
9. **alternativeViewpointConsideration:** Connects an individual to their willingness to explore and evaluate information from sources with diverse perspectives.
10. **contextualAnalysis:** Describes the process of considering the context and potential biases of a source before accepting its information as accurate.

This ontology structure outlines specific classes and properties that characterize various aspects of the "Authority Bias," from the recognition of expertise and credibility assessment to the practice of independent verification and critical thinking. It provides a structured framework for analyzing and understanding the complexities of this cognitive bias and its implications.


***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Source Credibility Assessment*

Class: Source Credibility

Properties:

perceivedAuthority
expertiseRecognition
criticalThinking
Scenario: A student is researching a controversial topic for a school project. They come across an article written by a prominent academic in the field. While the student acknowledges the authority of the author, they also apply critical thinking. They examine the author's credentials, cross-reference the information with peer-reviewed studies, and consider alternative viewpoints. This approach allows the student to leverage the authority of the source while independently verifying its credibility.

*Example 2: Media Literacy Workshop*

Class: Media Literacy Education

Properties:

mediaLiteracy
independentVerification
ethicalConsiderations
Scenario: A group of educators design a media literacy workshop for high school students. The workshop focuses on teaching students to critically evaluate news articles and online sources. Participants learn techniques to independently verify information, including checking multiple sources and assessing the credentials of authors. The workshop also highlights the ethical responsibility of media consumers to avoid blind reliance on authority and encourages a balanced approach to evaluating information.

*Example 3: Overcoming Authority Bias in Decision-Making*

Class: Overcoming the Bias

Properties:

criticalThinking
alternativeViewpointConsideration
diversityOfPerspectives
Scenario: An individual is part of a team tasked with making a business decision. The team leader, a well-respected authority in the company, presents a particular course of action. However, the individual recognizes the potential for authority bias and encourages the team to consider alternative viewpoints. They engage in critical discussions, seek input from team members with diverse perspectives, and independently research the proposed approach. By mitigating the influence of the authority bias, the team arrives at a well-rounded decision.

These examples demonstrate how the classes and properties from the ontology can be applied in different contexts to enhance critical thinking, promote media literacy, and overcome the effects of the "Authority Bias" in decision-making and information evaluation. The ontology provides a structured framework for understanding and addressing this cognitive bias.

## 3. Words as Frame Semantic Triggers

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

**- credibility**
**- authority**
**- trust**
**- verification**

We cross our results with the ones obtained in FRED by putting the following scenario:

2. **Educational Beliefs:** Students in a class blindly accept a teacher's explanation of a complex topic as accurate without questioning it, `assuming` that the teacher's expertise makes them infallible.

By doing these two steps, we selected the following **frames**:

**- Correctness**
**- Expertise**
**- Trust**
**- Statement**