# Introduction to Artificial Intelligence

> "We call ourselves *Homo sapiens* --man the wise-- because our intelligence is so important for us. For thousands of years, we have tried to understand how we think; that is, how a mere handful of matter can perceive, understand, predict and manipulate a world far larger and more complicated than itself. The field of artificial intelligence or AI, goes further still: it attempts not just to understand but also to build intelligent entities." - Artificial Intelligence, A Modern Approach by Russell and Norvig

The concept of AI began in ancient civilization through myths, stories, and rumors of artificial beings (idea of robots) with intelligence or consciousness that can perform tasks on their own. [In Greek Mythology (~700 BC), Talos was bronze giant build by Hephaestus, the Greek god of invention and blacksmithing, under commission by Zeus, the king of greek gods and was tasked with protecting the island of Crete](https://news.stanford.edu/2019/02/28/ancient-myths-reveal-early-fantasies-artificial-life/). Talos stood guard over the island, tirelessly patrolling the shores three times a day and hurled massive boulders towards invading enemy ships. Talos had a tube running from his head to feet that carried a mysterious life-giving elixir called 'ichor'. Later in another text sorceress Medea defeated Talos by removing a bolt of Talos ankle draining the ichor fluid. Hephaestus also build an artificial evil woman sent to Earth with task to punish humans for discovering fire. Hephaestus also created several young golden Maidens. In Jewish folklore, Golems created from inanimate matter such as clay or mud are brought to life to serve some purpose such as to defen against antisemitic attacks. Even in the Bible God create man from dust "the Lord God formed man of the dust of the ground, and breathed into his nostrils the breath of life; and man became a living soul.". Similarly in Hindu mythology the Vishwakarma, the god of craftsmanship and the architect of gods, and the sorceress Maya had created automation along with many architectural wonders. Vishwakarma (meaning: world creator) is also regarded as the creator of the Brahma, Vishnu and Shiva. Furthemore, Indian Lokapannatti (collection of cycles and lores from 11 century AD), tells the story of how an army of automated soldiers (bhuta vahana yanta) were crafted to protect the relics of Buddha in a secret stupa.

![LeonardoRobot](https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Leonardo-Robot3.jpg/800px-Leonardo-Robot3.jpg)

However the first recorded of artificial automation was [steam-powered pigeon by Archytas of Tarentum (428 BC)](https://www.ancient-origins.net/history-famous-people/steam-powered-pigeon-002179), [Hero of Alexandria (10-70 CE) constructed an automata puppet theater, where the figurines and the stage sets moved by mechanical means. Among the first verifiable automation is a humanoid knight drawn by Leonardo da Vinci in around 1495](https://en.wikipedia.org/wiki/History_of_robots). The term "robot" was coined in a satire play published by the Czech Karel Čapek in 1921. R.U.R. (Rossum's Universal Robots), robots were manufactured biological beings that performed all unpleasant manual labors. Industrial robots, manipulators having joints modelled on human shoulder-arm-wrist were developed for performing pull, push, presh and lift motions. With advancement of electronic processing system, the [first industrial robot "Unimate" was developed by Joseph Engelberger (the Father of Robotics) in 1959 from a design of mechanial arm patented in 1954 by George Devol](https://www.automate.org/a3-content/joseph-engelberger-unimate). The prototype Unimate#001 was installed on an assembly line at General Motors diecasting plant in Trenton.

However to build a truly intelligent agent, we would need to understand how humans and other animals show intelligence.[Ancient Egyptian lacked adequate means to obtain knowledge about the human brain, which was regarded to be a form of "cranial stuffings" and had a vague recognition of the effect of head trauma](https://en.wikipedia.org/wiki/History_of_neuroscience). The heart was assumed to be the source of intelligence ("memorizing by heart"). However, Ancient Greek philosopher Alcmaeon suggested that the brain was the organ that controlled the body and the senses. Roman Physician Galen (170 BC) disecting brains of different mammals concluded that the brains 4 ventricles were the site for complex thoughts, personality and bodily function. But in 16th century, Belgian anatomist Andreas Vesalius created a detailed map of the nervous system and proposed that nerve cells are the site of brain function and later Italian Luigi Galvani (1791) showed that electricity applied to nerves could make muscles contract. However, only when Santiago Ramón y Cajal started investigating the nervous system in 1887 using the Golgi stain, that led to the formation of neuron doctrine (nervous sytem and brain are made up of discrete cells, neurons) for which Santiago RamÓn y Cajal and Camillo Golgi were awarded the 1906 Nobel Prize. Furthermore, In 1932 Sir Charles Sherrington and Edgar Adrian won the Nobel Prize for proposing the concept of synapses (junctions between neurons, pictured), which advanced the understanding of the central nervous system; Alan Hodgkin, Andrew Huxley and Australian Sir John Eccles won a Nobel Prize in 1963 for showing how neurons communicate via electrical and chemical signalling. And based on the communication of chemical signals across complex networks of billions of neurons forms the cognitive abilities. It’s truly fascinating how these tiny cells, working together in harmony, enable us to navigate and make sense of the world around us.

![Ramón y Cajal's drawing of the cells](https://upload.wikimedia.org/wikipedia/commons/6/6f/CajalCerebellum.jpg)

By 1940s digital electonic computers were being developed as calculating machines, [the theory of computation, idea of computing machines, formalization of algorithms](https://www.wolframscience.com/prizes/tm23/images/Turing.pdf) were also being developed by Alan Turing (regarded as father of theoretical computer science and artificial intelligence). [Warren McCulloch and Walter Pitts (1943) attempted to model biological neurons based on the available knowledge as a binary threshold device that takes multiple binary inputs (on | off) each associated with a weight and produce a binary output based on the threshold function](https://www.cs.cmu.edu/~./epxing/Class/10715/reading/McCulloch.and.Pitts.pdf). The McCulloch-Pitts neuron, also known as the threshold logic unit, was the earliest mathematical model of artificial neural network, but it did not had the capacity to learn on its own. However they showed that any computable function such as logical connectives can be computed with some network of connected neurons. Donald Hebb in his book "The Organization of Behavior" (1949) provided a simple updating rule for modifying the connection strengths of the neurons called Hebbian learning. [Hebb's rule, theory attempts to explain the activity-dependent synaptic plasticity, the adpatation of brain neurons during the learning process; often summarized as "Cells that fire together wire together"](https://en.wikipedia.org/wiki/Hebbian_theory). The basis of the theory is that when our brain learns something new, neural pathways are activated forming new connections forming a network and with repeated stimulus the connections grow stronger and intuitive. Marvin Misky and Dean Edmonds built the first neural network computer SNARC in 1950 with 3000 vacuum tubes to simulate a network of 40 neurons. With certain modification Frank Rosenblatt at Cornell Aeronautical Laboratory published a paper on The Perceptron (1958) with perceptron learning algorithm.

In 1950 Alan Turing published a landmark paper ["Computing Machinery and Intelligence"](https://redirect.cs.umbc.edu/courses/471/papers/turing.pdf) in Mind journel which proposed a test for machine intelligence, the imitation game, now known as Turing test in which a human interrogator tires to distinguish between a human and a machine based on their answers to questions. The paper considers the problem "Can machines think?" and described in form of the imitation game; it presented different arguments to the possibility or desirability of machine thinking and also provided ideas on how machine can learn from experience or feedback. The proposed the idea of child program, rather than simulateing an adult mind, one can start with a child mind and subject it to an appropriate course of education to obtain the adult brain.

However in early 1950s, there were various names for the field of "thinking machines" such as automata theory, cybernetics and complex information processing and so on. [In 1955 John McCarthy, professor of Mathematics at Dartmouth college coined the name "Artificial Intelligence" for the new field and with Marving Misky, Nathaniel Rochester and Claude Shannon proposed a 2-month, 10-man study of artificial intelligence during summer of 1956](https://en.wikipedia.org/wiki/Dartmouth_workshop) to discuss and study on how to make machine use language, form abstractions and concepts to solve problems requiring some intelligence. Allen Newell and Herbert Simon has a reasoning program the Logic Theorist (LT) capable of thinking non-numerically and later was able to prove many theorems. The Darthmouth workshop did not lead to any new breakthroughs, but the discussion topics from this conference  initiated different domain such as the rise of symbolic method, early expert system and deductive systems versus inductive systems.

Assignment:

- Read Alan Turing paper on ["Computing Machinery and Intelligence"](https://redirect.cs.umbc.edu/courses/471/papers/turing.pdf) and write notes on Turing tests, mention the characteristics features that an agent should have to pass turing test.

## Approaches and Foundations to Artificial Intelligence

## Intelligent Agents

Introduction of agents, Structure of Intelligent agent, properties of Intelligent Agents, PEAS description of Agents, 

### Types of Agents

Simple Reflexive,
Model Based, Goal Based, Utility Based, Learning agent,
Environment Types: Deterministic, Stochastic, Static, Dynamic, Observablc, Semi-observable, Single Agent, Multi Agents