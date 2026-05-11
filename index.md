---
title: Home
---

# Welcome

This is the starter website for **airesilient.org**.

## Getting Started

- Edit this `index.md` file to update homepage content.
- Update `_config.yml` for site-level title and description.
- Add new Markdown pages in the repository root (for example, `about.md`).

# AI-Resilient Interfaces

Consider something you'd like AI assistance with. For example, reasoning about a long document or searching for information. 

For the purpose of this discussion, "AI" refers to automated decision making that is not deterministic, e.g., using an LLM to search documents for information instead of searching for documents that have the most instances of a given list of keywords.

#todo: revisit description of AI

A *fully* AI-resilient interface is one in which you can notice *every* choice an AI makes, presented *along with* visible context necessary to judge that choice well.

TODO: EXAMPLE of GPTSM

Not all interfaces will be fully AI-resilient; some will be AI-resilient with respect to a certain type of AI choice or the choices necessary to complete certain tasks.

TODO: produce figure from image of graph from May 11 (google photos)

<!-- For example, information retrieval: if an AI is making a choice about each document in a corpus of 10,000, making every AI choice completely visible (without dramatically abstracting away most details) to a human with typical human limits on cognition, memory, and attention, is probably physiologically impossible.  -->
For example, information retrieval: 
- If a regular deterministic program is computing some simple function over each document in a corpus of 10,000, making every output for every document visible is still probably physiologically impossible for a human to do, given our limits of cognition, memory, and attention. This is still true if the computation happening over each document is done more complex and requires AI. (point to high on vertical axis of figure)
- [example where scale of context necessary to judge makes the task of evaluating the AI choice comparable to the effort of having done it yourself] (point to far right on horizontal axis of figure)

- [example: showing 3 images from a natural language prompt for inner left corner of triangle in figure]

Saying the same thing another way, if showing the AI's choices for each of the 10k documents is only possible by abstracting away all but the position of the doucment in some 2D projection of a embedding space, then users can "see" every choice but the 2D embedding position doesn't provide enough context for the user to judge accurately whether the AI's choice about each document was, depending on the type of choice, (1) objectively correct, if that's well defined (2) contextually appropriate, if there's context that should affect the choice and/or (3) subjectively best, if there's non-trivial user preference at play.

Even if it's physiologically impossible, no matter how the interface is designed, for a human to review an AI's choice on every document in a 10k corpus, that doesn't mean we can't move, with better design, an interface towards making the user *more* AI-resilient than they would have been otherwise.



## Is AI-resilient interface design relevant