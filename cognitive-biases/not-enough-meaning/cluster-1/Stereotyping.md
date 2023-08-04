# Fuctional Fixedness bias

## 1. Context and Literature State of the Art

**Wikipedia:**
Functional fixedness is a cognitive bias that limits a person to use an object only in the way it is traditionally used. The concept of functional fixedness originated in Gestalt psychology, a movement in psychology that emphasizes holistic processing. Karl Duncker defined functional fixedness as being a mental block against using an object in a new way that is required to solve a problem. This "block" limits the ability of an individual to use components given to them to complete a task, as they cannot move past the original purpose of those components.
[Wikipedia Link](https://en.wikipedia.org/wiki/Functional_fixedness)

**Reasearch paper:**
[Duncker, K. (1945). "On problem solving". Psychological Monographs, 58:5 (Whole No. 270).]

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Functional fixedness"**

Functional fixedness bias is a cognitive bias that refers to the `tendency` of individuals to `perceive` objects or concepts as having a `fixed`, specific function or purpose, `limiting` their ability to see and `consider` `alternative` uses or functions. This bias can `hinder` creative `problem-solving` and innovative thinking, as people may become trapped in conventional or established ways of thinking about an object, hindering their ability to see its potential for new or unconventional purposes. Overcoming functional fixedness bias is crucial for fostering creativity and finding novel solutions to problems.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Functional fixedness"**

Certainly, here are ten example scenarios illustrating functional fixedness bias:

1. **Candle and Matches Problem**: When trying to attach a candle to a wall and light it, individuals may struggle to `consider` using the matchbox as a makeshift candle holder due to functional `fixedness`, instead of only using the candlestick.

2. **Belt as a Tool**: When a person's car is stuck in the snow, they might `overlook` using their belt as a makeshift tow strap due to viewing it solely as an accessory.

3. **Paperclip Uses**: People might primarily `associate` a paperclip with holding papers together and overlook its `potential` use as a makeshift lock pick or smartphone stand.

4. **Jar as a Container**: Someone might struggle to see a glass jar as a potential makeshift drinking glass or container for non-food items, due to their fixed `perception` of it being solely a storage container.

5. **Book as a Monitor Stand**: People might not think to use a thick book as a makeshift stand to elevate their computer monitor, as they see books only as reading materials.

6. **Spoon as a Doorstop**: When a door needs propping open, individuals might overlook using a spoon as a makeshift doorstop due to their `habitual` association of a spoon with eating.

7. **Bucket as a Chair**: When chairs are in short supply, individuals might not consider using an empty bucket as a makeshift seat due to their `preconceived` notion of a bucket's use.

8. **Clothes Hanger as Headphone Holder**: People may not think of using a clothes hanger to hang and organize their headphones, `perceiving` hangers solely as tools for clothing.

9. **CD/DVD Spindle as Bagel Holder**: Someone might struggle to see the potential of using a CD or DVD spindle as a holder for bagels or other round food items, `viewing` it only as a storage container for discs.

10. **Plastic Bottle as Plant Watering Device**: People might overlook using a plastic bottle with holes in the cap as a DIY watering device for potted plants, due to their fixed perception of plastic bottles as only beverage containers.

In each of these scenarios, functional fixedness bias limits individuals from seeing alternative, creative uses for familiar objects, hindering their ability to solve problems in `innovative` ways.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Candle and Matches Problem" and give me a small user story from it**

**User Story: The Bright Idea**

As the winter storm raged outside, Sarah found herself in a power outage. With darkness enveloping her home, she knew she needed to find a way to light up the room. Remembering a box of candles and matches in her kitchen drawer, she eagerly retrieved them. However, as she attempted to fix the candle on the table, frustration crept in. She struggled to keep the candle upright and secure.

Sarah had a moment of `inspiration`. She remembered a trick she had once seen on a survival show. With a `determined` glint in her eye, she fetched the box of matches and held it horizontally against the wall. Carefully, she placed the candle onto the box, allowing it to rest securely. Now, she just needed a way to light the candle.

Rummaging through her kitchen tools, Sarah found a metal fork. With a grin, she struck a match and used the flaming stick to light the candle. The room was bathed in a warm, flickering glow, providing both comfort and much-needed illumination.

Reflecting on her experience, Sarah realized how functional fixedness had initially clouded her problem-solving. She had narrowly focused on the candlestick, `disregarding` the `potential` of the matchbox as a clever makeshift candle holder. Her `resourcefulness` and the `ability` to `think outside` the box had transformed a simple matchbox into a vital tool during a blackout. Sarah felt a renewed sense of empowerment, knowing that creativity and `adaptability` could turn everyday objects into unexpected heroes.

***We can now derive CQs from the user story***

* CQ1: What cognitive processes contribute to the development of functional fixedness bias?
* CQ2: How does functional fixedness bias impact creativity and inventive thinking in problem-solving contexts?
* CQ3: What strategies or techniques can individuals employ to overcome functional fixedness bias and encourage more innovative thinking?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Functional fixedness", what classes and properties would you create?**

**Classes:**

1. **CognitiveBias:** Represents various types of biases, including the system justification bias. This class serves as a superclass for specific types of biases such as confirmation bias, availability bias, and more.
2. **FunctionalFixedness:** Represents a cognitive bias observed in human thinking, characterized by the tendency to perceive objects, concepts, or elements as having fixed, predefined functions or purposes.
3. **CognitiveProcesses:** Represents the class of cognitive processes involved in how individuals perceive objects and their functions. It's relate to how individuals form mental representations of objects and their intended purposes.
4. **Problem-SolvingStrategies:** Represents the use of analogies to relate familiar situations to unfamiliar ones, potentially aiding in overcoming functional fixedness. It's about looking at a problem from a different perspective to reveal alternative solutions.
5. **CognitiveFlexibility:** Represents an individual's capacity to adjust their cognitive processes and thinking patterns to different contexts, aiding in overcoming functional fixedness.

**Properties:**

1. **AffectsProblemSolving:** Describes the influence of functional fixedness on the process of problem-solving, often leading to suboptimal or conventional solutions.
2. **InvolvesPerception:** Represents the cognitive process through which an individual's perception of an object's primary function contributes to functional fixedness bias.
3. **InhibitsCreativity:** Indicates how functional fixedness acts as a barrier to creative thinking and innovative idea generation.
4. **RelatedToObjectFunction:** Links functional fixedness to an object's conventional or known functions, often leading to a narrow perspective on its potential utility.
5. **LeadsToSuboptimalOutcome:** Highlights the negative consequences of failing to address functional fixedness, often resulting in limited or less effective problem-solving strategies.

These classes and properties will provide a solid foundation for modeling the system justification bias in various scenarios and contexts. The ontology can be expanded further with specific instances and relationships, enabling a comprehensive understanding of how the bias operates and influences decision-making processes.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Candle and Matches Problem*

Scenario:
Lisa is preparing for a cozy dinner at home during a power outage. She wants to create a warm ambiance using candles but realizes she doesn't have a candle holder.

Usage of Classes and Properties:

Class: Functional Fixedness
HasExampleScenario: "CandleAndMatchesProblem"
Explanation:
In this scenario, Lisa encounters functional fixedness when she fails to recognize the matchbox's potential as a makeshift candle holder. The property "HasExampleScenario" links this situation to the "CandleAndMatchesProblem" instance, illustrating how her fixed perception of a matchbox only as a container for matches restricts her creative problem-solving.

*Example 2: Creative Office Solutions*

Scenario:
An office manager, Alex, is tasked with rearranging the workspace to accommodate more employees. The office is short on chairs, and Alex wants to find creative solutions.

Usage of Classes and Properties:

Class: Problem-Solving Strategies
Analogical Thinking
Reframing
Class: Cognitive Flexibility
Adaptability
Explanation:
In this scenario, Alex employs problem-solving strategies such as analogical thinking and reframing to overcome functional fixedness. The properties "Analogical Thinking" and "Reframing" under the class "Problem-Solving Strategies" highlight Alex's use of these techniques to see office items beyond their traditional functions. Additionally, the class "Cognitive Flexibility" and the property "Adaptability" emphasize Alex's ability to adapt his thinking, mitigating functional fixedness and promoting innovative solutions.

*Example 3: Cultural Influence on Tool Usage*

Scenario:
Maria, a cultural anthropologist, is studying a remote tribe's daily routines. She notices that tribe members use objects in unique ways that differ from Western practices.

Usage of Classes and Properties:

Class: Cultural Influence
Cultural Influence
Explanation:
In this scenario, Maria explores how cultural norms influence functional fixedness. The property "Cultural Influence" under the class "Cultural Influence" allows Maria to examine how the tribe's distinct cultural perspectives and practices affect their perception of object functions. This highlights the role of culture in shaping functional fixedness and the potential for different societies to exhibit varying levels of this cognitive bias.

These examples illustrate how the classes and properties within the ontology can be applied to diverse situations, showcasing the impact of functional fixedness on problem-solving, the use of strategies to overcome it, and its interaction with cultural influences.