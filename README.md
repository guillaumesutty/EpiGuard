# EpiGuard - A browser game to understand the role of epigenetics in brain pediatric cancer.

Conceived and developped by [] as part of the Workshop on GenAI organised by [PEPR Cell-ID](https://www.pepr-cell-id.fr/) at the Institut Curie.

Claude Sonnet 4.6 was used to generate the code.

Full prompt:
```
I want to code a web browser game. UI is DNA compacted on nucleosomes and should be in “light mode”. You can check an example of design in the picture attached[1]. We start the game with methylations stacked on the nucleosomes. Few phosphorylation and glycosylations are also present, but are not part of the game. 
We start with 5 “health points” in the form of little brain icons. Random events happen that remove 1 methylation mark. The player has a limited amount of time to put it back by clicking on it. After 3 missed marks, the chromatin unfolds and we lose 1 health point (brain icon). If there is no more methylation present, it's also game over. As the number of marks left decreases, the game should be harder (increase level=more demethylation events and time window to save marks shorter). Levels also automatically increase every 15 seconds, no matter how well the player is doing. Level can only increase
The score should be the number of marks we put back.
Items are falling through from the top of the screen and that we can click. It’s either bonuses (CAR-T cells, drugs, JMJD3 (a protein)) that reset (put back) all methylation marks or good food products/sport that bring a health point back, or dangers (UV, chemicals..) that we shouldn’t click otherwise they cause some additional demethylation events. Falling items should be big and very cute.
Before entering the game, a little narrative is shown that explain the scientific context using Cell-ID document attached and the website https://www.pepr-cell-id.fr/
Once in the game, add a tutorial on how to play the game.
```
\[1] **Figure 1: The H3.1 K27M altered chromatin state is reversible by JMJD3 inhibition.** Ramaswamy, V., Remke, M. & Taylor, M. An epigenetic therapy for diffuse intrinsic pontine gliomas. Nat Med 20, 1378–1379 (2014). https://doi.org/10.1038/nm.3769
