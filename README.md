# YouTube Comments Analysis for Kurzgesagt 🌌
Welcome to this YouTube comments analysis project for the Kurzgesagt channel. This project aims to deliver multiple insightful and actionable Tableau dashboards that provide a detailed understanding of the channel's comments and community.

# Project Overview 🛰️
This project involves the analysis of comments from 196 videos on the Kurzgesagt channel. Approximately 19,650 comments were retrieved using YouTube's API, then cleaned for extraneous characters and symbols. Other channel statistics were pulled using the API like 

# Sentiment Analysis: 🚀
- Utilized the cardiffnlp/twitter-roberta-base-sentiment-latest model, trained on 124 million tweets, to gauge sentiment.
- Initial results showed 12.2% negative, 28.1% neutral, and 59.7% positive sentiment.
- Feedback from an academic expert suggested a potential limitation in accurately predicting negative sentiments. A future improvement to the model may be fine-tuning it on the collected YouTube comments. My fine-tuning efforts can be found at the bottom of the "Comment Sentiment Analysis" notebook.
# Topic Modeling: ☄️
- Employed the LDA model to identify key topics and themes across the comments.
- I wanted to create 3 key topics and themes found in the comments text using the LDA model. The first topic is highly related to the video content, the second has to do with the general conversation in the comments, and the third is a hidden or subtopic related to the video content.
- The optimal number of topics was determined with the coherence model and was between 10-34 topics. I chose 10 distributed topics, each having 12 topic words.
- When picking the topic words at least 3/5 words came from the LDA model and the other 2/5 words came from the word cloud and my observation of the comments text.
- A word cloud visualization assisted in selecting relevant topics and words, particularly for the hidden/subtopics. If a topic I created used more words from the word cloud and less for the LDA model, it was marked with "(WC)".
- To structure the analysis, 16 video categories were created for 100 videos, enhancing the Tableau dashboard organization.

# Future Improvements 🤔
- Fine-Tuning: Fine-tuning the sentiment model on the YouTube comments I have to improve the accuracy.
- Topic Refinement: Continuously improving the selection of topic words using LDA and word cloud analysis.
# Conclusion 🫡
- This project serves as a detailed exploration of the Kurzgesagt YouTube community, employing robust sentiment and topic modeling techniques. The resulting Tableau dashboards offer valuable insights into audience sentiments and discussions. 

# Links: 🔗
Below is a link to the dashboards and a few of the insights, feel free to comment and let me know what you believe I can improve 🫡. https://public.tableau.com/views/YouTubeSentimentAnalysis/Overview?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

Link to the Kurzgesagt Youtube Channel: https://www.youtube.com/@kurzgesagt

If you'd like to clone this and reupload it, just throw a shout-out or an @ for me in there, it'd be cool to see what you do with it.
