# Reactance

## 1. Context and Literature State of the Art

**Wikipedia:**
In psychology, reactance is an unpleasant motivational reaction to offers, persons, rules, or regulations that threaten or eliminate specific behavioral freedoms. Reactance occurs when an individual feels that an agent is attempting to limit one's choice of response and/or range of alternatives.

Reactance can occur when someone is heavily pressured into accepting a certain view or attitude. Reactance can encourage an individual to adopt or strengthen a view or attitude which is indeed contrary to that which was intended — which is to say, to a response of noncompliance — and can also increase resistance to persuasion. Some individuals might employ reverse psychology in a bid to exploit reactance for their benefit, in an attempt to influence someone to choose the opposite of what is being requested. Reactance can occur when an individual senses that someone is trying to compel them to do something; often the individual will offer resistance and attempt to extricate themselves from the situation.

Some individuals are naturally high in reactance, a personality characteristic called trait reactance. [Wikipedia Link](https://en.wikipedia.org/wiki/Reactance_(psychology))

**Reasearch paper:**
[Miron, Anca & Brehm, Jack. (2006). Reactance Theory - 40 Years Later. Zeitschrift Fur Sozialpsychologie - Z SOZPSYCHOL. 37. 9-18. 10.1024/0044-3514.37.1.9.](https://www.researchgate.net/publication/240218056_Reactance_Theory_-_40_Years_Later)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Reactance"**

Reactance is a psychological phenomenon that occurs when individuals feel their `freedom` or autonomy is being threatened or restricted. When faced with attempts to control or `limit` their choices, people may experience a negative emotional response characterized by resistance, defiance, or a desire to restore their sense of `freedom`. Reactance is a defensive `reaction` aimed at reasserting one's independence and autonomy in the face of perceived `constraints` or attempts to manipulate behavior. This phenomenon can lead individuals to act in opposition to the imposed influence or persuasion, even if the original request aligns with their own best interests.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Reverse psychology"**

1. **Teenage Rebellion:** A teenager's parents impose strict rules and curfews on them, leading the teen to feel their freedom is being `restricted`. In response to this perceived `control`, the teenager may engage in `rebellious` behavior, staying out later than allowed or engaging in activities explicitly prohibited by their parents.

2. **Workplace Micromanagement** An employee feels micromanaged by their supervisor, who closely monitors every task and decision. This level of supervision triggers feelings of reactance in the employee, causing them to `resist` the excessive `control` by seeking more `autonomy` or even considering job opportunities elsewhere.

3. **Parental Instructions:** A child is given precise instructions on how to play with a new toy, leaving no room for personal exploration or creativity. The child may `resist` following the instructions and instead opt for `alternative` ways of playing to assert their `independence`.

4. **Advertising Overload:** A consumer encounters a constant bombardment of advertisements on social media and other platforms. The `overwhelming` presence of ads may trigger reactance, leading the consumer to ignore or actively `avoid` the advertised products.

5. **Banning Certain Content:** A school or organization bans access to certain websites or content deemed inappropriate. Instead of complying, individuals may feel motivated to find `alternative` ways to access the `restricted` content, driven by a desire to regain `control` over their choices.

6. **Relationship Pressure:** Friends or family members put `pressure` on someone to enter into a romantic relationship or marry, but the individual feels uncomfortable with the idea. The `pressure` may lead to reactance, causing the person to assert their right to make their own decisions about relationships.

7. **Government Mandates:** The government enforces new regulations or mandates that some citizens view as infringing upon their individual rights. In response, there may be protests or `resistance` to assert personal freedoms and `autonomy`.

8. **Health Recommendations:** A person is given specific health recommendations by their doctor, but they feel their `autonomy` is being challenged. As a result, they may be less motivated to follow the advice, even if it is beneficial for their well-being.

9. **Social Expectations:** A person is expected to conform to certain social norms or expectations, such as dress code or behavior, but they feel `restricted` by these norms. They may respond by purposely deviating from the norms to assert their `independence`.

10. **Academic Pressure:** Students face intense academic `pressure` from their parents or teachers to excel in certain subjects. This `pressure` may trigger reactance, causing students to `resist` or underperform in those subjects as a way of reclaiming `control` over their own academic choices.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Advertising Overload" and give me a small user story from it**

**User Story: Resisting Advertising Overload**

As a social media user, I find myself bombarded with a constant stream of advertisements and sponsored content while scrolling through my feed. Recently, I've become increasingly frustrated with the `overwhelming` advertising `overload` that interrupts my online experience.

One day, as I browse my favorite social media platform, I come across yet another intrusive ad that disrupts the flow of content I enjoy. Feeling a sense of reactance, I decide to take action against this advertising `overload`.

Motivated to regain control over my online experience, I actively search for ad-blocker tools and extensions. By installing these tools, I successfully eliminate the intrusive advertisements from my feed. As a result, my online browsing becomes more enjoyable, and I feel empowered to make decisions about the content I want to engage with.

Embracing my newfound `autonomy`, I also share my experience with friends and online communities, encouraging them to explore ad-blocking options as well. This collective reaction to advertising `overload` generates conversations about online user rights and the importance of preserving a seamless and personalized digital experience.

With a sense of empowerment, I navigate my online space with more agency, actively `resisting` the influence of advertising `overload` and choosing the content that truly matters to me.

***We can now derive CQs from the user story***

* CQ1: What are the common factors or stimuli that trigger reactance in individuals when they perceive their freedom or autonomy is being threatened?
* CQ2: How do individuals typically respond to situations where they experience reactance, and what actions or behaviors do they engage in to assert their autonomy?
* CQ3: In what contexts or domains does reactance often manifest, and what are the underlying motivations driving individuals to resist external influence or constraints?
* CQ4: What are the potential consequences or outcomes of reactance in decision-making processes, and how does it impact the choices individuals make in response to attempts at persuasion or control?
---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Reactance", what classes and properties would you create?**

**Classes:**

1. **ReactanceBias:** Represents the concept of reactance as a psychological bias.
2. **Individual:** Represents a person or individual who experiences reactance.
3. **Stimulus:** Represents the factors, stimuli, or situations that trigger reactance in individuals.
4. **Response:** Represents the actions, behaviors, or decisions that individuals take in response to experiencing reactance.
5. **Context:** Represents the domains, situations, or contexts in which reactance often manifests.
6. **Outcome:** Represents the potential consequences or outcomes of reactance in decision-making processes.

**Properties:**

1. **experiencesReactance:** Relates an Individual to the ReactanceBias class, indicating that the individual experiences the reactance bias.
2. **triggersReactance:** Relates the Stimulus to the ReactanceBias class, representing the factors or stimuli that trigger reactance.
3. **respondsToReactance:** Relates the Individual to the Response class, indicating the actions or behaviors taken in response to experiencing reactance.
4. **occursInContext:** Relates the ReactanceBias to the Context class, representing the domains or situations in which reactance often manifests.
5. **leadsToOutcome:** Relates the ReactanceBias to the Outcome class, representing the potential consequences or outcomes of reactance in decision-making processes.

These classes and properties will enable us to represent and reason about the concept of reactance bias and its manifestations in various contexts and scenarios. By utilizing this ontology, we can gain insights into how reactance influences decision-making and behavior when individuals perceive their freedom or autonomy is being threatened or restricted.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

**Example 1: Social Media Overload**

Entities: Sarah (Individual), Social Media Ads (Stimulus), Decision to Install Ad-Blocker (Response), Online Browsing (Context), Improved User Experience (Outcome)

Classes: ReactanceBias, Individual, Stimulus, Response, Context, Outcome

Properties:
- Sarah experiencesReactance ReactanceBias (true)
- Social Media Ads triggersReactance ReactanceBias
- Sarah respondsToReactance Decision to Install Ad-Blocker
- ReactanceBias occursInContext Online Browsing
- ReactanceBias leadsToOutcome Improved User Experience

Description: Sarah, an Individual, experiences reactance (ReactanceBias) due to the constant bombardment of social media ads (Social Media Ads). In response to this advertising overload, Sarah decides to install an ad-blocker on her browser (Decision to Install Ad-Blocker) as a way to regain control over her online experience. This decision is made within the context of her online browsing (Online Browsing) and leads to an improved user experience (Improved User Experience) with fewer intrusive ads.

**Example 2: Parent-Child Interaction**

Entities: Parent (Individual), Child (Individual), Imposed Curfew (Stimulus), Child's Rebellion (Response), Home Environment (Context), Altered Curfew Arrangement (Outcome)

Classes: ReactanceBias, Individual, Stimulus, Response, Context, Outcome

Properties:
- Child experiencesReactance ReactanceBias (true)
- Imposed Curfew triggersReactance ReactanceBias
- Child respondsToReactance Child's Rebellion
- ReactanceBias occursInContext Home Environment
- ReactanceBias leadsToOutcome Altered Curfew Arrangement

Description: The parent (Individual) imposes a strict curfew (Imposed Curfew) on their child (Child), causing the child to experience reactance (ReactanceBias). In response to this restriction, the child rebels by staying out later than the curfew allows (Child's Rebellion). The parent recognizes the child's reaction and engages in a dialogue, leading to an altered curfew arrangement (Altered Curfew Arrangement) that provides the child with more autonomy. This adjustment in rules is made within the context of their home environment (Home Environment) to address the reactance experienced by the child.

**Example 3: Sales Tactics**

Entities: Customer (Individual), Sales Pitch (Stimulus), Refusal to Purchase (Response), Retail Store (Context), Reduced Sales Revenue (Outcome)

Classes: ReactanceBias, Individual, Stimulus, Response, Context, Outcome

Properties:
- Customer experiencesReactance ReactanceBias (true)
- Sales Pitch triggersReactance ReactanceBias
- Customer respondsToReactance Refusal to Purchase
- ReactanceBias occursInContext Retail Store
- ReactanceBias leadsToOutcome Reduced Sales Revenue

Description: A customer (Individual) visits a retail store and is exposed to an aggressive sales pitch (Sales Pitch), leading to the experience of reactance (ReactanceBias). In response to this sales tactic, the customer chooses to refuse the purchase (Refusal to Purchase). As a consequence of this negative experience, the customer may decide to avoid returning to the store, potentially leading to reduced sales revenue for the retail store (Reduced Sales Revenue). The context for this scenario is within the retail store setting (Retail Store), where the reactance bias can manifest in response to pushy sales tactics.