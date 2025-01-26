# J-Dub-Prompts

### A curated list of my favorite or most-used LLM prompts.

**Prompt Engineering**: ***The practice of designing and refining inputs to guide AI models toward producing desired (and accurate) outputs.*** 

Unless otherwise stated in each prompt document, my prompts are targeting ChatGPT 4o or o1 models.  I may from time-to-time write a specific prompt for Google Gemini, Anthropic, or other LLMs (and will say when I do). 

Most of these were crafted by me the past year (noted within the prompt-file.md, if sourced elsewhere).

**Note**: Prompt engineering is currently more *art* than science, and these prompt files are living documents which can change often.  So either check-back now and then, or re-fork this repo for updated reference.

**Note2**: I welcome Pull Requests if you see a logical fallacy or just have a way better wording or suggestion.  If I don't accept or merge changes, I may create a separate alternate prompt-file.md from your suggestion. But input is always welcome!

----

[Here, also, is my suggestion for writing prompts from scratch](https://github.com/J-DubApps/J-Dub-Prompts/blob/main/1-Elements-of-a-Good-Prompt.md).

----

### A word on the "art"

Let's think, for a moment, about *why* we need prompt *engineering*: current LLMs pose a number of challenges that make *reliable* and *consistent* completions challenging to achieve (without first putting effort into prompt construction and optimization). 

1. Models can fabricate responses (*see* [Hallucinations](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))). 
2. Models are pre-trained with massive but *finite* datasets, meaning they can still lack knowledge about concepts outside of their training scope. As a result, they can produce completions that are inaccurate, imaginary, or directly contradictory to known facts.

Prompt engineering techniques help users identify and mitigate such fabrications e.g., by asking AI for citations or reasoning.  **It may not always be this way**: [AGI-ASI](https://en.wikipedia.org/wiki/Artificial_general_intelligence) eventually won't need a lot of prompt *engineering* when fielding requests.  Until then, it's on *us humans* to craft our prompts in a manner that gets the intended (and accurate) results!

Included at the top of this repo are pointers for helping you create better prompts, and even leverage AI models to create better prompts.  Or just look at my favorite examples in each prompt-file.md in this repo.

**Happy Prompting**!!
