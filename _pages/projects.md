---
layout: single
permalink: /projects/
title: "Selected Projects"
seo_title: "Projects | Shuailin Tao"
description: "Projects in semantic search, embedding evaluation, behavioral data analysis, and representation learning by Shuailin Tao."
excerpt: "Selected work in semantic retrieval, model evaluation, behavioral data analysis, and representation learning."
author_profile: true
---

<p>Selected work in semantic retrieval, model evaluation, behavioral data analysis, and representation learning.</p>

<article id="semantic-retrieval" class="project-entry">
  <h2 class="project-entry__title">Semantic Retrieval for App Search</h2>
  <p class="entry-context">Huawei AppGallery | Production retrieval and online evaluation</p>
  <p>App search needs to handle short and ambiguous queries, including abbreviations and category requests that can be difficult to resolve through lexical matching alone.</p>
  <p>I developed semantic retrieval methods using pretrained embedding models to represent application metadata and search queries. I worked on query representation design, offline retrieval checks, and integration with existing search workflows, in collaboration with engineering colleagues.</p>
  <p>Evaluation combined offline relevance analysis with online A/B experiments. The work was integrated into production search, and experiments showed positive results in the evaluated market.</p>
  <p class="method-tags">Semantic search · Embeddings · Query understanding · Online evaluation</p>
</article>

<article id="embedding-evaluation" class="project-entry">
  <h2 class="project-entry__title">Evaluating Embedding Quality</h2>
  <p class="entry-context">Huawei AppGallery | Offline evaluation</p>
  <p>Useful embedding systems need evidence that similarity scores reflect the relationships an application cares about. I built an evaluation workflow using candidate pairs and LLM-assisted relevance judgments on a three-level scale.</p>
  <p>Using these judgments as evaluation labels, I assessed both pairwise discrimination and ranked retrieval quality with AUC, Precision@10, NDCG@10, and MRR. The workflow supported comparisons between representation choices and investigation of failure cases.</p>
  <p>The emphasis was on understanding where a representation worked, where it failed, and how those findings could guide retrieval decisions.</p>
  <p class="method-tags">Relevance evaluation · LLM-assisted labeling · Ranking metrics · Error analysis</p>
</article>

<article id="behavioral-query-understanding" class="project-entry">
  <h2 class="project-entry__title">Behavior-Based Query Understanding</h2>
  <p class="entry-context">Huawei AppGallery | Data analysis and method development</p>
  <p>Search queries can express a clear app preference, a broader intent, or ambiguity. I analyzed aggregated query–app click data to study the concentration of user choices and develop representations informed by historical behavior.</p>
  <p>I also developed a method for estimating token importance by comparing interaction distributions across related query variants, including variants that differed by token deletion or replacement. Distributional differences were measured using Jensen–Shannon distance, with minimum-support thresholds and comparisons across data segments used to assess the reliability of estimates.</p>
  <p>This work focused on extracting useful signals from observational data, with attention to coverage, ambiguity, and the limitations of sparse observations.</p>
  <p class="method-tags">Behavioral data · Query representations · Distribution analysis · Signal reliability</p>
</article>

<article id="representation-learning" class="project-entry">
  <h2 class="project-entry__title">Representation Learning for Time-Series Data</h2>
  <p class="entry-context">Nanyang Technological University | Doctoral research</p>
  <p>My doctoral work studied neural methods for learning from time-series and multimodal sensor data. I developed compression and reconstruction models using autoencoders and attention mechanisms, and contributed to work on multimodal fusion and learning with limited or imbalanced datasets.</p>
  <p>The central questions were how to retain useful information in compact representations, combine complementary inputs, and evaluate model quality under practical constraints. The applications included physiological signals and human activity data.</p>
  <p>This work provided a foundation in experimental design, representation learning, and the trade-offs between model complexity and information preservation.</p>
  <p class="method-tags">Representation learning · Autoencoders · Attention · Multimodal learning</p>
  <p><a href="/publications/">Related publications</a></p>
</article>
