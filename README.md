
# veld_data_16_eltec_conllu_stats

Statistics on conllu data inferenced with udpipe on eltec corpora.

veld chain can be found here: https://github.com/acdh-oeaw/veld_chain_14_eltec_udpipe_inference

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

