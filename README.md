# 🧠 Modeling Cognitive Biases

The aim of our project is to model two biases taken from the classification made by Buster Benson, posted at this [link on Medium.](https://betterhumans.pub/cognitive-bias-cheat-sheet-55a472476b18)

A visualization of the cognitive bias cheat sheet has been provided by [John Manoogian III.](https://medium.com/@jm3)

![Cognitive Biases Codex](./documentation/img/cognitive-biases-codex-2016.png) 

The list is composed of 20 unique biased mental strategies that we use for specific reasons.
These 20 biases are gruoped by the general mental problem they attempt to address, which are: "What should we remember?"; "Too much information"; "Not enough meaning"; "Need to act fast".

In particular, we will focus on two biases respectly from the two mental problems "Need to act fast" and "Not enough meaning". They are:

1. **To avoid mistakes, we aim to preserve autonomy and group status and avoid irreversible decisions**

This includes:
- Status quo bias
- Social comparison bias
- Decoy effect
- Reverse psychology
- Reactance
- System justification

2. **We fill in characteristics from stereotypes, generalities, and prior histories**

This includes:
- Gruop attribution error
- Ultimate atribution  error
- Stereotyping
- Essentialism 
- Functional fixedness
- Moral credential effect
- Just-world hypothesis
- Argument from fallacy
- Authority bias
- Automation bias
- Bandwagon effect
- Placebo effect

## 📚 Methodology

Our final goal is modeling the biases presented above and create an onology for semantic web technologies using a specific iterative method for pattern-based onoltogy design, called **eXtreme Design.**
With the name eXtreme Design (XD), we identify an approach, a family of methods, and associated tools, based on the application, exploitation, and definition of ontology design patterns (ODPs) for solving ontology development issues.

### eXtreme Design in 4 steps:

1. Identify the requirements for the ontology design process and formulate a set of competency questions (CQ) that the ontology should be able to answer.

2. Assess whether existing Ontology Design Patterns (ODPs) from the Content ODPs repository2 meet the modeling requirements and can be reused.

3. Validate the ontology modules through error provocation, inference testing, and validation for each module in the ontology network.

4. Integrate the modeled and tested ontologies into a closure module and populate them with domain entities from knowledge graphs.

### CLOWN Modeling framework

The CLOWN Modeling framework is a framework that can be used in conjunction with the eXtreme Design (XD) methodology for ontology development. It provides a structured approach to modeling ontologies by incorporating various components. Let's break down the different components of the CLOWN Modeling framework:

1. Context and Literature State of the Art:
This component involves understanding the context and conducting a comprehensive review of the existing literature related to the domain you are working with. This step helps establish a solid foundation of knowledge and ensures that your ontology is aligned with current understanding and research in the field.

2. Large Language Models:
Large Language Models (LLMs) refer to powerful natural language processing models like GPT-3.5, which have the ability to generate human-like text. LLMs can be leveraged to assist in ontology development by providing suggestions, generating ontological elements, or aiding in the extraction of relevant information from textual sources.

3. Ontology Design Patterns:
Ontology Design Patterns (ODPs) are reusable modeling solutions for common ontology development challenges. ODPs capture best practices and provide a structured approach to representing specific concepts, relationships, or patterns within an ontology. They help ensure consistency and interoperability across ontologies.

4. Words as Frame Semantic Triggers:
This component suggests using words or terms as triggers for frame semantics. Frames refer to structured representations of knowledge that capture concepts, attributes, and relationships within a specific domain. By identifying specific words or terms, you can map them to corresponding frames and create a more semantically rich ontology.

5. New Modules Integration and Alignment:
This component focuses on integrating newly created ontology modules and aligning them with existing modules or ontologies. As you develop different parts of your ontology, it's important to ensure coherence and compatibility between the modules. This step facilitates the integration of new knowledge while maintaining consistency within the overall ontology structure.

## 🧗‍♂️ Workflow

1. Start by familiarizing yourself with the context and conducting a literature review to understand the domain you are working with.

2. Leverage large language models to assist in ontology development, such as generating suggestions or extracting relevant information from textual sources.

3. Identify and utilize existing ontology design patterns (ODPs) that align with your modeling requirements. These patterns provide guidance and promote consistency.

4. Identify specific words or terms that can serve as triggers for frame semantics, allowing you to map them to relevant frames within your ontology.

5. Integrate newly created ontology modules into the overall structure and ensure alignment and compatibility with existing modules or ontologies.

By incorporating the CLOWN Modeling framework into the XD methodology, we can benefit from a structured approach to ontology development that leverages existing knowledge, ontology design patterns, and semantic triggers, ultimately leading to a well-designed and coherent ontology.

## 🛠️ Tools

For reach our goal we will use the following technologies:

* ChatGPT:
https://chat.openai.com

* Quokka Concepts:
http://etna.istc.cnr.it/quokka/concepts

* Quokka Frames:
http://etna.istc.cnr.it/quokka/frames

* FRED: 
http://wit.istc.cnr.it/stlab-tools/fred/demo/

* Framester endpoint:
http://etna.istc.cnr.it/framester2/sparql

* Protégé:
https://protege.stanford.edu