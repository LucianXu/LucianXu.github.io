---
title: "Vocabulary In-Context Learning in Transformers: Benefits of Positional Encoding"
collection: publications
category: conferences
permalink: /publication/Ma2025Vocabulary
excerpt: "We study the universal approximation property of Transformers via in-context learning, found that when context is represented by tokens from a finite set (a vocabulary), Transformers need positional encoding to provide density to achieve universal approximation."
date: 2025-11-9
venue: '39th Conference on Neural Information Processing Systems'
slidesurl: 'https://lucianxu.github.io/files/Ma2025Vocabulary/poster.pdf'
paperurl: 'https://lucianxu.github.io/files/Ma2025Vocabulary/main.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

[Openreview version](https://openreview.net/forum?id=W0DDiJeZo6&noteId=W0DDiJeZo6) 

[arXiv version](https://arxiv.org/abs/2511.06376)

**Abstract.** Numerous studies have demonstrated that the Transformer architecture possesses the capability for in-context learning (ICL). In scenarios involving function approximation, context can serve as a control parameter for the model, endowing it with the universal approximation property (UAP). In practice, context is represented by tokens from a finite set, referred to as a vocabulary, which is the case considered in this paper, \emph{i.e.}, vocabulary in-context learning (VICL). We demonstrate that VICL in single-layer Transformers, without positional encoding, does not possess the UAP; however, it is possible to achieve the UAP when positional encoding is included. Several sufficient conditions for the positional encoding are provided. Our findings reveal the benefits of positional encoding from an approximation theory perspective in the context of ICL."


