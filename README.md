# YouTube Comments Analysis for Kurzgesagt 🌌
Welcome to this YouTube comments analysis project for the Kurzgesagt channel. This project aims to deliver multiple insightful and actionable Tableau dashboards that provide a detailed understanding of the channel's comments and community.

# Project Overview 🛰️
This project involves the analysis of comments from 196 videos on the Kurzgesagt channel. Approximately 19,650 comments were retrieved using YouTube's API, then cleaned for extraneous characters and symbols. Other channel Sttistics aere pulled using the API like 

# Sentiment Analysis: 🚀
- Utilized the cardiffnlp/twitter-roberta-base-sentiment-latest model, trained on 124 million tweets, to gauge sentiment.
- Initial results showed 12.2% negative, 28.1% neutral, and 59.7% positive sentiment.
- Feedback from an academic expert suggested a potential limitation in accurately predicting negative sentiments. As a future improvement, the model may be fine-tuned using collected YouTube comments. Preliminary fine-tuning efforts can be found in the "Comment Sentiment Analysis" notebook.
# Topic Modeling: ☄️
- Employed the LDA model to identify key topics and themes across the comments.
- Topics were categorized into three groups: highly related to the video content, general conversation, and hidden/subtopics.
- The optimal number of topics was determined to be between 10-34, with the final choice being 10 distributed topics, each having 12 topic words.
- A word cloud visualization assisted in selecting relevant topics and words, particularly for the hidden/subtopics.
- To structure the analysis, 16 video categories were created for 100 videos, enhancing the Tableau dashboard organization.

# Future Improvements 🤔
- Fine-Tuning: Fine-tuning the sentiment model on the YouTube comments I have to improve the accuracy.
- Topic Refinement: Continuously improving the selection of topic words using LDA and word cloud analysis.
# Conclusion 🫡
- This project serves as a detailed exploration of the Kurzgesagt YouTube community, employing robust sentiment and topic modeling techniques. The resulting Tableau dashboards offer valuable insights into audience sentiments and discussions. 

# Links:
Below is a link to the dashboards and a few of the insights, feel free to comment and let me know what you believe I can improve 🫡. https://public.tableau.com/views/YouTubeSentimentAnalysis/Overview?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

Link to the Kurzgesagt Youtube Channel: https://www.youtube.com/@kurzgesagt

If you'd like to clone this and reupload it, just throw a shout-out or an @ for me in there, it'd be cool to see what you do with it.
