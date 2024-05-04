---
title: "Floating Anchor Diffusion Model for Multi-motif Scaffolding"
collection: publications
permalink: /publication/2024-01-16-paper-title-number-2
date: 2024-05-01
excerpt: 'A new diffusion model for multi-motif scaffolding, which takes the motifs as rigids and allows them to move while preserving their strucuters'
venue: 'ICML 2024'
paperurl: 'https://arxiv.org/abs/2310.11802'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Motif scaffolding seeks to design scaffold structures for constructing proteins with functions derived from the desired motif, which is crucial for the design of vaccines and enzymes. Previous works approach the problem by inpainting or conditional generation. Both of them can only scaffold motifs with fixed positions, and the conditional generation cannot guarantee the presence of motifs. However, prior knowledge of the relative positions of motifs in a protein is not readily available, and constructing a protein with multiple functions in one protein is more general and significant because of the synergies between functions. We propose a Floating Anchor Diffusion (FADiff) model. FADiff allows motifs to float rigidly and independently in the process of diffusion, which guarantees the presence of motifs and the automatic motif position design. Our experiments demonstrate the efficacy of FADiff with high successful design rates and designable scaffolds. To the best of our knowledge, FADiff is the first work to tackle the challenge of scaffolding multiple motifs with flexible locations in one protein.

