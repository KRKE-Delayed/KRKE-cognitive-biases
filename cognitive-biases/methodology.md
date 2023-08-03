# Project Documentation

This project documentation outlines all the phases involved in modeling two clusters of biases and creating an ontology for semantic web technologies using the pattern-based ontology design method called 'eXtreme Design'.

## 1. Context and Literature State of the Art

To ensure that our ontology aligns with the current understanding and research in the field, we provide a Wikipedia definition of the biases and include links to relevant research papers on the topic.

## 2. Large Language Models (LLMs)

Leveraging the power of natural language processing models like ChatGPT-3.5, we can generate human-like text and extract important information. LLMs play a significant role in ontology development, providing suggestions, generating ontological elements, and aiding in the extraction of relevant information from textual sources.

We extract Lexical Units from the textual contents, which will be utilized to find semantic frames in Framester. As part of the XD procedure, we create Competency Questions (CQs) from the scenarios provided by ChatGPT. Analyzing these CQs helps us identify classes and properties restrictions needed to answer them effectively. Whenever we encounter modeling challenges, we can refer to Ontology Design Patterns for potential solutions.

## 3. Ontology Design Patterns

This step involves exploring and utilizing existing Ontology Design Patterns (ODPs) to address common ontology development issues. By leveraging ODPs, we can ensure consistency, reusability, and best practices in our ontology.

## 4. Words as Frame Semantic Triggers

To further align our domain of discourse with existing semantic frames, we use tools for knowledge extraction such as FRED or QUOKKA. In FRED, we analyze our CQs and observe the knowledge graph it generates. Alternatively, using the QUOKKA tool "Concepts Extractor," we search for Lexical Units (words) that we highlighted during the exploration of the biases and identify relevant frames from Framester.

## 5. Ontology Visualization with Protégé

In the final step, we model our OWL ontology in Protégé and visualize it. We treat biases as complex situations composed of simpler ones. Starting with QUOKKA, we analyze the frames evoked by the lexical units used to describe the biases. We compare these results with the definitions of the biases provided by ChatGPT to identify the necessary frames to describe each bias. By defining biases as classes of situations, we can represent them using existing frames, considering intersections and unions through boolean reasoning. This can be accomplished top-down or by starting from text, as we do with FRED and QUOKKA. The ontology creation process is iterative and guided by the understanding of biases as compositions of existing situations in the world.