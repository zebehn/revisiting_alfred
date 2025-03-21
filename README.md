# revisiting_alfred
This repository contains the results for our paper titled "Revisiting ALFRED: Refining commands for evaluating language-guided task planning([pdf](https://aair-lab.github.io/genplan25/papers/17.pdf))", which has been accepted for the GenPlan 2025 Workshop at AAAI 2025. For more details, please visit [the workshop webpage](https://aair-lab.github.io/genplan25/).

## Abstract

Language-guided task planning has seen significant advances with the emergence of large language models (LLMs). This paper presents a refinement of the ALFRED benchmark, a widely-used dataset for evaluating embodied AI in household environments. We identify and categorize errors in the original crowd-sourced commands and propose refined commands that maintain alignment with expert demonstrations. We further augment these commands through paraphrasing, contextualization, and cross-lingual translation to create a more comprehensive evaluation suite. Our experimental results across multiple LLM-based planners demonstrate that while state-of-the-art models achieve high success rates on base commands, performance degrades with increased linguistic complexity. The refined benchmark provides a more reliable foundation for evaluating language-guided planning systems while introducing controlled challenges through linguistic variations. Refined command sets are available at https://github.com/zebehn/revisiting_alfred.

## Poster
![Poster](./Poster_minsujang@GenPlan2025.jpg)

## Files
* Refined commands for valid_seen tasks: [refined_valid_seen_commands.json](refined_valid_seen_commands.json)
  * You can browse the commands in [refined_valid_seen_commands.md](refined_valid_seen_commands.md)
* Refined commands for valid_unseen tasks: [refined_valid_seen_commands.json](refined_valid_seen_commands.json)
  * You can browse the commands in [refined_valid_unseen_commands.md](refined_valid_unseen_commands.md)
 
## Acknowledgement
This work was supported by Institute of Information
& communications Technology Planning & Evaluation
(IITP) grant funded by the Korea government(MSIT) (No.
RS-2022- II220951, Development of Uncertainty-Aware
Agents Learning by Asking Questions, 50%, No. RS-2024-
00336738, Development of Complex Task Planning Tech-
nologies for Autonomous Agents, 50%).
