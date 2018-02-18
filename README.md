# keyword_extraction_nltk

## Reference Links:
- [ Evaluating N-gram based Evaluation Metrics for Automatic Keyphrase Extraction ](http://www.aclweb.org/anthology/C10-1065)
- [ NLTK book: Extracting Information from Text ](http://www.nltk.org/book/ch07.html)
- [ Au Naturale – an Introduction to NLTK ](http://alexbowe.com/au-naturale/)
- [ Key Phrase Extraction from Tweets ](https://datascienceplus.com/key-phrase-extraction-from-tweets/)
- [ Topic Modeling of Twitter Timelines in Python ](https://medium.com/@alexisperrier/topic-modeling-of-twitter-timelines-in-python-bb91fa90d98d)
- [ Beginners Guide to Topic Modeling in Python ](https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/)
- [ Tweet Sentiment Visualization ](https://www.csc2.ncsu.edu/faculty/healey/tweet_viz/tweet_app/)
- [ Ultimate Guide to Understand & Implement Natural Language Processing ](https://www.analyticsvidhya.com/blog/2017/01/ultimate-guide-to-understand-implement-natural-language-processing-codes-in-python/)


## Sample input and output:

- "We are making great progress with healthcare. ObamaCare is imploding and will only get worse. Republicans coming together to get job done!"
  > ['great', 'progress', 'healthcare', 'obamacare', 'republicans', 'job']
- "'U.S. Consumer Comfort Just Reached Its Highest Level in a Decade' ??https://t.co/S8nZgmeMMV https://t.co/xC0piRa6eP"
  > ['consumer', 'comfort', 'just', 'highest', 'level', 'decade', 'https', '//t.co/s8nzgmemmv', 'https', '//t.co/xc0pira6ep']
- "For eight years Russia 'ran over' President Obama, got stronger and stronger, picked-off Crimea and added missiles. Weak! @foxandfriends"
  > ['years', 'russia', 'president', 'obama', 'picked-off', 'crimea', 'missiles', 'foxandfriends']
- "122 vicious prisoners, released by the Obama Administration from Gitmo, have returned to the battlefield. Just another terrible decision!"
  > ['vicious', 'prisoners', 'obama', 'administration', 'gitmo', 'battlefield', 'just', 'terrible', 'decision']
- "MAKE AMERICA GREAT AGAIN!"
  > ['make', 'america', 'great', 'again']
- "North Korea just stated that it is in the final stages of developing a nuclear weapon capable of reaching parts of the U.S. It won't happen!"
  > ['north', 'korea', 'final', 'stages', 'nuclear', 'weapon', 'parts', 'u.s']
- "Russia has more warheads than ever, N Korea is testing nukes, and Iran got a sweetheart deal to keep theirs. Thanks, @HillaryClinton."
  > ['russia', 'warheads', 'n', 'korea', 'nukes', 'iran', 'sweetheart', 'deal', 'thanks', '@', 'hillaryclinton']
- "In Bangladesh, hostages were immediately killed by ISIS terrorists if they were unable to cite a verse from the Koran. 20 were killed!"
  > ['bangladesh', 'hostages', 'isis', 'terrorists', 'verse', 'koran']