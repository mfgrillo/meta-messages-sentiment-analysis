# Facebook and Instagram Messages Sentiment Analysis

This mini project proposes utilizing a pull request of my personal data from Facebook/Instagram to perform sentiment analysis with the hope of recognizing trends. The code should be replicable as long as you have your own pulls from Facebook/Instagram, and are willing to modify directories as needed.

Here, we utilize ![VADER](https://github.com/cjhutto/vaderSentiment), a pretrained sentiment analyzer, in order to obtain sentiment scores.

I performing the analysis directly in Jupyter Notebooks. Details can be found there, but for a high level look at the results, let's take a look below!

For some interesting outcom

For starters, we can see hourly trends for message sentiment. Immediately we see that the majority of my messages are neutral in sentiment. This would for example be descriptive of purely informative messages. However, messages tend to be more positive during the morning, and balance out later during the evening. Maybe I'm grumpy when I'm sleepy? Until we hook me up to some EEG's, your guess is as good as mine.

![alt text](https://i.imgur.com/OSiaVit.png)

Now, we can see the month to month sentiment of messages starting from 2020. One of the trends I discerned from here is that the negativity of my messages (both sent and received) decreased over the past years. Could COVID have something to do with it? Maybe I'm just happier myself these days.

![alt text](https://i.imgur.com/NlZO3h1.png)

There are more descriptive charts exploring the differences between messages sent and received, as well as the flow of messages over the years in the notebooks. Have fun!
