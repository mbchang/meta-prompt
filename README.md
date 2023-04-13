# Meta-Prompt
This is a minimalistic re-implementation of [Meta-Prompt](https://noahgoodman.substack.com/p/meta-prompt-a-simple-self-improving) by [Noah Goodman](https://cocolab.stanford.edu/ndg). It is written in [LangChain](https://github.com/hwchase17/langchain) for building self-improving agents.

Meta-Prompt is a simple self-improving language agent that reflects on interactions with a user and modifies its own instructions based its reflections. The only thing that is fixed about the agent is the *meta-prompt*, which is an instruction for how to improve its own instructions.

For a description of Meta-Prompt, see Noah's [blog-post](https://noahgoodman.substack.com/p/meta-prompt-a-simple-self-improving).

## Setup
This repo is written with LangChain. See installation instructions [here](https://github.com/hwchase17/langchain#quick-install).
