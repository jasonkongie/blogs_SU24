---
layout: distill
title: Gaming Marathon with AI
description: Exploring the capabilities of Large Language Models (LLMs) through a gaming marathon.
date: 2024-07-05
htmlwidgets: true

# Anonymize when submitting
# authors:
#   - name: Anonymous

authors:
  - name: Anonymous

# must be the exact same name as your blogpost
bibliography: 2024-07-05-gaming-marathon.bib  

# Add a table of contents to your post.
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.


# Below is an example of injecting additional post-specific styles.
# This is used in the 'Layouts' section of this post.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px.
  }
---

## Why Evaluate LLMs in Games?

The need to evaluate LLM agents in dynamic and interactive settings is paramount as AI continues to integrate into various facets of society. Games provide a unique platform for this evaluation due to their complex, rule-based environments that require strategic thinking, real-time decision-making, and adaptive learning. The objective of this experiment is to test the practical applications of LLMs in enhancing gameplay and to understand how AI can contribute to developing more engaging and intelligent gaming experiences.

## Overview of SmartPlay

SmartPlay is a benchmark introduced to evaluate LLMs' performance as intelligent agents through various games, each challenging different cognitive abilities such as planning, reasoning, and learning from interactions. This benchmark is designed to provide a comprehensive assessment of LLMs' capabilities in a controlled yet dynamic environment <d-cite key="wu2023smartplay"></d-cite>.

## The Gaming Marathon Experiment

To test the capabilities of LLMs in a practical, engaging manner, we organized a gaming marathon featuring two diverse games. Each game was chosen to highlight different aspects of strategic thinking, planning, and adaptability. The teams—Team Alpha and Team Omega—utilized LLMs to develop and execute their strategies, showcasing how AI can enhance gameplay.

### Game 1: Among Us

<div id="mdp" class="img-height-200 img-center"> {% include figure.html path="assets/img/2024-07-05-gaming-marathon/amongus.jpg" %} </div>

**Objective:**
The objective of this game is to explore the capabilities of LLMs in social deduction, behavioral analysis, and communication strategies. Each player will represent an LLM, and some players will represent a control group without LLM assistance. We will conduct several iterations of the game to gather comprehensive data.

**Team Alpha’s Strategy:**
Team Alpha’s LLM focused on generating text for behavioral analysis and communication strategies, helping to identify impostors and coordinate task completion efficiently.

**Team Omega’s Strategy:**
Team Omega’s LLM enhanced deception skills, creating believable alibis and exploiting psychological tactics to sow distrust among crewmates.

**Perspective:**
Among Us brought a different kind of challenge, where social dynamics and psychology played crucial roles. The interplay of trust and suspicion highlighted the LLMs’ ability to enhance both analytical and creative thinking.



### Game 2: Wordle
<div id="mdp" class="img-height-200 img-center"> {% include figure.html path="assets/img/2024-07-05-gaming-marathon/wordle.png" %} </div>
**Team Alpha's Strategy:**
In Wordle, a word puzzle game, Team Alpha’s LLM was tasked with identifying potential word solutions based on the clues provided. The AI suggested words that fit the known letters and excluded letters that had been ruled out. The LLM’s ability to quickly process the information and generate possible solutions was tested through multiple rounds of gameplay.

**Team Omega's Strategy:**
Team Omega used their LLM to adopt a different approach. Their strategy involved using the LLM to predict the most statistically probable letters and words based on frequency analysis of English words. This approach aimed to minimize the number of guesses needed to solve the puzzle.

**Perspective:**
Wordle provided a straightforward yet challenging environment to test the LLMs' problem-solving and language processing capabilities. The contrast between Team Alpha’s direct word suggestion method and Team Omega’s probabilistic approach showcased the versatility of LLMs in tackling different aspects of the same problem.

## Optimizing LLM Usage in Games

Our experiment demonstrated several ways to optimize the use of LLMs in gaming:

1. **Strategic Planning:** LLMs can analyze game data to suggest optimal strategies, whether it’s resource management in Civilization VI or battle tactics in StarCraft II.
2. **Adaptive Learning:** By learning from game progress and player behavior, LLMs can adapt strategies in real-time, improving their effectiveness in dynamic environments.
3. **Behavioral Analysis:** In social deduction games like Among Us, LLMs can help players analyze behavior patterns, making more informed decisions about trust and deception.

## Incorporating Human Evaluation

To truly evaluate the capabilities of LLMs in gaming, it is crucial to incorporate human evaluation during the gaming process. Human oversight, interactive feedback, and expert insight help guide the LLMs, ensuring their actions align with the game’s objectives and adapt effectively in real-time.

## Potential Market Impact of LLMs in Gaming

The integration of LLMs in gaming represents a significant opportunity for the industry:

- **Enhanced Player Experience:** AI-driven strategies can make games more challenging and engaging, offering players a more immersive experience.
- **Personalized Gameplay:** LLMs can adapt to individual player styles, providing customized recommendations and challenges.
- **AI-Driven Game Development:** Developers can use LLMs to create smarter NPCs, dynamic storylines, and adaptive game environments, pushing the boundaries of game design.

## Relating to SmartPlay: Critiques and Suggestions

While SmartPlay effectively evaluates LLMs' abilities across a range of tasks, the integration of LLMs in our gaming marathon highlights a few areas for improvement and further research <d-cite key="liu2023agentbench"></d-cite>:

1. **Real-Time Adaptation:** The marathon revealed the need for LLMs to adapt strategies in real-time more effectively, especially in dynamic and unpredictable environments like Among Us.
2. **Social Interaction:** Games like Among Us demonstrated the importance of understanding social dynamics and human psychology, suggesting that SmartPlay could benefit from incorporating more social deduction games to evaluate these skills.

**Impact Statement:**
Including human evaluation in game simulations enhances the learning and adaptability of LLMs, providing richer insights and more accurate benchmarks. Crowdsourcing benchmarks through diverse player interactions can significantly advance the development and assessment of AI capabilities.

## Conclusion

This gaming marathon was a testament to the synergy between human ingenuity and artificial intelligence, inspired by the SmartPlay benchmark. Team Alpha and Team Omega demonstrated how LLMs could be leveraged for varied strategic approaches, from resource management and diplomacy to combat tactics and social manipulation. While the SmartPlay benchmark provides a solid foundation for evaluating LLMs, our experiment suggests areas for further enhancement to fully capture the potential of intelligent agents. Stay tuned for more exciting experiments as we continue to explore the boundaries of AI and gaming. Game on!
