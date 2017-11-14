## Welcome to HybridBot Site

You can download it from this [link](https://github.com/FundamentalEq/Seq2seqchatBot). It is an hybrid of two types of bot, First one is IRIS ChatBot and Second one is Seq2Seq chatbot.


### Markdown

Follow following steps to use it:  
Setting up IRIS ChatBot  
Download [Cornell Dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html) and rename it to cornell_movie-dialogs_corpus than just run
```markdown
  bash prepare.sh
```
Setting up Seq2Seq ChatBot  
Download dependencies which are just Python 2.7 and Pytorch 0.12 than run two command one after another
```markdown
  python preprocess.py
  python train.py
```

To Run final bot
```markdown
  python finalBot.py
```
