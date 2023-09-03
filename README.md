# Bayes_ARP_Abarth_1

## Project Target
### 1 Collect online comments regarding EV then make topic modeling & sentiment analysis
### 2 Propose business insights and identify risks & opportunities based on the model

## File Introduction
### 1. Xiao_SpeakEV_0: The code to scrape online comments & other information from SpeakEV. Brands except Peugeot use the Approach_1 to naviagte (via brand forum), Peugeot was scrapped via Approach_2 (the key-word searching)
### 2. Xiao_Preprocess_0: The code to clean text data (e.g., cut out the text before 'Click to expand...' within each reply)
### 3. TopicDis_Shawn: The code that trained and tuned Topic Models and assigned each text with the topic number that has the highest possibility. Visualise distribution under each brand over time
### 4. Shawn_Pretrain: The code run on Google Colab that tried 4 sentiment classifiers based on manual labels
### 5. Senti_Topic: The code run on Google Colab that assigned labels of sentiments to each text
### 6. Senti_Topic_Vis: The code that visualise sentiment distributions & Sentiment-Topic distributions
