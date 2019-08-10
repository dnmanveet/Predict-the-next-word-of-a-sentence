# Predict-the-next-word-of-a-sentence
Built using fast.ai library.

![Screenshot from 2019-08-10 17-05-14](https://user-images.githubusercontent.com/29728855/62823661-d5603100-bbb0-11e9-8aa6-ff0352ed6c4c.png)

I used a pretarined on a bigger dataset(a cleaned subset of wikipedia called wikitext-103).
That model has been trained to guess what the next word,its input being all the previous words.It has a recurrent structure and a hidden state that is updated each time it sees a new word.This is hidden state thus contains information about the sentence up to that point.
This is where unlablled data is going to useful to us, as we use it to fine tune our model.
This predicts the next coming words as shown in the screen shot above.
