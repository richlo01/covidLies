# COVIDLies Research (UCI ML Hackathon)
Over the past recent years, the use of tweets as a source of news has increased. Sometimes, it has proven to be quite incorrect and misleading -- sometimes causing death.
Social media enables a rapid spread of misconceptions. With a partner, our goal was to see if a tweet propagated a misconception. Given the COVIDLies dataset of 7+ million tweets,
we planned to create a Neural Net that learned a tweet and a specific misconception.
<br />
We used transfer learning to solve this problem. To create word embeddings, we used FastText. We trained it using a subset of our data and an included "lee_corpus" to learn
formal English. Then our idea involved using RAKE (Rapid Automatic Keyword Extraction) to get important parts of the misconception and a query tweet. We would attach adjectives 
and adverbs to grab negations if either the misconception or the tweet had them. Then, we would use cosine similarity to get the result. The process is as follows:
<p align="center">
</p>
  <img src=" " width=200>
<br />
What we found was that we weren't quite as successful. Tweets weren't representative of english and it was difficult to recognize negated sentences from normal ones. Here are the
solutions:
<p align="center">
</p>
<br /> Here is a picture of the word embeddings:
<p align="center">
</p>
