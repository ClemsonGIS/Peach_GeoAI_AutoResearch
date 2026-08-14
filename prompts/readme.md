# Intro
This is where all of the Anthropic Fable 5 prompts are stored.

# base_prompt.txt
Contains the base prompt that gave the LLM all of its domain knowledge, this prompt was then combined with either the first_loop or loop prompt depending on which number trial was being performed.

# first_loop.txt
Contains the prompt added to the base prompt for the first trial run. This prompt explains to the LLM it has to decide informed base parameters for the first trial that will inform its future trials.

# loop.txt
Contains that prompt for any trial after the first trial, which informs the LLM about its prior runs.