# AI Labs

Lab notebooks for the AI course, one per topic. Each has the task answers, the code and its output.

| Notebook | Topic |
|---|---|
| `agents.ipynb` | Goal-based warehouse agent (BFS) |
| `bayes_lm.ipynb` | Bayesian networks and n-gram language models |
| `logic.ipynb` | STRIPS-style planning (`logic.pl` is the optional Prolog part) |
| `neural.ipynb` | XOR, activations, softmax |
| `search.ipynb` | A* vs BFS |

```
pip install -r requirements.txt   # torch is only needed for neural.ipynb
jupyter notebook
```

The code and task answers were written with help from an LLM (Claude), used as an engineering/writing assistant as each lab asks, and then checked by running every notebook end to end (`jupyter nbconvert --to notebook --execute`). Each notebook's reflection section notes what the LLM contributed and what had to be verified independently.
