# Social Comparison Bias

*## CLUSTER: To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions*

## 1. Context and Literature State of the Art

**Wikipedia:**
Social comparison bias is the tendency to have feelings of dislike and competitiveness with someone seen as physically, socially, or mentally better than oneself. Social comparison bias or social comparison theory is the idea that individuals determine their own worth based on how they compare to others.[…] This can be compared to social comparison, which is believed to be central to achievement motivation, feelings of injustice, depression, jealousy , and people's willingness to remain in relationships or jobs. The basis of the theory is that people are believed to compete for the best outcome in relation to their peers. For example, one might make a comparison between the low-end department stores they go to frequently and the designer stores of their peers. Such comparisons may evoke feelings of resentment, anger, and envy with their peers. This bias revolves mostly around wealth and social status; it is unconscious and people who make these are largely unaware of them. In most cases, people try to compare themselves to those in their peer group or with whom they are similar. [Wikipedia Link](https://en.wikipedia.org/wiki/Social_comparison_bias)

**Reasearch paper:**
[Garcia, S.M., Song, H., Tesser, A., 2010. Tainted recommendations: the social comparison bias. Organ. Behav. Hum. Decis. Process. 113, 97–101.](https://www.researchgate.net/publication/227419119_Tainted_recommendations_The_social_comparison_bias)

---

## 2. Large Language Models (LLMs)

***2.1 - Let's ask ChatGPT for a generic definition, just to get an idea of the domain.***

**Give me a definition of "Social comparison bias"**

"Social Comparison Bias" refers to a cognitive bias in which individuals tend to `evaluate` themselves and their abilities by `comparing` themselves to others. This bias often involves the tendency to make upward social comparisons, where individuals compare themselves to others they perceive as `superior` in certain aspects. As a result, individuals may feel `inadequate` or dissatisfied with their own abilities or achievements when they perceive others as more `successful` or accomplished.

The Social Comparison Bias can influence various aspects of an individual's life, including `self-esteem`, motivation, and `decision-making`. It can lead to feelings of envy, competition, or self-doubt, as individuals strive to `measure up` to the perceived standards set by others.

This bias is particularly prevalent in today's interconnected world, where social media and constant exposure to others' achievements can amplify the `comparison` process. Understanding and addressing the Social Comparison Bias can be crucial for promoting healthy self-perception and fostering a positive and supportive social environment.

---

***2.2 - Let's ask to give us some examples of possible scenarios to better understand the context***

**Give me 10 example scenarios of "Social comparison bias"**

1. **Academic Achievement:** Alice, a student, feels `demotivated` and `discouraged` after `comparing` her grades to those of her classmates. Despite achieving good grades, she constantly compares herself to the `top-performing` students, leading her to doubt her academic `abilities`.

2. **Career Advancement:** Bob, a young professional, constantly `compares` his career progress to that of his colleagues. When he sees his `peers` receiving promotions or recognition, he feels dissatisfied with his own career growth, even if he is doing well in his job.

3. **Social Media Influence:** Clara spends hours scrolling through social media, `comparing` her life to carefully curated posts of her friends. She often `feels inadequate` and envious of the seemingly perfect lives displayed by others on social media.

4. **Physical Appearance:** Daniel `compares` his body image to fitness influencers and models, leading him to develop a negative `self-image` and unrealistic body standards.

5. **Material Possessions:** Emily becomes discontent with her belongings after `comparing` them to the luxurious possessions of her neighbors. She feels a constant need to acquire more to `match` their lifestyle.

6. **Personal Achievements:** Greg, an artist, feels `demoralized` when he `compares` his artistic skills to those of renowned artists. He struggles with feelings of inadequacy despite his own unique talents.

7. **Relationship Status:** Hannah feels pressure to find a partner after `comparing` herself to her friends who are in committed relationships. She fears being judged and views her single status `negatively`.

8. **Parenting Skills:** Ian, a new parent, becomes `anxious` when `comparing` his parenting approach to other parents. He worries that he is not doing as well as they are, despite the uniqueness of each child and parenting journey.

9. **Financial Success:** Jack `feels unsatisfied` with his financial situation after `comparing` his income and possessions to those of wealthier friends. He neglects his own financial achievements and progress.

10. **Athletic Abilities:** Katie, an amateur athlete, becomes `disheartened` when she `compares` her sports `performance` to that of professional athletes. She `underestimates` her own progress and dedication.

These scenarios demonstrate how the Social Comparison Bias can manifest in various aspects of life and how it can influence individuals' perceptions, emotions, and behaviors. It is important to be aware of this bias and its effects, as it can impact mental well-being and lead to unnecessary stress and dissatisfaction.

---

***2.3 - Let's ask for some user story and competency questions***

**Consider the scenario "Social Media Influence" and give me a small user story from it**

**User Story: Breaking Free from Social Media Comparison**

As an artist sharing my work on social media, I often find myself `comparing` my journey to others, leading to `self-doubt` and `discouragement`. One day, I come across an inspiring post from a fellow artist, Alex, celebrating their growth and `resilience`. Instead of `feeling envious`, I feel motivated by their story. I reach out, sparking a positive exchange that encourages other artists to embrace their uniqueness. Together, we create #ArtBeyondComparison, a supportive space that celebrates diverse artistic expressions. The movement grows, inspiring artists of all skill levels to share their work confidently, free from the trap of comparison.

***We can now derive CQs from the user story***

* CQ1: How do individuals perceive and experience the impact of social comparison in various aspects of their lives?
* CQ2: What are the common emotions and reactions triggered by social comparison situations?
* CQ3: In what ways does social comparison influence individuals' self-esteem and self-worth?
* CQ4: How do people cope with feelings of inadequacy or dissatisfaction arising from social comparison?

---

***2.4 - Let's now ask about modeling this bias for an ontology***

**If you should make an ontology of the "Social comparison bias", what classes and properties would you create?**

**Classes:**

1. **SocialComparisonBias:** The main class representing the Social Comparison Bias itself.
2. **Individual:** Represents individuals who engage in social comparison behaviors.
3. **Context:** Represents the situations or contexts in which social comparison occurs (e.g., academic, professional, appearance).
4. **Emotion:** Represents the emotions triggered by social comparison, such as envy, dissatisfaction, or inspiration.
5. **Self-Esteem:** Represents an individual's self-esteem level, which may be influenced by social comparison.
6. **Decision:** Represents the decisions or actions taken by individuals influenced by social comparison.
7. **CopingStrategy:** Represents the strategies individuals employ to cope with negative emotions arising from social comparison.

**Properties:**

1. **hasSocialComparisonBias:** Indicates that an individual is influenced by the Social Comparison Bias.
2. **occursInContext:** Relates the SocialComparisonBias to specific contexts in which social comparison is observed.
3. **triggersEmotion:** Relates social comparison to the emotions it may trigger in individuals.
4. **influencesSelfEsteem:** Indicates that social comparison can influence an individual's self-esteem.
5. **leadsToDecision:** Relates social comparison to the decisions or actions it may lead individuals to take.
6. **employsCopingStrategy:** Relates an individual to coping strategies they use in response to social comparison.

---

***2.5 - Let's ask for some example of usage of the ontology***

**Can you give me three examples of usage of this classes and properties?**

*Example 1: Fashion Choices and Social Comparison*

Entities: Emily (Individual), Fashion Bloggers (Group)
Classes: Individual, SocialComparisonBias, Context
Properties: hasSocialComparisonBias true (for Emily), occursInContext (relates Emily to Fashion Bloggers)

Description: Emily follows various fashion bloggers on social media and often finds herself comparing her fashion choices to those of the influencers she follows. This social comparison triggers feelings of self-doubt and influences her clothing decisions. The ontology can represent Emily as an Individual with the SocialComparisonBias (hasSocialComparisonBias true). It can also capture the context of comparison as "Fashion Bloggers" (Context class) that occurs in Emily's social media interactions (occursInContext).

*Example 2: Academic Achievements and Peer Comparison*

Entities: Alex (Student), Classroom Environment (Context)
Classes: Student, SocialComparisonBias, Context
Properties: hasSocialComparisonBias true (for Alex), occursInContext (relates Alex to Classroom Environment)

Description: Alex is a student in a highly competitive classroom environment, where academic achievements are frequently compared among peers. The pressure to perform well triggers feelings of stress and influences Alex's study habits. The ontology can represent Alex as a Student with the SocialComparisonBias (hasSocialComparisonBias true). It can also capture the context of comparison as "Classroom Environment" (Context class) where academic achievements are frequently compared (occursInContext).

*Example 3: Career Choices and Social Media Influence*

Entities: Sarah (Individual), Career Influencers (Group)
Classes: Individual, SocialComparisonBias, Context
Properties: hasSocialComparisonBias true (for Sarah), occursInContext (relates Sarah to Career Influencers)

Description: Sarah is a young professional who often compares her career choices to those of influential figures she follows on social media. This constant social comparison affects her decision-making and causes moments of uncertainty about her career path. The ontology can represent Sarah as an Individual with the SocialComparisonBias (hasSocialComparisonBias true). It can also capture the context of comparison as "Career Influencers" (Context class) that occurs in Sarah's social media experiences (occursInContext).

In these examples, the ontology's classes and properties are utilized to represent individuals' engagement in social comparison and the contexts in which the comparisons occur. The use of relationships between entities and classes helps to identify how the Social Comparison Bias influences emotions and decision-making processes in different domains of life.