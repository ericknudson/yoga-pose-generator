# yoga-pose-generator

I generate new Sanskrit-sounding yoga pose names using a character-level RNN implemented in PyTorch.  I based the model on [this tutorial](https://pytorch.org/tutorials/intermediate/char_rnn_generation_tutorial.html) and trained it on 250+ poses that I transcribed from B.K.S. Iyengar's *Light on Yoga*. 

Some examples:

* `Karinala`
* `Ana Malasvra Irakasana Dhabradasana`
* `Upta Kurkapadasana I`
* `Angulavastaiasasanasana`

The model hasn't overfit the data (by just re-producing existing pose names), but also hasn't underfit (the names are believable, at least for a non-Sanskrit speaker like myself).
