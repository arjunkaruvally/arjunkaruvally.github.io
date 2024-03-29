---
layout: distill
title: Memory and the Energy Paradigm
description:  A brief historical account of the quest for understanding memory and the energy paradigm
tags: memory intelligence
giscus_comments: true
date: 2023-09-14
featured: true

authors:
  - name: Arjun Karuvally
    url: "https://arjun23496.github.io/"
    affiliations:
      name: BiNDS, CICS, UMASS Amherst

bibliography: 2018-12-22-distill.bib

---

Memory modeling is an expansive research field that aims to understand and suggest mechanisms for storing and processing memories in both human brains and artificial neural networks. While the topic of memory is vast and can't be covered fully in a short piece, I'll highlight a few foundational paradigms that have shaped memory research, culminating with the energy paradigm that has been particularly influential in recent decades.

One might wonder, Why focus on memory? What role does it play in the larger context of intelligence? The importance of memory in understanding intelligence, both in biological and artificial realms, was recognized early on by scientists.

## Biological Intelligence

First, let us look at the question of memory from the perspective of biology.
Initial explorations (late 1800s to early 1900s) into memory commenced with pioneering work by psychologists such as William James and Hermann Ebbinghaus. They investigated the structure and function of memory using introspection and experimental psychology.
The mid-20th century saw advancements in understanding the neurological basis of memory, largely driven by neuropsychological studies on individuals with brain injuries (e.g., the famous case of HM). During this period, the multi-store model of memory which includes sensory, short-term, and long-term stores, was proposed by Atkinson and Shiffrin (1968).
From the 1980s, the advent of neuroimaging technologies like MRI and PET scans facilitated a deeper understanding of the brain’s memory systems and researchers started to unveil the molecular and cellular basis of memory, with Eric Kandel’s work on synaptic plasticity being notably influential.
From 1990s, we have seen the rise of computational models to simulate neural processes underlying memory. These models aided in understanding how neural networks in the brain process, store, and retrieve information.

## Artificial Intelligence

Almost parallel to these developments, the domain of artificial intelligence (AI) also saw memory-centric developments. In the early 1950s, scientists started to take the question of intelligence seriously and introduced the symbolic paradigm. In this paradigm, AI systems were imagined as rule-based system that manipulated symbolic entities to achieve its goals. Here, memory played a crucial role as a fixed data-structure upon which the rule based systems operated.
Later, from the 1980s, a new kind of science started taking shape broadly termed the connectionist paradigm. The models of intelligence based upon this paradigm took inspiration from how biological neurons worked and proposed what are termed as artificial neural networks (ANNs).
At the point, ANNs were at their infancy, only capable of simple tasks in the purview of small university research labs and people pursuing ANN research were considered heretics.

## Convergence - Artificial Neural Networks

It's fascinating to note that both biological and artificial memory research, despite their distinct origins, eventually converged on the potential of ANNs. 
With this convergence came the pressing need to address how memory works in ANNs. At the time, a group of researchers broadly called the behaviourists started investigating memory in neural networks by looking at randomly connected networks.
They found some evidence for the ability of memory storage in neural networks but as a major drawback of the approach, the scientific basis for the memory capabilities could not be uncovered just looking at the behavioral properties of networks alone.
It was at this time, a radical idea for modeling memory started taking shape pioneered by J. J. Hopfield - a theoretical physicist who was curious enough to dabble in the abstract notions of memory research.

## The Energy Paradigm

Hopfield pioneered a mathematically robust model for memory in ANNs using what's known as the energy paradigm. I believe this paradigm stands tall as one of the most significant milestones in contemporary memory research. Its enduring relevance from the 1980s till now certainly attests to its importance.

To truly appreciate the energy paradigm, let's first understand its primary target: *associative memory*.

### Associative Memory

Associative memory lends humans the ability to associative stimuli (visual, auditory, etc) with previous experiences.
Imagine you're in a room with shelves full of books. Each book has a unique cover and a story inside. Now, when you see a book with a cover depicting a beach, your mind might automatically recall the last beach vacation you took, the feel of the sand, the sound of waves, or even the book you were reading while sunbathing.
This link between the book's cover and your personal memories of the beach is a basic example of association. Your brain didn't look at every single memory to find the beach-related one; it simply "jumped" to it because of the connection or association it had made earlier.

Associative memory is all about relationships. Instead of retrieving information by a specific "address" (like pulling out a book from a shelf using a specific order number), the brain retrieves memories based on a web of associations. See a dog? You might remember your childhood pet. Smell a certain perfume? You might recall a person who wore it. In each case, one piece of information (e.g., the smell of a perfume) is linked to another (e.g., a specific person).
Associative memory is like the magical threads in our brain that connect various pieces of information. When one piece is activated, it can pull on these threads and bring forward related memories, making our experiences rich and interconnected. It's one of the many wonders of how our brain works, linking moments, feelings, and knowledge in an intricate web of connections.

### The energy paradigm for associative memory

The concept of the "energy paradigm" might sound technical, but let's break it down using simple ideas and analogies.

> **_The Landscape Analogy_**: Imagine a vast landscape with hills, valleys, and basins. In this landscape, a ball can be placed anywhere. If you set it down on a hill, it will roll down into a nearby valley or basin. The ball will continue to roll until it finds the lowest point it can rest in. Each of these low points or basins represents a stable memory or state.

In the context of associative memories, the landscape is a metaphorical representation of "energy". The idea is that memories, when activated or recalled, seek a state of minimum energy, much like the ball seeks the lowest point in the basin.
When we try to recall something, our brain pushes the memory into the landscape. It might not land directly in a basin (or a perfect recall of the memory). Instead, it might land on a hill. But, just like the ball, it will move to the nearest basin, which represents the memory that our brain thinks is the closest match.
This process is why sometimes our recall isn't perfect. Our memories can get influenced by nearby "basins" or other related memories. It's also why certain triggers can suddenly bring back forgotten memories. They push our memory into the right basin.

### Why is the Energy Paradigm Useful?

1. *Error Correction*: The energy paradigm helps in understanding how our brains can correct distorted or partial information. If you see a part of a familiar object, your brain can often "fill in" the rest, because it's rolling the memory-ball down to the closest complete memory-basin.

2. *Robustness*: Memories stored this way can resist "noise" or interference. Even if some details are fuzzy, the overall memory can still be recalled.

3. *Associations* (See what I did there): It explains why certain memories can trigger related memories. They're like basins located close together in the landscape. If the ball rolls near the edge of one basin, it might easily move over to a neighboring one.

### Wrapping Up

The energy paradigm in associative memories provides a way to visualize and understand the complex processes of memory recall and storage. By thinking of memories as seeking the lowest energy or the most stable state, we get insight into how our brains efficiently store, recall, and sometimes even mix up or modify our memories. It's a reminder of the intricate and dynamic nature of our cognitive processes.
