# clembench: Systematic Evaluation of Chat-Optimized Language Models as Conversational Agents

> Chalamalasetti, K., Götze, J., Hakimov, S., Madureira, B., Sadler, P., & Schlangen, D. (2023). clembench: Using Game Play to Evaluate Chat-Optimized Language Models as Conversational Agents. In Proceedings of EMNLP 2023. [PDF](https://doi.org/10.48550/arXiv.2305.13455)


We propose **a complementary way of evaluating LLMs** which combines the control (and reproducibility that comes from automation) that reference-based evaluation offers with the interactivity challenged in chatbot-type preferential evaluation. This is achieved **through *gameplay* in well-defined conversational / dialogue games**. We have implemented a set of games (such as Wordle or Taboo, or games where one player must formulate descriptions of what to do to another player) which current models can play *in self-play*. These games come with metrics that measure the quality of the game play. Together, across the set of games, we can calculate an overal score per model (what we call the *clemscore*) which serves as an indicator of how well the model can follow fine-grained instructions and how well it can simulate goal-directed conversational behaviour.


## Links

- The [main clembench project website](https://clembench.github.io)
- Up-to-date leaderboard with evaluated models is available here: [CLEM Leaderboard](https://huggingface.co/spaces/colab-potsdam/clem-leaderboard)
- Benchmark [code](https://github.com/clembench/clembench) & [results](https://github.com/clembench/clembench-runs) are publicly available.


```
@misc{chalamalasetti2023clembench,
      title={Clembench: Using Game Play to Evaluate Chat-Optimized Language Models as Conversational Agents}, 
      author={Kranti Chalamalasetti and Jana Götze and Sherzod Hakimov and Brielen Madureira and Philipp Sadler and David Schlangen},
      year={2023},
      eprint={2305.13455},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
