# Collaborative Discussion 2: Exploring Ontologies and Their Representation Languages
{: .hidden-title }

## Brief

In this activity, I explored Chapter 2 of Nasim, T.M. (2022), alongside other relevant sections of the thesis, to deepen my understanding of ontologies and their applications. The focus was to examine how ontology is defined within the thesis context and to evaluate which ontology representation language, KIF, OWL2, RDF, or OWL-lite, is most effective for use by software agents on the World Wide Web. This reflection aims to connect theoretical definitions with practical considerations in ontology language selection.

## Navigation
- [Initial Post](#initial-post)
  - [Peer Response 1](#peer-response-1)
  - [Peer Response 2](#peer-response-2)
- [Summary Post](#summary-post)
- [Back to Knowledge Representation and Reasoning](/krr)


## Initial Post

In this thesis by Nasim (2022), an ontology is defined as a set of structural rules that represent concepts in a way that allows machines to perform logic-based operations. It’s described as a “formal, explicit specification of shared conceptualization” (Guarino, Oberle and Staab, 2009, cited in Nasim, 2022, p.9). That means it's a structured way to model knowledge, allowing it to be shared and reused by both people and computer systems. Ontologies include classes, properties and individuals, which can be thought of as specific instances of a modelled concept, for example, an instance of a class Person named Bob.

The main purpose of an ontology, according to the thesis, is to organise knowledge and enable systems to reason about data. This is especially important for the Semantic Web, where machines need to understand and relate information from different sources without human help (Berners-Lee, Hendler and Lassila, 2001).

Given this definition, the most suitable language for expressing ontologies on the World Wide Web is OWL 2 (Web Ontology Language 2). OWL2 is an updated and more expressive version of the original OWL and OWL-Lite. It enables rich and complex knowledge representation while remaining machine-readable and interoperable. It also supports reasoning, which is essential for tasks like ontology alignment and data integration, key topics discussed in the thesis. OWL2 is considered the “formally recommended ontology language for Semantic Web modelling” (Lawan and Rakib, 2019, p. 8).  

OWL2 strikes a good balance between expressiveness and practicality for web-based agents. That could make it a good choice for real-world applications of ontologies on the Semantic Web.


References

Berners-Lee, T., Hendler, J. and Lassila, O. (2001) ‘The Semantic Web: A New Form of Web Content That is Meaningful to Computers Will Unleash a Revolution of New Possibilities’, Scientific American [Preprint]. Available at: https://www.researchgate.net/publication/225070375_The_Semantic_Web_A_New_Form_of_Web_Content_That_is_Meaningful_to_Computers_Will_Unleash_a_Revolution_of_New_Possibilities (Accessed: 3 July 2025).

Guarino, N., Oberle, D. and Staab, S. (2009) ‘What Is an Ontology?’, in S. Staab and R. Studer (eds) Handbook on Ontologies. Berlin, Heidelberg: Springer Berlin Heidelberg, pp. 1–17. Available at: https://doi.org/10.1007/978-3-540-92673-3_0.

Lawan, A. and Rakib, A. (2019) ‘The Semantic Web Rule Language Expressiveness Extensions-A Survey’. arXiv. Available at: https://doi.org/10.48550/arXiv.1903.11723.

Nasim, T.M. (2022) Improving Ontology Alignment Using Machine Learning Techniques. M.S. Arizona State University. Available at: https://www.proquest.com/docview/2666489192/abstract/727666A2F5334B59PQ/1 (Accessed: 27 June 2025).

[Back to the top](#)

## Peer Responses

### Peer response 1

I fully agree with the definition and stance presented in your post, highlighting ontologies as structured, formal frameworks designed to represent domain-specific knowledge explicitly, enabling logic-based reasoning and inference. As you rightly referenced, ontologies constitute a “formal, explicit specification of a shared conceptualisation” (Gruber, 1993, as cited in Nasim, 2022). This conceptualisation acts as an abstract, shared model of phenomena, laying the foundation for effective semantic communication and interoperability among diverse systems and human users alike (Guarino, Oberle, and Staab, 2009).

Ontologies systematically organise domain knowledge through the precise definition of classes, properties, and individuals. Classes represent general concepts, properties describe the relationships and attributes, and individuals instantiate specific occurrences of these concepts. This structural clarity significantly facilitates both knowledge sharing and automated reasoning, fundamental for realising the vision of the Semantic Web (Bernstein et al., 2016, cited in Nasim, 2022).

Your stance on OWL2 as the most suitable language for semantic web ontologies is equally justified. OWL2, a W3C-endorsed standard grounded in Description Logics, balances expressive power with computational practicality. Its compatibility with RDF enhances interoperability and enables powerful, decidable reasoning capabilities, essential for tasks like ontology alignment, data integration, and semantic web applications such as DBpedia (Nasim, 2022; UoEO, n.d.). Thus, OWL2 emerges clearly as the most robust, interoperable, and widely adopted language, ensuring effective, scalable semantic modelling across web-based platforms.

References

Guarino, N., Oberle, D. and Staab, S. (2009). Handbook on Ontologies. Springer, Berlin.

Nasim, T. M. (2022). Improving Ontology Alignment Using Machine Learning Techniques. ProQuest Dissertations & Theses.

UoEO (n.d.). Lecturecast, Module 4 Knowledge Representation and Reasoning, Unit 9 Formalism Techniques and Applications.

[Back to the top](#)

### Peer response 2

Jaco in his initial post presents in a robust way the definition of ontologies providing details on their structure. Additionally, considering its expressive power, logical soundness, and modularity, he concludes that OWL2 is the most useful language to express ontologies that can be utilised by software agents on www.

I fully concur with Jaco conclusion and to complement this argument I will provide a short description of the other 3 options, namely RDF, OWL-lite, and KIF.

RDF

It is widely adopted, lightweight and is a very good solution for data interchange. However, it lacks rich ontology modelling, such as class hierarchies.

OWL-Lite

It is easy to implement and though it has the OWL2 characteristics, its expressive power is limited and in turn its use to the majority real-world applications is difficult or even impossible.

KIF

It has expressive power and logical soundness, but it is not web-native, not widely adopted, and not standardized for semantic web.

To sum up, in my view compared to RDF, OWL-Lite, and KIF, OWL2 is indeed the most useful language to express ontologies that can be by software agents on www.

References

Brockmans, S., Haase, P., Serafini, L., & Stuckenschmidt, H. (2009). Formal and Conceptual Comparison of Ontology Mapping Languages. In H. Stuckenschmidt, C. Parent, & S. Spaccapietra, Modular Ontologies. Lecture Notes in Computer Science. Berlin, Heidelberg: Springer.

Guarino, N., Oberle, D. and Staab, S. (2009). Handbook on Ontologies. Springer, Berlin.

Kalibatiene, D., & Vasilecas, O. (2011). Survey on Ontology Languages. In J. Grabis, & M. Kirikova, Perspectives in Business Informatics Research. BIR 2011. Lecture Notes in Business Information Processing. Berlin, Heidelberg: Springer.

Nasim, T. (2022). Improving Ontology Alignment Using Machine Learning Techniques. ProQuest Dissertations & Theses.

Thabet, S. (2015). Ontology Development: A Comparing Study on Tools, Languages and Formalisms. Indian Journal of Science and Technology, 8(24).

[Back to the top](#)


## Summary Post

The original post looked at how ontologies work as structured systems for organising knowledge. According to Nasim’s thesis (2022), these frameworks enable machines to understand and reason with data. It also referred to Guarino, Oberle, and Staab (2009), explaining that ontologies are made up of classes, properties, and individuals. These elements help define concepts and link them to real-world examples. The post highlights their role in organising knowledge and enabling machines on the Semantic Web to understand and relate information independently (Berners-Lee, Hendler, and Lassila, 2001). The post argued that OWL2 is the optimal language for writing ontologies on the web. Balancing detailed knowledge representation with reasoning. These features are especially important for tasks like combining data from different sources (Lawan and Rakib, 2019; Nasim, 2022).

The first peer response aligns with this view, reinforcing the idea that ontologies provide a shared conceptualisation essential for semantic communication and interoperability (Guarino, Oberle and Staab, 2009). It agrees on the importance of structuring domain knowledge clearly through classes, properties, and individuals, and supports the choice of OWL2. The response further emphasises OWL2’s practical advantages as a W3C standard with strong reasoning capabilities and compatibility with RDF, which enable scalable semantic web applications (Nasim, 2022; UoEO, n.d.).

The second response also supports the conclusion on OWL2 but adds useful context by comparing it with other ontology languages such as RDF, OWL-Lite, and KIF. It points out the limitations of these alternatives—RDF’s weaker modelling power, OWL-Lite’s limited expressiveness, and KIF’s poor adoption on the web—strengthening the argument that OWL2 offers the best combination of features for real-world semantic web use (Brockmans et al., 2009; Slimani, 2015).

Together, the responses expand on the original points, confirming the value of ontologies for knowledge representation and underscoring OWL2 as the most effective language for semantic web technologies.

 
References
 

Berners-Lee, T., Hendler, J. and Lassila, O. (2001) ‘The Semantic Web: A New Form of Web Content That is Meaningful to Computers Will Unleash a Revolution of New Possibilities’, Scientific American [Preprint]. Available at: https://www.researchgate.net/publication/225070375_The_Semantic_Web_A_New_Form_of_Web_Content_That_is_Meaningful_to_Computers_Will_Unleash_a_Revolution_of_New_Possibilities (Accessed: 3 July 2025).

Brockmans, S. et al. (2009) ‘Formal and Conceptual Comparison of Ontology Mapping Languages’, in H. Stuckenschmidt, C. Parent, and S. Spaccapietra (eds) Modular Ontologies: Concepts, Theories and Techniques for Knowledge Modularization. Berlin, Heidelberg: Springer, pp. 267–291. Available at: https://doi.org/10.1007/978-3-642-01907-4_13.

Guarino, N., Oberle, D. and Staab, S. (2009) ‘What Is an Ontology?’, in S. Staab and R. Studer (eds) Handbook on Ontologies. Berlin, Heidelberg: Springer Berlin Heidelberg, pp. 1–17. Available at: https://doi.org/10.1007/978-3-540-92673-3_0.

Lawan, A. and Rakib, A. (2019) ‘The Semantic Web Rule Language Expressiveness Extensions-A Survey’. arXiv. Available at: https://doi.org/10.48550/arXiv.1903.11723.

Nasim, T.M. (2022) Improving Ontology Alignment Using Machine Learning Techniques. M.S. Arizona State University. Available at: https://www.proquest.com/docview/2666489192/abstract/727666A2F5334B59PQ/1 (Accessed: 27 June 2025).

Slimani, T. (2015) ‘Ontology Development: A Comparing Study on Tools, Languages and Formalisms’, Indian Journal of Science and Technology, 8(24). Available at: https://doi.org/10.17485/ijst/2015/v8i1/54249.

UoEO (n.d.). Lecturecast, Module 4 Knowledge Representation and Reasoning, Unit 9 Formalism Techniques and Applications.

[Back to the top](#) or [Back to Knowledge Representation and Reasoning](/krr)