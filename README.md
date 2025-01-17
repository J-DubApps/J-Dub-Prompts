# J-Dub-Prompts

### A curated list of my favorite or most-used LLM prompts, in markdown form.

**Prompt Engineering**: ***The practice of designing and refining inputs to guide AI models toward producing desired outputs.*** 

Unless otherwise stated in each prompt document, my prompts are targeting ChatGPT 4o or o1 models.  I may from time-to-time write a specific prompt for Google Gemini, Anthropic, or other LLMs. 

Most of these were created by me vs cited within the prompt-file.md if it's a prompt sourced from somewhere.

Note: Prompt engineering is currently more art than science, and these prompt files are living documents which I am often changing.  So you may want to check-back now and then, if you download or fork this repo.

Note2: I welcome Pull Requests if you see a logical fallacy or just have a way better wording suggestion.  I might not always accept it (or I may create a separate alternate prompt prompt-file.md from your suggestion), but input is always welcome!

----

#### A word on the "art"

Let's think, for a moment, about *why* we need prompt engineering: current LLMs pose a number of challenges that make *reliable* and *consistent* completions challenging to achieve (without first putting effort into prompt construction and optimization). 

1. Models can fabricate responses (*see* [Hallucinations](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))). 
2. Models are pre-trained with massive but *finite* datasets, meaning they can still lack knowledge about concepts outside of their training scope. As a result, they can produce completions that are inaccurate, imaginary, or directly contradictory to known facts.

Prompt engineering techniques help users identify and mitigate such fabrications e.g., by asking AI for citations or reasoning.

Included at the top of this repo are pointers for helping you create better prompts, and even leverage AI models to create better prompts.  Or just look at my favorite examples in each prompt-file.md in this repo.

***Happy Prompting**!!