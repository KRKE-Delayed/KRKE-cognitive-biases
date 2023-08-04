## Project Documentation: Modeling Cognitive Biases with eXtreme Design

This comprehensive project documentation delineates all the crucial phases involved in modeling two clusters of biases and creating a task-specific Application Ontology for semantic web technologies. Our ontology design method of choice is the pattern-based approach known as 'eXtreme Design.'

The ontology we aim to develop is tailored as an Application Ontology, meticulously focused on addressing the specific task and domain at hand.

In this project, we adopt a hybrid methodology that incorporates both top-down and text-driven approaches. Initially, we employ a top-down approach to understand and define the Universe of Discourse. Additionally, we leverage powerful tools like QUOKKA and FRED to enhance knowledge extraction from textual sources, enabling us to enrich and validate the ontology with valuable insights derived from the text. This combined methodology ensures a robust and comprehensive ontology that is driven by both theoretical conceptualization and empirical data.

## 1. Context and Literature State of the Art

In the initial step of the XD methodology, we diligently explore the domain of biases by leveraging various valuable resources. We start by referring to Wikipedia to gain a foundational understanding and precise definition of the biases under investigation. Additionally, we conduct an in-depth review of research papers related to the topic, which provides us with insights from scholarly works and the latest advancements in the field.

Moreover, to augment our knowledge exploration process, we integrate the expertise of ChatGPT, a powerful language model capable of generating human-like text and providing valuable insights. While we substitute traditional domain experts with these intelligent tools, we ensure that the information we acquire is reliable, relevant, and up-to-date. This comprehensive approach enables us to lay a solid foundation for our ontology, ensuring its alignment with the state-of-the-art knowledge in the domain of biases and semantic web technologies.

## 2. Large Language Models (LLMs)

Leveraging the power of natural language processing models like ChatGPT-3.5, we can generate human-like text and extract important information. LLMs play a significant role in ontology development, providing suggestions, generating ontological elements, and aiding in the extraction of relevant information from textual sources.

We extract Lexical Units from the textual contents, which will be utilized to find semantic frames in Framester. As part of the XD procedure, we create Competency Questions (CQs) from the scenarios provided by ChatGPT. Analyzing these CQs helps us identify classes and properties restrictions needed to answer them effectively. Whenever we encounter modeling challenges, we can refer to Ontology Design Patterns for potential solutions.

## 3. Ontology Design Patterns

This step involves exploring and utilizing existing Ontology Design Patterns (ODPs) to address common ontology development issues. By leveraging ODPs, we can ensure consistency, reusability, and adopt best practices in our ontology.

During our research, we have developed a set of content ontology design patterns (Content ODPs), aimed at solving small design problems (modules) within an ontology. This means that the patterns themselves are small ontologies, accompanied by additional annotations that describe them, such as the general requirements each pattern fulfills (usually expressed in the form of Competency Questions).

As a primary modeling issue, we need to represent agents who perform the actions and experience each cognitive bias. To achieve this, we imported the **[AgentRole CPs](http://ontologydesignpatterns.org/wiki/Submissions:AgentRole)**, which addresses the competency questions: ***Which agent does play this role?*** and ***What is the role that played by that agent?***
Enriching our knowledge base with the concept of DecisionMaker, which represents the role of an agent who performs the bias, we defined DecisionMaker as a subclass of Role, and Person and Organization as subclasses of Agent.

Given that cognitive biases are cognitive solutions we apply to interpret the world and address specific problems, it is essential to consider the concept of *consequence*, as there is usually a before and after a bias is applied. To model this event sequence, we found the **[Sequence CPs](http://ontologydesignpatterns.org/wiki/Submissions:Sequence)**, which answers the competency questions: ***What is before what? What's next?*** and ***What's immediately following this?***

Another critical modeling issue is that biases are applied to real-world situations, suggesting the utility of a CPs that describes contexts or situations. We discovered the **[Situation CPs](http://ontologydesignpatterns.org/wiki/Submissions:Situation)** that addresses the competency questions: ***What is the context or situation of something?*** and ***What are the things present in this context or situation?***

As a result, we can now infer the relationship between "Situation" and "CognitiveBias" by using the "precedes" relation, signifying that the situation comes before the cognitive bias.

## 4. Words as Frame Semantic Triggers

To enhance the alignment of our domain of discourse with existing semantic frames, we leverage powerful knowledge extraction tools like FRED and QUOKKA. With FRED, we conduct a thorough analysis of our scenarios and examine the resulting knowledge graph it generates. Additionally, through the QUOKKA tool's "Concepts Extractor" feature, we actively search for Lexical Units (words) that were prominently highlighted during our comprehensive exploration of the biases. By doing so, we can efficiently identify and integrate pertinent frames from the extensive Framester repository. These invaluable tools play a pivotal role in our ontology development process, empowering us to enrich the ontology with relevant semantic frames and ensuring a more comprehensive and robust representation of the biases within our domain of interest.

## 5. Ontology Design with Protégé

In this final step, we utilize Protégé to model our OWL ontology and visualize the structure we have constructed. Our approach involves treating biases as complex situations that can be composed of simpler ones. To begin, we employ QUOKKA to analyze the frames evoked by the lexical units used to describe the various biases. These results are then compared with the definitions of the biases provided by ChatGPT, aiding us in identifying the specific frames required to accurately represent each bias.

For our ontology design, we consider biases as classes of situations, enabling us to effectively represent them using existing frames. By applying boolean reasoning, we can handle intersections and unions, allowing for a more nuanced representation. This reasoning process can be executed through either a top-down approach or by starting directly from textual descriptions, as we do with FRED and QUOKKA. Throughout the ontology creation process, we maintain an iterative and guided methodology, driven by the understanding that biases can be effectively modeled as compositions of existing situations found in the real world.


