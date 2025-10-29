# Out of Many, One
Aalborg Universitet, Social Data Science, 2025

This repository is a rough and perhaps too casual introduction to my master's thesis. This README and repository are in English for ease of access and communication, but the thesis itself, as well as the appendix material, is all in Danish.
The repository should contain the thesis paper itself, the two Python notebooks, as well as the appendix material, which is mostly graphs and figures from the various tests.

A few caveats:
0) I have not included the data from 'Tryghedsmålingen 2024' in this repository, only what is described above. If you want access to the data, contact Tryghedsgruppen/Trygfonden.
1) The Python notebooks are a mess and are basically just left in the state they were in when I finished the thesis, so code is pretty unkempt and full of temporary-fix solutions.

(somewhat) Quick pitch:
Can LLMs fill out surveys? The answer is yes, but there are certain flaws that crop up. The models were, in many cases, good at estimating the median of the human population they were mimicking, but lacked the human variance.
However, much of this research at the time I started was a couple of years out of date, which in the LLM world is prehistory. 
So I was curious if these same strengths and issues existed in the newer models, if they could be solved with increased temperature, and wound up also testing the impact of a numeric answering format vs a text-based answering format.
The answer is somewhat complicated, as these three variables are heavily intertwined, but put simply:
The models struggled to capture the median in the way they had in prior research, likely due to the use of Danish data.
The variance issue persists, especially in newer models, maximum temperature is insufficient to fix it, and prompting is trial-and-error and difficult to predict.
