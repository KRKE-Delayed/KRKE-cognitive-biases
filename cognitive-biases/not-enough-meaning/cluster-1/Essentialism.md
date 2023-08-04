# Essentialism bias

## CLUSTER: We fill in characteristics from stereotypes, generalities, and prior histories

## 1. Context and Literature State of the Art

**Wikipedia:**
Essentialism is the view that objects have a set of attributes that are necessary to their identity. In early Western thought, Plato's idealism held that all things have such an "essence"—an "idea" or "form". In Categories, Aristotle similarly proposed that all objects have a substance that, as George Lakoff put it, "make the thing what it is, and without which it would be not that kind of thing". The contrary view—non-essentialism—denies the need to posit such an "essence'".

Essentialism has been controversial from its beginning. Plato, in the Parmenides dialogue, depicts Socrates questioning the notion, suggesting that if we accept the idea that every beautiful thing or just action partakes of an essence to be beautiful or just, we must also accept the "existence of separate essences for hair, mud, and dirt".

In biology and other natural sciences, essentialism provided the rationale for taxonomy at least until the time of Charles Darwin; the role and importance of essentialism in biology is still a matter of debate.

In modern times, academics in science, aesthetics, heuristics, psychology, and gender-based sociological studies have advanced their causes under the banner of essentialism.
[Wikipedia Link](https://en.wikipedia.org/wiki/Essentialism)

**Reasearch paper:**
[Cartwright, Richard L. (1968). "Some Remarks on Essentialism". The Journal of Philosophy. 65 (20): 615–626.](https://www.pdcnet.org/jphil/content/jphil_1968_0065_0020_0615_0626)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Essentialism"**

Essentialism bias refers to the cognitive tendency or belief that individuals or groups possess inherent, unchangeable, and fixed `characteristics` that `define` their `nature` or `identity`. This bias often `oversimplifies` and `generalizes` complex attributes, behaviors, or `traits` based on perceived fundamental qualities, `ignoring` the influence of `context`, environment, and individual variations. Essentialism bias can lead to `stereotypes`, `discrimination`, and a limited understanding of the true `diversity` and dynamic nature of people and entities. It may manifest in various contexts, such as `gender`, `race`, `culture`, or other categorizations, reinforcing rigid and oversimplified views that fail to capture the richness of human experiences and `identities`.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Essentialism"**

Certainly, here are 10 example scenarios that illustrate "Essentialism" bias:

1. **Gender Roles**: `Assuming` that all women are naturally `inclined` towards caregiving and homemaking, while all men are naturally inclined towards leadership and assertiveness.

2. **Racial Stereotypes**: Believing that people of a certain race are `inherently` more athletic or intellectually gifted, ignoring the influence of individual effort and environmental factors.

3. **National Stereotypes**: Thinking that individuals from a specific country all share the same cultural traits or behaviors, ignoring the diversity within that country.

4. **Sexuality Assumptions**: Assuming that all individuals who identify as LGBTQ+ have certain personality traits or interests based solely on their sexual `orientation`.

5. **Age Bias**: Believing that older individuals are inherently technologically `incompetent` or resistant to change, `disregarding` the wide range of technological skills among different age groups.

6. **Religious Generalizations**: `Stereotyping` all followers of a particular `religion` as having the same beliefs and behaviors, disregarding the diversity of thought within that religious `group`.

7. **Parenting Norms**: Believing that mothers are inherently better caregivers than fathers, ignoring the `unique` parenting styles and capabilities of individual parents.

8. **Language Proficiency**: Assuming that individuals who speak with an accent are less `competent` or intelligent in a given language, disregarding their proficiency and fluency.

9. **Ethnic Cuisine**: Associating specific cuisines only with certain ethnic groups, oversimplifying the culinary diversity and influences that contribute to a cuisine's development.

10. **Artistic Talent**: Believing that certain races or cultures are naturally more artistic or creative, neglecting the individual talents and artistic `backgrounds` of people from various backgrounds.

These scenarios demonstrate how "Essentialism" bias can lead to oversimplified and often inaccurate perceptions of individuals and groups, failing to consider the complexities and individual variations that contribute to human identity and behavior.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Language Profiency" and give me a small user story from it**

**User Story: Language Profiency and Essentialism Bias**

Meet Alex, a dedicated linguist who has a passion for learning and speaking different languages. Alex comes from a multicultural background and has traveled extensively, interacting with people from diverse linguistic backgrounds. Despite their impressive language skills, Alex often encounters a frustrating bias `rooted` in essentialism.

One day, Alex attended an international conference where experts from various fields gathered to discuss their research. During a panel discussion, Alex raised a thought-provoking question. However, when Alex spoke, their unique accent was noticeable. After the panel ended, a fellow attendee approached Alex and said, "Your question was intriguing, but it's clear that English isn't your first language. You should work on your language skills before participating."

This comment left Alex feeling disheartened. The assumption that Alex's accent indicated a lack of language proficiency was a classic case of essentialism bias. The attendee had jumped to conclusions `based on` a `superficial` trait, disregarding Alex's deep understanding of multiple languages and their extensive efforts to communicate effectively across cultures.

Determined to challenge this `bias`, Alex decided to engage in a one-on-one conversation with the attendee. Alex shared their linguistic journey, explaining how being multilingual was a key aspect of their `identity` and career. By sharing personal `experiences` and stories of overcoming language `barriers`, Alex successfully challenged the essentialism bias that had led the attendee to make a hasty `judgment`.

The encounter served as a valuable reminder that language proficiency is not solely defined by accent or first language, but rather by a combination of `factors`, including fluency, comprehension, and effective communication. Alex's story became a catalyst for promoting awareness and understanding of essentialism bias, encouraging others to recognize and appreciate the richness of linguistic diversity and the individual journeys of language learners.

***We can now derive CQs from the user story***

* CQ1: What are the primary characteristics that contribute to create inner bias?
* CQ2: How do personal experience influence the judgment on real scenarios?
* CQ3: How to recognize the effects of this bias?
* CQ4: What are the impact of this bias on individuals and groups interactions?
---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Essentialism", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **BiasType:** Represents different categories of essentialism biases that generalize traits or attributes to specific groups.
3. **EssentialismBias:** Instances of biases that involve attributing fixed traits to groups.
4. **targetGroup:** Specifies the Group instance that is the subject of the essentialism bias in a particular EssentialismBias instance.
5. **Influence:** Represents the factors or entities that influence decision-makers and contribute to the perpetuation of biases. Subclasses can represent various types of influences, such as social influence, cultural influence, or media influence.
6. **SocialRoleBias:** Represents biases that attribute specific social roles or behaviors to certain groups.

**Properties:**

1. **hasBiasType:** Connects an EssentialismBias instance to its corresponding BiasType instance, indicating the type of essentialism bias involved.
2. **targetsGroup:** Specifies the Group instance that is the subject of the essentialism bias in a particular EssentialismBias instance.
3. **hasName:** Assigns a name or label to Group and Trait instances.
4. **isInherent:** Indicates whether a Trait instance is inherently associated with individuals possessing it.
5. **isAttributedToGroup:**  Connects a Trait instance to the Group instance that it is commonly attributed to.

These classes and properties will provide a solid foundation for modeling the system justification bias in various scenarios and contexts. The ontology can be expanded further with specific instances and relationships, enabling a comprehensive understanding of how the bias operates and influences decision-making processes.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Gender Roles Bias*

In this scenario, we'll focus on the "Gender Roles" bias:

BiasType: GenderBias
EssentialismBias: GenderRolesBias
Properties:
hasBiasType: GenderBias
targetsGroup: Women
Group: Women
Properties:
hasName: "Women"
hasMembers: [Alice, Sarah, Emily]
Trait: Caregiving
Properties:
hasName: "Caregiving"
isInherent: true
isAttributedToGroup: Women

*Example 2: Racial Stereotypes*

Now let's examine the "Racial Stereotypes" scenario:

BiasType: RacialBias
EssentialismBias: IntellectualAbilityBias
Properties:
hasBiasType: RacialBias
targetsGroup: AfricanAmericans
Group: AfricanAmericans
Properties:
hasName: "African Americans"
hasMembers: [Jamal, Maya, Malik]
Trait: IntellectualAbility
Properties:
hasName: "Intellectual Ability"
isInherent: false
isAttributedToGroup: AfricanAmericans

*Example 3: Language Proficiency Bias*

Lastly, let's explore the "Language Proficiency" bias:

BiasType: LanguageProficiencyBias
EssentialismBias: AccentIntelligenceBias
Properties:
hasBiasType: LanguageProficiencyBias
targetsGroup: NonNativeSpeakers
Group: NonNativeSpeakers
Properties:
hasName: "Non-Native Speakers"
hasMembers: [Elena, Javier, Mei]
Trait: LanguageProficiency
Properties:
hasName: "Language Proficiency"
isInherent: false
isAttributedToGroup: NonNativeSpeakers

In these examples, the ontology's classes and properties help represent and organize the concepts of essentialism bias, specific biases, groups, and traits. The properties establish meaningful relationships between instances, allowing us to model real-world situations where essentialism bias can occur and its implications on various groups and traits.

## 3. Words as Frame Semantic Triggers

To further align the biases with existing semantic frames in Framester, we leverage powerful knowledge extraction tools like QUOKKA's "Concepts Extractor" and FRED.

In QUOKKA, we extracted concepts from the following lexical units:

**- identity**
**- generalize**
**- stereotype**
**- gruop**

We cross our results with the ones obtained in FRED by putting the following scenario:

1. **Gender Roles**: `Assuming` that all women are naturally `inclined` towards caregiving and homemaking, while all men are naturally inclined towards leadership and assertiveness.

By doing these two steps, we selected the following **frames**:

**- Categorization**
**- Aggregate**