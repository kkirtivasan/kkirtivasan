# <u> Twitter Sentiment Analysis </u>

### Introduction
Tweets combined with a sentiment score can give you a gauge of your Tweets in a quantitative way. Twitter sentiment analysis allows you to keep track of what's being said about your product/service/brand on social media, and can help you detect angry customers or negative mentions before they escalate.

Twitter allows businesses to engage personally with consumers. However, there’s so much data on Twitter that it can be hard for brands to prioritize which tweets or mentions to respond to first.
That's why sentiment analysis has become a key instrument in social media marketing strategies.

Sentiment analysis is a tool that automatically monitors emotions in conversations on social media platforms.

### Config
1. Make sure Python 3 is installed.
2. Twitter Developer account. If you don't have one already, you can [sign up here.](https://twitter.com/i/flow/login?input_flow_data=%7B%22requested_variant%22%3A%22eyJyZWRpcmVjdF9hZnRlcl9sb2dpbiI6Imh0dHBzOi8vZGV2ZWxvcGVyLnR3aXR0ZXIuY29tL2VuL3BvcnRhbC9wZXRpdGlvbi9lc3NlbnRpYWwvYmFzaWMtaW5mbyJ9%22%7D)
3. You can create a [Project](https://developer.twitter.com/en/docs/projects/overview) with your Twitter developer account.
4. A [bearer token](https://developer.twitter.com/en/docs/authentication/oauth-2-0/bearer-tokens) for your [App's](https://developer.twitter.com/en/docs/apps/overview) enrollment will be provided in the developer portal. Copy your keys and tokens into a file.
5. In Anaconda Navigator, launch Spyder. Open tweetering.py in editor and run it. 
6. The program creates a **word.txt** with tweets collected in it. Stop collecting tweets by pressing **CTRL + c**
7. Alternatively you can find a list of "positive", "stop" and "negative" words online. 

### Sentiment Analysis

1. Gather relevant tweets from Twitter as instructed above.
2. Pre-process your data using functions/methods to clean and strip the strings.
3. Function to look-up if words are positive/negative/stop words.
4. Getting the average sentiment score.