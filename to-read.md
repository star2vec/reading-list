1. concepte / tehnici mai generale

KTO (Kahneman Tversky Optimization) is a way of fine tuning with feedback.

DE CITIT maybe un paper cv pt tuned lens???

DE CAUTAT DESPRE MED?? MEAN EMERGENCE DEPTH????


2. actual thing

https://arxiv.org/pdf/2403.06634 - cv stealing part of an actual model

https://arxiv.org/html/2404.00806v6 - ceva algorithmic collusion


https://arxiv.org/abs/2503.08679 Chain-of-Thought Reasoning In The Wild Is Not Always Faithful" (Neel Nanda's group)

https://arxiv.org/abs/2508.17511 School of Reward Hacks: Hacking harmless tasks generalizes to misaligned behavior in LLMs

https://arxiv.org/abs/2402.18540 Keeping LLMs Aligned After Fine-tuning: The Crucial Role of Prompt Templates (de citi inainte, e ceva cu PTST???)
https://alignment.anthropic.com/2025/inoculation-prompting/

https://arxiv.org/abs/2310.13548 Towards Understanding Sycophancy in Language Models

TELL-TALE (2025)

"Demystifying the Roles of LLM Layers" (2025)

in context learning and induction heads :000 - de scos the actual paper
https://www.lesswrong.com/posts/TvrfY4c9eaGLeyDkE/induction-heads-illustrated
https://www.youtube.com/watch?v=dCkQQYwPxdM

BadEdit (ICLR 2024)

https://www.anthropic.com/research/small-samples-poison

Multi-Trigger Poisoning (2025)



EVALS!!!!!!!!!!!
Perez's method: https://arxiv.org/abs/2212.09251
aia de la apollo research: https://www.alignmentforum.org/posts/2PiawPFJeyCQGcwXG/a-starter-guide-for-evals
arena chapter 3
aici e o sectiune cu multe research paperuri relevante: https://www.alignmentforum.org/posts/fnc6Sgt3CGCdFmmgX/we-need-a-science-of-evals
DE CITIT asta cu claude fights back https://www.astralcodexten.com/p/claude-fights-back
DE CITIT METR SCAFFOLDING EVAL PAPER? https://arxiv.org/abs/2312.11671

DE CITIT TOT ASA AI EVAL IDK:
https://alignment.anthropic.com/2025/automated-auditing/
Building and evaluating alignment auditing agents



3. cred ca deja au fost citite?? idk, macar accesate maybe

HUGGING FACE RLHF
https://huggingface.co/blog/rlhf



-------------

TO READ NEAPARAT!!

Sources:

Language models transmit behavioural traits through hidden signals in data (Nature)
Subliminal Learning Is Steering Vector Distillation
Beyond Owls: Subliminal Learning Can Transfer Learned Capabilities and Backdoors
Distillation for Incrimination and Distillation for Capabilities (Redwood)
Subliminal Learning is a LoRA Artifact


Blank et al. On their account, what the student picks up is a single direction added to its activations. 
arxiv
Keenan et al. Their evasion model is a rank 1 LoRA on Llama 3.1 8B. It has no trigger phrase and works from monitor verdicts shown in the conversation. Distillation is not mentioned. 
lesswrong
Nief et al. Their transfer effect is sensitive to LoRA rank and vanishes under full fine tuning. 
arxiv















IDK CE CATEGORIE YET - DAR TO READ LIST:
* Unsupervised steering vectors (Mack and Turner, 2024) search for many different vectors that each unlock a different hidden behavior, including planted backdoors.
idee research: <img width="839" height="252" alt="Screenshot 2026-09-28 at 01 53 30" src="https://github.com/user-attachments/assets/b8107cf9-0f76-4cfc-b697-6737b9880a86" />

vvv tot asa steering ca aia de mai sus
* van der Weij, Poesio and Schoots (2024), "Extending Activation Steering to Broad Skills and Multiple Behaviours." 





O POTENTIALA IDEE DE LA CLAUDE pe partea de layers/removing layrs:
What might still be open
Your specific framing is a bit different from what those papers do. Picture a table where each row is a task and each column is a layer (or attention head), with each entry saying how much removing that component hurts that task. Most papers look at the rows one at a time. Your idea is to look at the structure of the whole table:
Can a few shared patterns explain most rows? For example, one "general" pattern every task uses, plus a few task-type patterns (retrieval, arithmetic, reasoning).
Do tasks that look similar to humans have similar rows?
Is the general part concentrated in a few components, or spread out?




--------------
FINETUNING STUFF:::





follow-up DE LA CLAUDE CU PAPER MENTIONAT (ARITMETICA PE LORA):
also, you could look into this: "LoRA composition: LoraHub (2023) builds a new task by mixing a library of existing adapters, which is almost exactly your "preset adapters" idea. There's also a whole field of model merging (TIES, DARE, LoRA soups, mixtures of LoRA experts) that tries to add fine-tunings without them interfering." 

