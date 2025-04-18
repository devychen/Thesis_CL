
### Wang.ea-23, Avalon:  

1. Design/framework: **`ReCon`** (Recursive contemplation)
- *"Think twice before act"*
- Two mechanisms: <br>
1/ **formulation contemplation**: first/second-order perspective trasition <br>
2/ **refinement contemplation**
2. Baseline: CoT
3. Evalution: 
- **End-to-End**: <br>
1/ Implement ReCon to different LLMs to assess its genralisation ability (ChatGPT, Claude, failed in LLaMA-2). <br>
2/ Ablation: ReCon w/o two mechanisms
- **Multi-Dimentionsal Evaluation (six)**: Concealment, logic, contribution, persuasiveness, infomration, creativity. **❗️Claim to be the MAINSTREAM BENCHMARK❗️**
4. Notes
- *6 Related Word* section 有MAI，有thought methods/mechanisms, 有game-playing in deceptive environment (AI-related deception).


### Light.ea-23-Avalon

1. Work: **`AvalonBench`**, a agme engine to benchmark the Multi-LLM agents. Includes: 1/ a game environment to play Avalon, 2/ rule-based AI bots as baseline opponents, 3/ ReAct-style i.e Reason-then-Act (_Yao.ea-23_) LLM agents with tailored prompts for each role.
2. Model: GPT-3.5, Llama2
3. Evaluation: Baseline strategy - against NAIVE agents:
- no consideration in dialogue, voting history;
- belive other plays will do the same. 
4. Notes: 4 phrases of Avalon: team selection - voting - quest/action - assassination. Each has a discussion.

### Lan.ea-23, Avalon

1. Contribution: 
- a **`framework`** to play Avalon and to faciliate efficient communication and interaction (提供了quantify的方法论)
- explore social behavious of LLMA: teamwork, leadership, persuation, camouflage, confrontation.
2. Model: GPT-3.5-turbo-16k
3. Evaluation: **Baseline: Xu.ea.23's Werewolf AI Agent**


### Meta.ea-22, Diplomacy
1. Base model: BART-based encoder-decoder called R2C2 (2.7b)
2. Model: base model trained on Diplomacy data

### Mukobi.ea-23, Diplomacy


### Xu.ea-23, Werewolves
```
Facilitate gameplay by LLMs through retrieval and reflection.
Observe solely the camouflage during gameplay, Wang.ea-23-Avalon identifies the camouflage & introduce a comprehensive framework to discern and address deception.
```

### Xu.ea.23, Werewolves RL

### Park.ea.23, Society Simulation

### Qian.ea.23, Software Development Company

### Shao.ea.23, Character-LLM
```
character simulacra of human beings
```
1. **`Character LLM`**: a trainable agent for role-playing that lreasn from actual experiences, characteristics, and emotions
2. 

### Callison-Burch.ea-22, Dungeons and Dragons
```
Dialogue system challenge
```

### Lin.ea-23, Human-AI Dialogue