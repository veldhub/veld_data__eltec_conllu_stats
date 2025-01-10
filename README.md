# veld_data__eltec_conllu_stats

Statistics on conllu data inferenced with udpipe on eltec corpora.

This repo and its data is the output of this chain veld repo: 
https://github.com/veldhub/veld_chain__eltec_udpipe_inference

## statistics

### count_token

Simply counting the token for each file (token definition: https://universaldependencies.org/format.html)

### count_lemma_total

Simply counting the unique lemmas (lemma definition: https://universaldependencies.org/format.html)

### count_lemma_normalized_by_token

Taking `count_lemma_total` and dividing it by `count_token` so that this lemma count is respective to the overall token count.

### count_pos

For each part-of-speech tag, count its occurrence (pos definition: https://universaldependencies.org/u/pos/index.html)

### count_feat

For each feature tag, count its occurence (feature definition: https://universaldependencies.org/u/feat/index.html)

