## CHANGES IN sentencepiece VERSION 0.1.3

- Fix Solaris installation issue related to incorrect usage of pointer as a function 
- Also download the binary model in sentencepiece_download_model as it can be loaded with word2vec::read.wordvectors
- read_word2vec now uses word2vec::read.wordvectors from word2vec >= 0.2.0
- added BPEembed and predict.BPEembed
- allow subword regularisation by adding nbest and alpha option in sentencepiece_encode and changed sentencepiece_decode accordingly

## CHANGES IN sentencepiece VERSION 0.1.2

- Fix Solaris installation issue which used log of uint64 which is not defined on Solaris

## CHANGES IN sentencepiece VERSION 0.1.1

- Added verbose argument in sentencepiece

## CHANGES IN sentencepiece VERSION 0.1.0

- Initial package based on https://github.com/google/sentencepiece release v0.1.84 commit  2424d82d396b43b2556203c592e48a621ef10f3c
- Third-party code from https://github.com/google/sentencepiece/tree/master/third_party is put in src/absl, src/esaxx, src/darts_clone, src/protobuf-lite
