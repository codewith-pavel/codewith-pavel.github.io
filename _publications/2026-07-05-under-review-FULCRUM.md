---
title: "FULCRUM: Option-Contrastive Frame Selection for Long-Video Understanding"
collection: publications
category: under-review
status: under-review
authors: "Anonymous Authors"
role: "Co-Author"
venue: "International Conference on Learning Representations (ICLR)"
journal: "ICLR"
quartile: "A*"
year: 2026
thumbnail: "/images/500x300.png"
keywords: ["Long-video understanding", "Video large language models", "Frame selection", "Option-contrastive relevance", "Multiple-choice video question answering", "LongVideoBench", "Training-free inference"]
permalink: /publication/fulcrum-option-contrastive-frame-selection-long-video
excerpt: "FULCRUM is a training-free frame selector for long-video understanding that scores frames by option-contrastive relevance, allocates evidence across the video, and selects non-redundant frames for stronger multiple-choice video question answering."
date: 2026-09-19
citation: "Anonymous Authors (under review). FULCRUM: Option-Contrastive Frame Selection for Long-Video Understanding"
---
## Abstract

Video large language models answer questions about long videos from a budget of a few frames, so frame selection bounds the evidence the answerer sees. Current selectors score each frame by its similarity to the question, or to the question joined with the answer options, and spend the budget on the highest scores. A multiple-choice answerer, however, chooses among options, and a frame informs that choice only if it favors one option over the others. A score shared by all options cannot express this. We propose FULCRUM, a training-free, plug-and-play frame selector built on option-contrastive relevance. FULCRUM scores each frame against every option and measures the margin of the best-supported option over the average option, a margin that equals the log-odds of the favored option against the geometric mean of all options. It then divides the frame budget across the video in proportion to this evidence, with every part of the video guaranteed a frame, and selects non-redundant frames within each part. With 8 frames on LongVideoBench, FULCRUM improves Qwen2.5-VL-7B over uniform sampling by 9.1 points and over the strongest published selector by 3.0, and 4 frames chosen by FULCRUM outperform 16 uniform frames. The gains hold on Video-MME and MLVU and across three answerers. Our results suggest that the options of a multiple-choice question already specify the evidence its answerer needs.

**Keywords:** Long-video understanding; Video large language models; Frame selection; Option-contrastive relevance; Multiple-choice video question answering; LongVideoBench; Video-MME; MLVU; Training-free inference.