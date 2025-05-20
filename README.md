## About

This repo contains exercises I did working through
[ARENA Chapter 3: LLM
Evaluations](https://arena-chapter3-llm-evals.streamlit.app/)
as part of a [Recurse Center](https://www.recurse.com/) study group in April 2025.

The git history might be interesting as a walkthrough of progress.

The repo organization bears explaining:

- I did the first two sections by copying python notebooks from Arena into
  Colab and saving them in `arena_coursework/`.

- I decided that was pointless busywork (and also, I find Colab is often more trouble
  than running locally if you don't need their GPUs), so I just imported the entire [Arena repo](https://github.com/callummcdougall/ARENA_3.0) as a git subtree, in `ARENA_3.0/`.

The only files I worked on in the `ARENA_3.0` subtree are:

```
ARENA_3.0/chapter3_llm_evals/exercises/part3_running_evals_with_inspect/3.3_Running_Evals_with_Inspect_exercises.ipynb
ARENA_3.0/chapter3_llm_evals/exercises/part4_llm_agents/3.4_LLM_Agents_exercises.ipynb
ARENA_3.0/requirements.txt
```

(The requirements.txt was just tweaked to get past some installation obstacles, by
skipping stuff that was only needed for chapters I wasn't doing.)
