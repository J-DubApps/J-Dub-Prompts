## ChatGPT Prompt Creation Elements

My own list of Elements for creating a great *prompt* when working within an LLM, in my preferred order-of-importance:

### 1. Task or Action

**The thing the LLM/AI is *doing*: the requested output, deliverable, or product.**

Task / Action are *most* important because any task can be given without the other elements I list below (context / role, etc).  There's still opportunity for a meaningful output, and you do not need all six components in every prompt to get usable results. <br />

    Example: "Create a list US ASCII Characters used by 101-key keyboards."

### 2. Context

**Here in *Context* we give more details about the Task or Action, and here we should also set the scope (so that we may limit endless possibilities):**

- What is the prompter's background (or situation / needs)?
- What does success look like?
- What environment are they in?


```Example: "I am an Infrastructure Architect working on an Agile team, to create a DevOps automation process for our company's primary software pipeline.  I have been tasked with creating a basic framework for JSON file processing, such that our chosen solution (Ansible) will log all parsed JSON data, for human-review of actions queued into our CI/CD pipeline.  A successful output would offer a way to create a well-formatted log resource, such that our build, test, and deploy groups can monitor up-to-date logs." ```

### 3. Examples

**Examples can be anything that shows the reasoning proces needed for the best result.**  

This can be descriptive words or a past similar thing, to help inform the *new output* it is about to create.  Can be an attachment with a picture, or screenshot of an email, a brochure, etc.  

E.g. if having ChatGPT rewrite your resume, in addition to the exmple of the resume itself, provide an example of a resume that you like as well.

### 4. Role / Persona

**Who do you want the AI to *be*?  Think of someone (an expert, etc) that you wish you had instant access to for the task you're facing.**

    Example: if looking for a job, tell the AI "you're a hiring manager..."
    Example: if you're injured, tell the AI "you're an experienced physical therapist..."

### 5. Format

**Give any direction as to how you want the output to be structured. Visualize the format you want the result to be in (emails, codeblocks, bullet points, etc).**

    Example: "Output in table format with column headers "Feedback", "Team", and "Priority."
    Example: "Output in an array list format for use within Python."

### 6. Tone 

**Specify the output *tone* or voice for the output**.  

    Example: "Use a {casual / formal} tone" or "Give me a witty output" or "Show enthhusiasm" or "sound pessimistic" etc.

-----
### Optional Elements

- Ask the AI LLM to include its thought process: <br />

    **Provide your thought process or reasoning, e.g. "(I am thinking X Y Z)", along with your output.** <br />

- Ask the AI LLM to include citations of its sources used in an aswer ( to avoid inaccuracies or "[hallucinations](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))").

    **Provide any sources you are referencing when creating your answer** <br />