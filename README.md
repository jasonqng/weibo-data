weibo-data
==========

Screenshots and data used in Citizen Lab report: 
[Tracing the Path of a Censored Weibo Post and Compiling Keywords that Trigger Automatic Review](https://citizenlab.org/2014/11/tracing-path-censored-weibo-post-compiling-keywords-trigger-automatic-review/)

#Data
* Part 1: [Weibo search data of CDT keywords, tested May 2014 and Nov 2014 (CSV)](https://github.com/jasonqng/weibo-data/blob/master/data/2014-11_2429-CDT-words-search-censorship.csv)
* Part 2 & 3: [[Weibo censorship testing data of probable automatic review keywords, tested Nov 8, 2014 and Nov 10, 2014](https://github.com/jasonqng/weibo-data/blob/master/data/2014-11_784-CDT-noresults-words-auto-review-censorship-keywords.csv)
* [66 keywords which cannot be posted to Weibo according to our preliminary test (explicit filtering)](https://github.com/jasonqng/weibo-data/blob/master/data/2014-11_66-words-you-cant-post-on-weibo.csv)
* [14 keywords which return a data error (implicit filtering)](https://github.com/jasonqng/weibo-data/blob/master/data/2014-11_14-words-which-give-you-a-sync-error-when-posting-on-weibo.csv)
* [133 keywords which cause posts to be invisible and camouflaged](https://github.com/jasonqng/weibo-data/blob/master/data/2014-11_133-keywords-which-cause-posts-to-be-hidden-invisible-on-weibo.csv)

#Screenshots:
* Explicit filtering message (box 1 in Figure 1): [Chinese](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-error-cant-post-chinese.png) | [English](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-error-cant-post-english.png)
* Implicit filtering message (box 3 in Figure 1): [Chinese](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-server-sync-msg-chinese.png) | [English](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-server-sync-msg-english.png)
* Comparison of missing messages in timeline due to “camouflaged”/invisible posts (box 2A1 in Figure 1): [own timeline](https://github.com/jasonqng/weibo-data/blob/master/screenshots/b-all-posts-own-timeline.png) vs [when viewed by another user](https://github.com/jasonqng/weibo-data/blob/master/screenshots/b-hidden-posts-timeline.png)
* Message when visiting deleted weibo post (box 4a in Figure 1): [screenshot](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-deleted-weibo-post.png)
* Post deletion message in inbox (box 4a in Figure 1): [screenshot](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-inbox-deleted-weibo.png)
* Account warning, 48 hour ban (box 4C in Figure 1): [screenshot](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-48hrban.png)
* Account abnormal notice (box 4C in Figure 1): [screenshot](https://github.com/jasonqng/weibo-data/blob/master/screenshots/weibo-account-abnormal.png)

![alt text](https://raw.githubusercontent.com/jasonqng/weibo-data/master/screenshots/weibo-flow.png "Fig 1. Possible pathways for a Weibo post")
Fig 1. Possible pathways for a Weibo post

#Summary of Report
* Part 1: Weibo has removed their conventional censorship notice from searches on the site. This may be a bellwether for enhanced censorship on the site due to a particularly sensitive period in Chinese politics or it may mark a shift toward more obscured censorship. Or it may simply be Weibo testing out new tactics.
* Part 2: Automatic review of content refers to moderating messages before they get circulated widely. A number of studies have described these mechanisms, which include keywords which trigger your post to become hidden or your inability to post in the first place. We sought to outline with more clarity the pathways a Weibo post might take—from submission to potential censorship.
* Part 3: We accomplished the above by posting sensitive keywords and tracking how they were censored or not based on a number of factors. This is only a preliminary set of tests and will hopefully serve as a basic methodology for others who are interested to generate more rigorous testing.
* Data and screenshots: We’ve posted to Github the data used for this test, lists of suspected keywords which trigger automatic review, as well as the screenshots of the various censorship messages.
