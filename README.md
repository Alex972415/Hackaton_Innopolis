# Innopolis Hackathon
### [Link to the report made in Google Colab](https://colab.research.google.com/drive/1SDR6CU6KrJ65B106nOvV5oR9nX_QJam0?usp=sharing)
### This project was carried out as part of participation in the hackathon for the city of Innopolis in December 2023. Our team, consisting of 5 members - a project manager, 2 marketers and 2 analysts, analyzed the current state of the Innopolis telegram channel and provided recommendations for its improvement and development. The customer appreciated our project highly, awarding us the honorable 3rd place.
### Task description:
Innopolis is the first and so far the only Russian city for IT specialists. In addition, it is the first city built from scratch in the modern history of our country. Now more than seven and a half thousand people live and work there, and 68% of residents have moved from other regions of the Russian Federation, and 6% are foreign citizens. At the same time, every third resident in Innopolis is an IT specialist or a scientist. Today, the city has all the necessary social infrastructure: kindergartens, schools, IT lyceum, hospital, urban spaces. Innopolis University, Russia's first IT university, has been opened here. It is included in the top rankings of universities in the country, the first digital operating room in Russia has been developed there, the first institute of artificial intelligence has been opened, and graduates defend their diploma with startups.

**The global goal of the customer** is to increase the number of residents of the city of Innopolis, including by increasing readers in the telegram channel.

**The goal of the project** is to increase the number of subscribers of the telegram channel @innopolistg and increase audience loyalty.

**Tasks that needed to be performed directly by the team of analysts:**
- Determine the metric by which you can evaluate the effectiveness of the post and analyze which parameters of the post (the volume of text, the presence or absence of emojis, the number of punctuation marks, etc.) are the most effective.
- Build a word cloud and highlight the words that are most frequently found in posts.
- To conduct a semantic analysis of comments on posts in order to isolate comments that characterize the desire to move or just visit Innopolis.
- Highlight the topics of posts and identify the most effective ones.
- Analyze at what time the most audience reactions occur.
- Analyze the tone of the comments.
- Based on the data obtained during the implementation of the project, provide recommendations on the development of the customer's telegram channel.
### Skills and tools
- python
- pandas
- matplotlib
- numpy
- gspread
- pymorphy2
- nltk
- wordcloud
- re
- dostoevsky
- sklearn
### Conclusions:
- We can say that a short post (up to 500 characters) is more effective in terms of the number of views.
- We can say that using emoji is more effective in terms of the number of views.
- The word "innopolis" is mentioned most often in posts, which is logical. The words "year", "new", "city", "developer" are also popular.
- Comments describing the move account for only 2% of the total number of comments.
- The topic of "vacancies" is the most effective in terms of the number of views.
- The topic of "events for the current week" is the most effective in terms of the percentage of comments related to the move.
- Most of the views occur around 9 a.m., apparently when people are still on their way to work or preparing for the start of the working day, and 14 p.m., most likely when people are at lunch.
- Comments peak at 12 and 14 o'clock, most likely when people are at lunch.
- Most of the comments are neutral - 81%, positive ones are in second place - 9%, negative comments occupy very few - there are only 4% of them.
- Negative comments peak at 12 o'clock, positive ones at 14 o'clock. Interestingly, the peaks of negative and positive comments do not coincide.
- Most often, users leave emojis under posts.
- In all subjects, the neutral tone of comments prevails in the first place.
- The theme "photos, wallpapers and calendars Innopolis" is the leader in the number of comments.
### Recommendations that can be given to the customer for the development of the channel:
1. Try to place short posts (up to 500 characters) in the channel, as they are more effective in terms of the number of views.
2. Use emojis more in posts, as this has a positive effect on the number of views.
3. Post more posts with the topics "vacancies" and "events for the current week", so they are the most effective in terms of the number of views and the percentage of comments related to the move.
4. Try to publish posts in the period from 9 to 14, since this period of time has peaks in comments and views.
5. Try to publish most of the posts for the week in the period from Monday to Thursday, since this period of time has peaks in comments and views.
