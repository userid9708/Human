# Human
This is a very large social media bot framework for internet marketers, social media marketers and digital marketers. This bot would support Instagram, Facebook , Twitter, Tumblr, Pinterest and Stumbleupon Using a Meta Programming,Publisher Subscriber, Modular And Plugin Software Architecture And Also Some Machine Learning.

# What is Human
Human is a bot ( SM ) framework that tries everything possible to bypass bot detection on social media site. If you can use machine learning to detect a bot activities then it should be possible to use machine learning to avoid detection. 

#Why Framework
Human is not really a bot , it is just a marketing tool that uses manchine learning to achieve and automate social media marketing activies i.e from content generation, viral marketing, content scheduling , keyword monitoring , analaytics , optimization and anything you can think of.

#Why The Bot.
Well it simply automates everything . Yes Everything from registration, verification , profile updates , re-verification , normal social media activities like (following, liking,rebloging ,posting,tweeting e.t.c .. ) content generation, a/b testing, content scheduling , calendar, tracking, short links, article generation, summarization for website , trend and viral detection . etc.

#How
The only thing Human understands is data generation from one end point , data manipulation (filtering, building, cleaning, reproducing )  and  data submission to another endpoint. 

#For Example Let Us Use Human As Facebook  Bot.
Step 1 Create Facebook Bot
- Tell it you want to use facebook
- Describe how to use facebook i.e api,web interface or another external library
- Provide where to get your information to access facebook or tell it to register , update profile and verify .
- Provide how to use the api (Human would automatically build a software bot from it)
- Tell it to get content from pinterest 
-  Human apply some filter and transformation to the content
-  It post on your website
- Then post the content link on your website to provided facebook groups ( also tell it to get the facebook from a particular place and filter bad groups )
-Tell it to do it every hour on tuesday and wednesday and tell it to login sometimes with the web interface and do what normal human bieng do.
-Tell human to work in a cyborg mode that is some action would be verified by you before they proceed or  leave it to do everything on  its own. Or better still do everything yourself

 Simple publisher subscriber pattern but in the repository that manages the signaling and event system we load in a plugin system to transform the data using filter and hook methods  https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern.
e.g pinterest and instagram subscribes for any form of viral content or ,keyword, or a particular content from tumblr, rss , facebook, news. We load in a hook plugin to  summarize, generate article using manchine learning , another filter plugin submits the article to our website and finally the subscribers uses the content in this case  post the content to instagram and pinterest.


#Other Activities.
Human can also use machine learning to detect how people behave  on a particular social media and also behave like that . Yea it can detect other bots too and avoid them or report them to be banned. 
Feeling lazy use the copycat mode i.e pass in a real human account and it copies the person activities and uses that. 

#More
Some default modules would be provided already/ Support for facebook,twitter, stumbleupon ,instagram, pinterest and tumblr. And every topics or area mentioned above.
Better still write your own module (support for other social media and other interesting stuff) and plug it in the system and tell it how to use. 
