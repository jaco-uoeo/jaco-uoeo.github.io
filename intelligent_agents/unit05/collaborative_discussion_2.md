# Collaborative Discussion 2: Agent Communication Languages
{: .hidden-title }

## Brief

What are the potential advantages and disadvantages of the use of agent communication languages such as KQML? How do they compare with method invocation in Python or Java?

#### Learning Outcomes
- An understanding of the main agent models in use today and their grounding in artificial intelligence research.
- The knowledge and skills required to develop, deploy and evaluate the tools and techniques of intelligent systems to solve real-world problems.
- An understanding of contemporary research issues in the area of intelligent agent systems.


## Navigation
- [Initial Post](#initial-post)
  - [Peer Response 1](#peer-response-1)
  - [Peer Response 2](#peer-response-2)
- [Summary Post](#summary-post)
- [Back to Intelligent Agents](/intelligent_agents/)


## Initial Post

Agent Communication Languages (ACLs), such as KQML, enable agents to communicate both data and the intent behind messages through performatives like inform and request. This approach is rooted in speech act theory, allowing agents to coordinate more meaningfully than simple method calls.

One of the main advantages of ACLs is interoperability. Agents developed in different programming languages or running on distinct platforms can still interact as long as they share a communication protocol and a common ontology. This flexibility makes ACLs well-suited for open and dynamic multi-agent systems where components may be heterogeneous and distributed (Souza et al., 2016). However, this strict reliance on a common ontology may lead to errors if agents interpret terms differently. This makes achieving semantic alignment both essential and challenging at the same time.

Developing and maintaining shared ontologies along with their supporting components, parsers and semantic managers, adds complexity and overhead to the system (Berna-Koes, Nourbakhsh and Sycara, 2004; Fatras, Ma and Jørgensen, 2022).  Method invocation in languages like Python or Java is more straightforward and efficient. It requires no additional protocol or semantic layer, but it only works reliably in tightly coupled, homogeneous environments where all components are built within the same framework or have deep knowledge of the internals of other elements of the system.

In summary, ACLs provide semantic richness and autonomy valuable for complex, distributed systems. For smaller or tightly integrated systems, the simplicity and speed of direct method calls often outweigh the benefits of ACLs.



#### References

Berna-Koes, M., Nourbakhsh, I. and Sycara, K. (2004) ‘Communication efficiency in multi-agent systems’, in IEEE International Conference on Robotics and Automation, 2004. Proceedings. ICRA ’04. 2004. IEEE International Conference on Robotics and Automation, 2004. ICRA ’04. 2004, pp. 2129-2134 Vol.3. Available at: https://doi.org/10.1109/ROBOT.2004.1307377.

Fatras, N., Ma, Z. and Jørgensen, B.N. (2022) ‘An agent-based modelling framework for the simulation of large-scale consumer participation in electricity market ecosystems’, Energy Informatics, 5(4), p. 47. Available at: https://doi.org/10.1186/s42162-022-00229-0.

Souza, M. et al. (2016) ‘Integrating Ontology Negotiation and Agent Communication’, in V. Tamma et al. (eds) Ontology Engineering. Cham: Springer International Publishing, pp. 56–68. Available at: https://doi.org/10.1007/978-3-319-33245-1_6.


[Back to the top](#)

## Peer Responses

### Peer response 1
Your analysis fairly evaluates the advantages and disadvantages of ACLs. One of the most appealing features of ACLs, particularly in distributed and heterogeneous systems, is interoperability. Agents developed in different programming languages and contexts can interact meaningfully through ontological communication (Souza et al., 2016). Because diverse ontological interpretations may make communication difficult, semantic alignment remains challenging.   


The contrast you draw between ACLs and direct method invocation is also insightful. Method calls in languages such as Java or Python offer efficiency and simplicity, but they are best suited for tightly coupled and homogeneous environments (Berna-Koes, Nourbakhsh and Sycara, 2004). By comparison, ACLs provide richer semantics that support autonomy and flexible coordination. However, they introduce additional complexity, particularly in developing and maintaining parsers, semantic managers, and other supporting infrastructure (Fatras, Ma and Jørgensen, 2022).

Examining hybrid approaches in greater detail might be beneficial. While ACLs can handle interactions across more diversified or distributed infrastructures, direct method calls may be more appropriate for managing communication within homogenous subsystems. Performance and interoperability can be practically balanced using such a tiered strategy.

Overall, your piece successfully integrates theory and practice with solid backing from the well-chosen sources. You demonstrate how various communication techniques can be used based on the system's requirements and clearly outline the trade-offs.  

#### References

Berna-Koes, M., Nourbakhsh, I. and Sycara, K. (2004) ‘Communication efficiency in multi-agent systems’, Proceedings. ICRA ’04. 2004 IEEE International Conference on Robotics and Automation, 3, pp. 2129–2134. doi:10.1109/ROBOT.2004.1307377.
Fatras, N., Ma, Z. and Jørgensen, B.N. (2022) ‘An agent-based modelling framework for the simulation of large-scale consumer participation in electricity market ecosystems’, Energy Informatics, 5(4), p. 47. doi:10.1186/s42162-022-00229-0.
Souza, M. et al. (2016) ‘Integrating Ontology Negotiation and Agent Communication’, in Tamma, V. et al. (eds) Ontology Engineering. Cham: Springer, pp. 56–68. doi:10.1007/978-3-319-33245-1_6.


[Back to the top](#)


### Peer response 2

Agent Communication Languages, or ACLs, such as KQML, were created to let software agents exchange not only information but also intent. Through performatives like inform or request, an agent can express what it wants another agent to know or do. The idea traces back to speech-act theory, where communication is viewed as action rather than mere data transfer. Because of that grounding, ACLs give agents a way to coordinate in a manner that feels closer to conversation than to simple function calls.

One clear strength of ACLs lies in how they promote interoperability. Even if two agents are written in different languages or live on separate platforms, they can still communicate effectively provided they share a protocol and a common ontology. That ability makes ACLs attractive for large, open multi-agent systems that need to evolve and plug in new components on the fly (Souza et al., 2016). At the same time, relying so heavily on shared ontologies brings its own problems. When two agents interpret the same term slightly differently, subtle but serious errors can creep in. Maintaining consistent meaning—semantic alignment—is therefore both essential and notoriously difficult.

Building and maintaining those shared ontologies, together with all the supporting tools such as parsers and semantic managers, adds a fair bit of complexity and runtime cost (Berna-Koes, Nourbakhsh & Sycara, 2004; Fatras, Ma & Jørgensen, 2022). By contrast, direct method calls in languages like Python or Java feel much simpler and faster. They don’t need extra protocols or semantic layers. The trade-off, of course, is that such calls only work well inside tightly coupled systems, where every component has been designed within the same framework—or at least knows quite a lot about how its peers operate internally.

In practice, the choice depends on context. ACLs offer richer semantics and greater autonomy, which are invaluable in large, distributed, and evolving environments. But for smaller or more uniform systems, the plain efficiency of a direct method call often wins out. There’s no single answer here; each approach carries its own balance of flexibility, overhead, and control.


#### References

Bellifemine, F.L., Caire, G. and Greenwood, D. (2007) Developing Multi-Agent Systems with JADE. John Wiley & Sons, Chichester.

Euzenat, J. and Shvaiko, P. (2013) Ontology Matching. 2nd edn. Springer, Heidelberg.

Robu, V., Noot, H., La Poutré, H. and van Schijndel, W.J. (2013) 'A multi-agent platform for auction-based allocation of loads in transportation logistics', Expert Systems with Applications, 40(8), pp. 3483–3491.

Visser, P.R., Jones, D.M., Bench-Capon, T.J. and Shave, M.J. (1997) 'An analysis of ontology mismatches: heterogeneity versus interoperability', AAAI 1997 Spring Symposium on Ontological Engineering, pp. 164–172.

[Back to the top](#)


## Summary Post
Agent Communication Languages (ACLs), such as KQML, let agents exchange not just raw data but also convey their intentions using message types such as “inform” or “request.” This type of communication tends to help with more flexible coordination, especially when dealing with systems that are spread out and made up of different types of agents. One clear upside is interoperability: agents built in different languages or running on separate platforms can still communicate if they agree on a common communication protocol and ontology (Souza et al., 2016). That said, depending on shared ontologies can be tricky. Sometimes, words that appear straightforward can imply different things to different agents, so enforcing semantic alignment is important to prevent mix-ups. Additionally, creating and maintaining ontologies, semantic managers, and parsers introduces extra complexity, slowing down progress both during the build and operational phases of the system (Berna-Koes, Nourbakhsh and Sycara, 2004; Fatras, Ma and Jørgensen, 2022).

On the other hand, calling methods directly, like running functions in Java or Python, is a simpler and faster way to communicate, but generally only works well when the parts of the system are tightly connected and already understand each other. This method avoids dealing with protocols or semantics, which cuts down on extra processing. However, it doesn’t scale well when components vary widely or operate independently.

The peer response backs this up: ACLs are great for supporting autonomy and flexibility across different system boundaries, but they come at the cost of maintaining semantic infrastructure. Meanwhile, direct invocation is fast and simple but only works when the architecture is uniform.

A hybrid approach could offer a good middle ground. When parts of the system are uniform, direct calls remove unnecessary overhead. However, for interactions across more loosely connected areas, ACLs provide the flexibility needed to communicate effectively. Using a hybrid approach can confine complexity and overhead to just the parts of the system that really need distributed communication or autonomy.

 
#### References

Berna-Koes, M., Nourbakhsh, I. and Sycara, K. (2004) ‘Communication efficiency in multi-agent systems’, in IEEE International Conference on Robotics and Automation, 2004. Proceedings. ICRA ’04. 2004. IEEE International Conference on Robotics and Automation, 2004. ICRA ’04. 2004, pp. 2129-2134 Vol.3. Available at: https://doi.org/10.1109/ROBOT.2004.1307377.

Fatras, N., Ma, Z. and Jørgensen, B.N. (2022) ‘An agent-based modelling framework for the simulation of large-scale consumer participation in electricity market ecosystems’, Energy Informatics, 5(4), p. 47. Available at: https://doi.org/10.1186/s42162-022-00229-0.

Souza, M. et al. (2016) ‘Integrating Ontology Negotiation and Agent Communication’, in V. Tamma et al. (eds) Ontology Engineering. Cham: Springer International Publishing, pp. 56–68. Available at: https://doi.org/10.1007/978-3-319-33245-1_6.


[Back to the top](#) or [Back to Intelligent Agents](/intelligent_agents)