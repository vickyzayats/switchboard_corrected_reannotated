We provide a new version of Switchboard corpus with disfluency annotations for careful speech transcripts.

The columns in the data correspond to:
sentence -            list of words for each sentence in Penn Treebank
ms\_sentence -      list of words for each sentence in Ms-State transcript
comb\_sentence -   combination of the two versions of the sentence
names -                word ids for sentence
ms\_names  -         word ids for ms\_sentence
comb\_ann  -          tags for comb\_sentence that indicate which words have to be inserted/deleted/substituted in order to get from MsState to Treebank
tags -         BIO tags for sentence (Penn Treebank annotation)
ms\_disfl -    BIO tags for MsState sentence (silver annotation)

BIO tags are the following:
BE - beginning of the reparandum
IE - inside the reparandum
IP - the last word before the interruption point
BE\_IP - single token reparandum 
C - repair (correction)
O - non-disfluency
C\_IE - the word is both in the reparandum and repair but not before interruption point (in nested disfluencies)
C\_IP - the word is both in the reparandum and repair and the last before the interruption point (in nested disfluencies)

You can find more details in our paper: https://arxiv.org/pdf/1904.04398.pdf.


```
@article{zayats2019disfluencies,
  title={Disfluencies and Human Speech Transcription Errors},
  author={Zayats, Vicky and Tran, Trang and Wright, Richard and Mansfield, Courtney and Ostendorf, Mari},
  journal={Interspeech},
  year={2019}
}
```

