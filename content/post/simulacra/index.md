---
title: Simulacra
date: 2023-12-29
---

# Generative Agents to Simulate Human Decision-Making

In many cases, language models proved effective in "reasoning" like humans. A natural evolution of LLMs is generative agents: LLMs are given a memory, some reasoning abstraction to make decisions, and access to external tools they can use when needed. In the last few months, an increasing amount of researchers (notably Park, O'Brien, Cai, et al., 2023; Vezhnevets, Agapiou, Aharon et al., 2023) popularized the idea of creating virtual environments and populating them with generative agents. If the agents are believable, i.e., their behavior is a reasonable representation of human behavior. Such simulations can allow the creation of tools to make inferences about human decision-making without the need to conduct experiments with real humans. Several frameworks for creating simulated environments have already been published, but there has yet to be a consensus on running systematic experiments in silico and drawing inferences from those. In the coming months, I would like to explore a possible methodology.

I see a future, not too far away, where we can use generative agents' simulations for human decision-making. I want to digress a second about the epistemic question: "By what standard should we judge whether (and in what ways, and under which conditions) the results of in silico experiments are likely to generalize to the real world?" (formulation taken from Vezhnevets, Agapiou, Aharon, et al., 2023). We are in such an early stage of generative agents that we have no means to answer this question. You might then ask me, "Rob, why would you bother creating simulations if you cannot trust the results?

Also, how can these kinds of simulations bring some new inferences to the table? Let's think for a second about a couple of the current tools we have to simulate human behaviors:
- Economic models
- Psychological and sociological models

In economic models, the agents are usually Homo economicus, i.e., rational economic actors trying to maximize their economic benefit. But we know humans are only sometimes like that, especially when inter-human interaction is involved. They are valid for many scenarios, but more often than not, they need a representation of human reasoning. 
Models of behavior from sociology focus more on how humans behave in certain social situations. The two main epistemic limitations are that the amount of experiments you can do on humans is minimal (and the search space is infinitely large). You never know when to generalize your findings to a larger population w.r.t. the tested one.

In both cases, researchers came up with those models from a very high level by looking at some past human behavior, trying to extrapolate a rule from such data, together with their prior beliefs. I want to put forward an analogy. If we make models based on LLMs, we do something close to the researchers creating those models.
Indeed:
- We are using past observed human behavior to model it (since LLMs are trained on human artifacts on the web)
- It will only sometimes generalize well to all humans on Earth.
- Researchers' prior beliefs influence the conclusions because the setting of the simulations (e.g., the LLM reasoning abstraction) can bias the results.
The point I am trying to make is that these are all downsides of models we're already familiar with - when we trust a Supply and Demand model or a System 1 and System 2 model for thinking. 

The following are some scenarios in which simulations could and will be used eventually, assuming we have a believable representation of human beings:
Single individuals - before making important life decisions or conversations, one could simulate what could happen with different seed initializations millions of times. Averaging the results, one could have an estimate of the probabilities of each outcome. For instance, what would happen if I asked for a salary increase? What's the best strategy, given the profile of my manager?
- Smaller communities - let's say I am handling a community of volunteers helping the local homeless shelter. What incentives can I use to build a larger community? How can I keep them motivated? What happens if I start hiring more and more people?
- Companies - before launching a new feature on actual humans or doing A/B testing, I could have a sandbox to provide an initial hypothesis on how things might pan out. If I add more advertisements, will usage decrease?
- Governments and public entities - if I am the mayor of a city, what happens if I let many immigrants into the city? And if I block everyone from entering?


The following are some experiments that I consider to be interesting for the scope of my research project:
- Morality: studying the interaction between agents when they face a moral choice. How do group dynamics affect their decisions? What happens when a moral agent is surrounded by agents maximizing their self-interest? Do we observe conformity to the group effect? This might show how simulations can be used to study experimental psychology and group dynamics.
- External tools and APIs: studying the interactions of one or more agents with external tools, providing LLM access to APIs. How do they interact with chat applications, emails, and calendars? This might unveil the simulation's capabilities to be used as a "test bed" for software applications.
- AGI: visualizing possible AGI (Artificial General Intelligence) scenarios in a simulated environment. What happens if we gradually increase an AI's power and capabilities inside the simulation? How does it affect society? Does it reach a point at which it becomes detrimental? It could be helpful for alignment research.

To do so, I will need to follow these steps:
- Choose or build a framework to generate the simulated environment
- Choose an abstraction for the reasoning and memory abilities of the agents
- Create a strategy to assess the believability of the simulations
- Select a handful of scenarios that could yield interesting emergent behaviors
- Evaluate the results by answering the following questions:
- Are the simulated agents believable representations of human behavior?
- If they are, what inference can we draw about human decision-making/future from the simulated scenarios?
