# Reverse Psychology

## 1. Context and Literature State of the Art

**Wikipedia:**
Reverse psychology is a technique involving the assertion of a belief or behavior that is opposite to the one desired, with the expectation that this approach will encourage the subject of the persuasion to do what is actually desired. This technique relies on the psychological phenomenon of reactance, in which a person has a negative emotional reaction to being persuaded, and thus chooses the option which is being advocated against. This may work especially well on a person who is resistant by nature, while direct requests work best for people who are compliant. The one being manipulated is usually unaware of what is really going on. [Wikipedia Link](https://en.wikipedia.org/wiki/Reverse_psychology)

**Reasearch paper:**
[Macdonald, Geoff & Nail, Paul & Harper, Jesse. (2011). Do people use reverse psychology? An exploration of strategic self-anticonformity. Social Influence. 6. 1-14. 10.1080/15534510.2010.517282.](https://www.researchgate.net/publication/233021679_Do_people_use_reverse_psychology_An_exploration_of_strategic_self-anticonformity)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Reverse psychology"**

"Reverse psychology" is a psychological `technique` used to `persuade` or `influence` someone to do something by suggesting the `opposite` of what is desired or expected. The idea behind reverse psychology is to trigger a `reaction` of resistance or defiance in the individual, leading them to `act against` the suggested course of action. In essence, the person being influenced may be more inclined to comply with the request or desire when they perceive it as a form of `rebellion` or defiance against the reverse suggestion. It is often used as a subtle method of `persuasion`, especially in parenting, marketing, and negotiation contexts.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Reverse psychology"**

1. **Parenting Technique: Bedtime Routine**: A parent wants their child to go to bed on time but faces resistance and refusal. `instead` of insisting on bedtime, the parent tells the child, "I bet you can't stay up past 9:00 PM." The reverse psychology triggers the child's desire to `prove` they can, resulting in the child willingly going to bed at the intended time.

2. **Healthy Eating Encouragement**: A nutritionist wants to encourage a client to choose healthier food options. `instead` of `directly` recommending healthier choices, the nutritionist says, "You probably won't like these delicious salads and fruits." The reverse psychology prompts the client to try the healthier options, eager to `prove` the nutritionist wrong.

3. **Study Motivation**: A teacher wants students to study for an upcoming exam. `instead` of `directly` asking them to study, the teacher says, "I know you won't be able to score well on the exam." The reverse psychology prompts students to study harder to `prove` their teacher wrong.

4. **Potty Training**: A parent wants their toddler to start using the potty. `instead` of insisting on using the potty, the parent says, "I don't think you're ready for big kid underwear." The reverse psychology `motivates` the child to use the potty to demonstrate readiness.

5. **Marketing Campaign**: A company launches a new product and wants to generate interest. `instead` of promoting the product's benefits, the marketing campaign highlights potential drawbacks or limitations. The reverse psychology arouses curiosity, `encouraging` consumers to explore the product further.

6. **Fitness Challenge**: A fitness trainer wants to motivate clients to push their limits. `Instead` of `encouraging` them `directly`, the trainer says, "I don't think you can handle this intense workout." The reverse psychology sparks determination in clients to `prove` their capabilities.

7. **Team Building Exercise**: In a team-building activity, the facilitator wants participants to work together more effectively. `Instead` of explicitly stating the goal, the facilitator says, "I doubt you can complete this task as a team." The reverse psychology `encourages` participants to collaborate and succeed.

8. **Negotiation Strategy**: In a negotiation, one party wants the other to agree to certain terms. `Instead` of insisting on those terms, they express doubt about the feasibility of reaching an agreement. The reverse psychology may lead the other party to be more open to finding common ground.

9. **Encouraging Creativity**: A teacher wants to inspire students to think creatively. `instead` of instructing them `directly`, the teacher suggests that creative thinking is difficult and beyond their abilities. The reverse psychology `encourages` students to `challenge` themselves and come up with innovative ideas.

10. **Promoting Environmental Consciousness**: An environmental organization wants to `encourage` people to reduce plastic usage. `instead` of promoting environmental benefits `directly`, they say, "I'm sure you won't be able to go a week without using single-use plastics." The reverse psychology `motivates` individuals to take on the `challenge` and make eco-friendly choices.

These examples illustrate various scenarios in which reverse psychology is used as a persuasive technique to influence behavior and decision-making.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Encouraging Creativity" and give me a small user story from it**

**User Story: Unleashing Creative Potential**

As a teacher, I aim to nurture creativity in my students and foster a classroom environment where innovative ideas flourish. One day, during an art class, I notice some students hesitating to express themselves freely and fear making mistakes. `To inspire` their creativity, I decide to employ reverse psychology.

With a smile, I say to the class, "I don't think you can create anything truly unique and imaginative. It's quite challenging, you know." The reverse psychology ignites a spark of determination in the students. They take it as a friendly `challenge` and become eager to prove their creative prowess.

Seeing their newfound enthusiasm, I `encourage` them to experiment fearlessly, break free from self-imposed limitations, and embrace the joy of exploration. By using reverse psychology, I empower my students to overcome their inhibitions and embrace their imaginative potential, ultimately leading to a classroom filled with innovative artwork and a sense of artistic confidence among the students.

***We can now derive CQs from the user story***

* CQ1: How do external factors influence decision-making processes in the presence of multiple options?
* CQ2: What are some effective strategies to counteract the influence of external cues and maintain rational decision-making?
* CQ3: In what ways do contextual cues impact an individual's perception of value and attractiveness among available choices?
* CQ4: How does the presence of additional options influence decision-making and alter individuals' preferences among the original choices?
---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Decoy effect", what classes and properties would you create?**

**Classes:**

1. **ReversePsychology:** Represents the concept of using reverse psychology as a psychological technique for persuasion or influence.
2. **Individual:** Represents a person or individual who is the target of the reverse psychology technique.
3. **Motivation:** Represents the underlying motivation or desired response that the reverse psychology aims to evoke in the individual.
4. **Context:** Represents the situation, scenario, or context in which the reverse psychology technique is employed.

**Properties:**

1. **employsReversePsychology:** Relates an Individual to the ReversePsychology class, indicating that they are using or applying the reverse psychology technique.
2. **targetsIndividual:** Relates the ReversePsychology to the targeted Individual, representing who the technique is aimed at influencing.
3. **aimsToEvoke:** Relates the ReversePsychology to the Motivation class, indicating the desired response or behavior the technique seeks to elicit.
4. **occursInContext:** Relates the ReversePsychology to the Context class, representing the situation or scenario in which the technique is employed.

These classes and properties will enable us to represent and reason about the concept of reverse psychology and its application in various scenarios, contexts, and motivations. By utilizing this ontology, we can better understand how reverse psychology influences decision-making and behavior in different situations.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

**Example 1: Parenting Strategy**

Entities: Parent (Individual), Child (Individual), Bedtime Routine (Context)
Classes: Individual, ReversePsychology, Motivation, Context
Properties: employsReversePsychology (relates Parent to ReversePsychology), targetsIndividual (relates ReversePsychology to Child), aimsToEvoke (relates ReversePsychology to Motivation), occursInContext (relates ReversePsychology to Bedtime Routine)

Description: A parent wants their child to willingly go to bed on time. Employing reverse psychology, the parent tells the child, "I bet you can't stay up past 9:00 PM." The ReversePsychology ontology represents the parent (Individual) using the reverse psychology technique (employsReversePsychology) targeting the child (targetsIndividual). The desired motivation (aimsToEvoke) is for the child to prove they can stay up late, leading them to willingly go to bed on time. The context (occursInContext) is the bedtime routine.

**Example 2: Sales and Persuasion**

Entities: Salesperson (Individual), Customer (Individual), Product Promotion (Context)
Classes: Individual, ReversePsychology, Motivation, Context
Properties: employsReversePsychology (relates Salesperson to ReversePsychology), targetsIndividual (relates ReversePsychology to Customer), aimsToEvoke (relates ReversePsychology to Motivation), occursInContext (relates ReversePsychology to Product Promotion)

Description: A salesperson wants to persuade a customer to make a purchase. Using reverse psychology, the salesperson says, "I'm not sure if this product is right for you; it might be too advanced." The ReversePsychology ontology represents the salesperson (Individual) applying the reverse psychology technique (employsReversePsychology) targeting the customer (targetsIndividual). The desired motivation (aimsToEvoke) is for the customer to prove they can handle the product, which may encourage them to make the purchase. The context (occursInContext) is the product promotion.

**Example 3: Classroom Motivation**

Entities: Teacher (Individual), Students (Group), Art Class (Context)
Classes: Individual, ReversePsychology, Motivation, Context
Properties: employsReversePsychology (relates Teacher to ReversePsychology), targetsIndividual (relates ReversePsychology to Students), aimsToEvoke (relates ReversePsychology to Motivation), occursInContext (relates ReversePsychology to Art Class)

Description: A teacher wants to inspire creativity and artistic expression in their students during an art class. Using reverse psychology, the teacher says, "Creating something truly unique and imaginative is quite challenging." The ReversePsychology ontology represents the teacher (Individual) employing the reverse psychology technique (employsReversePsychology) targeting the students (targetsIndividual). The desired motivation (aimsToEvoke) is to encourage the students to prove their creative abilities, leading to more imaginative artwork. The context (occursInContext) is the art class.

These examples demonstrate how the "Reverse Psychology" ontology can be applied to different scenarios involving individuals using the reverse psychology technique to influence others' behavior or decision-making in various contexts.