We provide a new version of Switchboard corpus with disfluency annotations for careful speech transcripts.

The columns in the data correspond to:<br>
sentence -            list of words for each sentence in Penn Treebank <br>
ms\_sentence -      list of words for each sentence in Ms-State transcript <br>
comb\_sentence -   combination of the two versions of the sentence <br>
names -                word ids for sentence <br>
ms\_names  -         word ids for ms\_sentence <br>
comb\_ann  -          tags for comb\_sentence that indicate which words have to be inserted/deleted/substituted in order to get from MsState to Treebank <br>
tags -         BIO tags for sentence (Penn Treebank annotation) <br>
ms\_disfl -    BIO tags for MsState sentence (silver annotation) 

BIO tags are the following: <br>
BE - beginning of the reparandum <br>
IE - inside the reparandum <br>
IP - the last word before the interruption point <br>
BE\_IP - single token reparandum <br>
C - repair (correction) <br>
O - non-disfluency <br>
C\_IE - the word is both in the reparandum and repair but not before interruption point (in nested disfluencies) <br>
C\_IP - the word is both in the reparandum and repair and the last before the interruption point (in nested disfluencies) <br>

You can find more details in our paper: https://arxiv.org/pdf/1904.04398.pdf.


```
@article{zayats2019disfluencies,
  title={Disfluencies and Human Speech Transcription Errors},
  author={Zayats, Vicky and Tran, Trang and Wright, Richard and Mansfield, Courtney and Ostendorf, Mari},
  journal={Interspeech},
  year={2019}
}
```

