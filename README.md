# Predict-Tense
- train a RNN to predict the phonemized past tense of English words
- using the letter sequences of 80% of the phonemized present & past tense, trains an RNN
- then using the remaining 20% tests the accuracy...
- accuracy currently low (around 50%) butttt when it was for the orthographic past tense only, the accuracy was around 95%
- accuracy is the main issue

# Take a look at the data
ɹᵻfɹeɪn :  ɹᵻfɹeɪnd correctly predicted
  - refrain: refrained
smaɪl :  smaɪld correctly predicted
  - smile: smiled
ʃɑp :  ʃɑpt incorrectly predicted for ʃoʊpt
  - shop: shopped
  - (this is one that is incorrect due to a slight change in the vowel pronunciation)
ɛnhæns :  ɛnhænst correctly predicted
  - enhance: enhanced
ɹɛkɚd :  ɹɛkɚd incorrectly predicted for ɹᵻkoɹdᵻd
  - record: record
ɪntɚvju :  ɪntɚvjud correctly predicted
  - interview: interviewed
kaʊntɚɹækt :  kaʊntɚɹækt incorrectly predicted for kaʊntɚɹæktᵻd
  - counteract: counteract
  - we see the same issue as the record conjugation
ɐbændən :  ɐbændənd correctly predicted
  - abandon: abandoned
ɐplaɪ :  ɐplaɪnd incorrectly predicted for ɐplaɪd
  - apply: appliend
  - I think this one is silly :)
bɑɾəl :  bɑɾəld correctly predicted
  - barrel: barreled
