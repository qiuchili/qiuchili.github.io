---
title: "Syntax-Aware Aspect-Level Sentiment Classification with Proximity-Weighted Convolution Network"
collection: publications
permalink: /publication/sigir19-short
excerpt: 'We build a promixity weighted convolution network for aspect-level sentiment classification.'
date: 2019-07-25
venue: 'The 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019)'
paperurl: 'https://qiuchili.github.io/files/sigir19-short.pdf'
citation: 'Chen Zhang, Qiuchi Li and Dawei Song. (2019). &quot;Syntax-Aware Aspect-Level Sentiment Classification with Proximity-Weighted Convolution Network.&quot; To appear in <i> The 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019)</i>. '
---
It has been widely accepted that Long Short-Term Memory (LSTM) network, coupled with attention mechanism and memory module, is useful for aspect-level sentiment classification. However, existing approaches largely rely on the modelling of semantic relatedness of an aspect with its context words, while to some extent ignore their syntactic dependencies within sentences. Consequently, this may lead to an undesirable result that the aspect attends on contextual words that are descriptive of other aspects. In this paper, we propose a proximity-weighted convolution network to offer an aspect-specific syntax-aware representation of contexts. In particular, two ways of determining proximity weight are explored, namely position proximity and dependency proximity. The representation is primarily abstracted by a bidirectional LSTM architecture and further enhanced by a proximity-weighted convolution. Experiments conducted on the SemEval 2014 benchmark demonstrate the effectiveness of our proposed approach compared with a range of state-of-the-art models.
[Download paper here](https://qiuchili.github.io/files/sigir19-short.pdf)
