# Personal prompts library

I chat with LLMs quite often, but always start from scratch. This may be annoying especially for the more complex tasks like planning a feature or writing code. I always have to pass the context written by hand, although I usually work with the same stack, etc.

For this purpose it would be good to have some common snippets which would enforce specific behavior or pass common context, like making AI a wall to bounce ideas of or get them to know a few files.

I always feel like the tools I use (aider, codecompanion) doesn't work well for my cases and the LLM drives away in their thoughts.

This could also be a great way to create some scripts handling automated context extraction, when I need a file (along with its dependencies from imports) or just a _map_ using treesitter to make LLM aware of my API. In my case all of this have to work with PHP first.

`mods` allows to pass role, but it is rather for shorter prompts, and I am not even sure if it handles as the system prompt (it should).

This is rather a continuous work, rather than one time shot, but the foundation should be a good start.

Example prompt areas:
- Planning a feature
- Creating a specification with emphasis on feedback loop and questions
- Acting as a bash cli for short queries (reset last git commit)
- Just a concise answer, developer focus

Impact: 8
Confidence: 7
Ease: 8
Category: Organization
