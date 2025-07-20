# Strategies for Developing Ontologies
{: .hidden-title }

There are several approaches to building ontologies, each with its own advantages and challenges. The top-down approach starts with broad concepts and gradually breaks them down into more specific classes and relationships. This method often relies on competency questions to guide development and ensure the ontology meets its intended purpose (Noy and McGuinness, 2001). It works well when the domain is well understood and expert knowledge is available, though it can be time-consuming and less flexible during early stages.

In contrast, the bottom-up approach constructs the ontology from existing data sources like knowledge graphs or databases. This can be faster and better suited for large datasets but may result in less consistent or clear conceptual models without careful review (Noy and McGuinness, 2001).

A more recent hybrid approach, discussed by Ciroku et al. (2024), combines these methods by using language models to generate competency questions from knowledge graphs. This allows for scalable and automated ontology development, especially in data-rich environments like Wikidata. However, it still requires human oversight to validate and refine the results.

Ultimately, the choice of method depends on the domain and goals. Well-defined domains may benefit from a top-down approach, while dynamic or data-driven areas might be better served by bottom-up or hybrid strategies. Finding the right balance is essential to creating useful and maintainable ontologies.

### References

Ciroku, F. et al. (2024) ‘RevOnt: Reverse engineering of competency questions from knowledge graphs via language models’, Journal of Web Semantics, 82, p. 100822. Available at: https://doi.org/10.1016/j.websem.2024.100822.

Noy, N.F. and McGuinness, D.L., 2001. Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory. Available at: https://protege.stanford.edu/publications/ontology_development/ontology101.pdf

[Back to Knowledge Representation and Reasoning](/krr)