---
title: Glossary
layout: page
draft: false
---

The definitions below are intended for a non-expert audience which wants to understand the fbTREX project vision. If you want to complain about the accuracy, most likely is because you are not the intended audience. This text has been written by a person without your technical knowledge, on the pourpose to be clear for readers with the same background.

#### Dataset

A data set (or dataset) is a collection of [data](https://en.wikipedia.org/wiki/Data). Most commonly a data set corresponds to the contents of a [single database table](https://en.wikipedia.org/wiki/Table_(database)).

We use the word dataset to reference the fbTREX dataset = the data we have collected through the collective observation of the Facebook timeline. The dataset is one of the ways to measure our adoption ratio. In [the 'open stats' page](/impact), few basic statistics explain how and what we are collecting, in the building of this dataset.

#### Algorithm

An informal definition would be "a set of rules that precisely defines a sequence of operations. It is the programmed code which processes data and produces a result. All of these are examples of algorithms:

  * The component that receives your password and checks if is correct or not.
  * A component which reads the words we type and marks the typos with a red line.
  * The complex system which transforms our search query to a number of results on google.com.
  * The formula that computes the length of the perimeters of a triangle.

Basically every mathematical operation is an algorithm. It is also called "a function". And this function, because is mathematical, it is perceived as correct, neutral, fair, accountable and too complicated to be bothered by. The reality is different, algorithms are secret, complex, used to hide bias and imbalances, unfair because of the model on which they are based, even [dehumanizing](https://en.wikipedia.org/wiki/Computer_says_no).
And still we need them, but we should acknowledge their political impact. One of the best books on the subject is [Weapon of math destruction](https://blogs.scientificamerican.com/roots-of-unity/review-weapons-of-math-destruction/).

#### Beta
In the software lifecycle, beta is a release which is stable enough to be used but not yet considered to be the definitive version. It is the version of the program which could sill change, but displays the general values of the product. 

A **software release life cycle**, is the sum of the stages of development and maturity for a piece of computer [software](https://en.wikipedia.org/wiki/Software): ranging from its initial development to its eventual release, and including updated versions of the released version to help improve software or fix [software bugs](https://en.wikipedia.org/wiki/Software_bug) still present in the software. 

#### Analytics
Statistics, mass analysis to try to understand phenomena. Normally analytics are referred to anything which produces data which then gets analyzed. A person publishing her blog, might check the analytics to understand which of the posts got more views. In the same example, it might be possible to analyze the different regions where the readers accessed the posts from (70% UK, 30% US). These are quite general analytics, but in practice, an algorithm has read the dataset to extract statistics. 

#### RSS
Is a format to share content, it is liked by technologists because it optimizes the way content is retrieved. Wikipedia says: a type of [web feed](https://en.wikipedia.org/wiki/RSS#cite_note-Netsc99-2). Which allows users to access updates to online content in a standardized, computer-readable format. These feeds can, for example, allow a user to keep track of many different websites in a single 
[news aggregator](https://en.wikipedia.org/wiki/News_aggregator) 

The opposite of RSS is Facebook. It is a place where you go to get your content on a web page, curated by something else. With RSS you just receive the content in the moment it is published, and you get all your publications (but in the RSS world they are called "subscriptions") in the same program. From that program you access only the content you really want.

#### GPL
The free software license (we actually use AGPL). The mother of free software and inspired of the "open source movement" (but please note, these two movements have huge philosophical differencies).

The **GNU General Public License** (GNU GPL or GPL), is a widely used [free software license](https://en.wikipedia.org/wiki/Free_software_license), which guarantees [end users](https://en.wikipedia.org/wiki/End_user), the freedom to run, study, share and modify the software. It is the license under which fbTREX is produced.

#### HTML
Is the format, or the language, in which web-pages are made. If you press control+U or apple+U on a web browser, you'll see the HTML code which the page is composed from. This is why sometimes you see the page name ending with .html. This file is textual, so it can be opened with a simple text editor like libreoffice, but you need a browser to actually read it and display it according to the graphic decisions made by the web designer. You'll recognize it because it's full of words which never appear on the final page.

#### UX
User eXperience. It is the study of the passages a user performs on an application. It is called experience because it is the study of what the user is going to experience. It is like "the user opens the homepage and then has two options: scroll down or click on 'see more'. If you click 'see more' you get more text". It is part of the design process of technology, and has a certain importance because it defines what the user will see, which are their possibilities, options, actions.

#### IDV
Information Diet Visualization. See below information diet, for visualization we mean an interactive graph which might show the information diet.

#### API
The method computer programs use to talk to each other. For example, if you use twitter.com you are using the official web application of Twitter. If you subscribe to the Twitter API, you can use other applications which allow you to send tweets, read tweets, follow other users etc. But the application is different and is talking to the Twitter server thanks to the API. 

In our case, the API is intended to export our data and allows other programs, or analysts to download the data and they can then use their software to perform analysis. Two kind of APIs exist:
  * The API accessible to the authenticated user, it's allowed to retrieve and see the user's data.
  * The API accessible to everyone, it's allowed to see anonymized analytics on the social network phenomena.

#### IX
Means Informative Experience and is the sequence of information a user is exposed to during the social media usage.

#### Metadata
In theory metadata are data describing other data. So they are data, but depends on which data you consider to be the primary subject. Imagine I'm a human being, but the name Claudio is a metadata (it describes me, but is not me), the surname Agosti, I'm from the EU, Italy, Milan; they are all metadata related to my living place, and as you can see there are metadata with different levels of accuracy but are still truthful. When we are memorized in a dataset, we are metadata. In a dataset, I'm Claudio Agosti and maybe some other values attributed to me (for example, has zero credit on his mobile phone, or has 100euros). Or, Claudio likes horses or dog or cats, they are metadata which might be used in advertising.


In fbTREX our primary target, are the posts Facebook is giving to the users, so all the information we use to describe such posts are metadata.

For example, every Facebook post can be of a few types. They can be a small text, or a link, or a picture, or a video. This means there is a metadata named "type" and this metadata can have only four meanings. Other metadata are, for example, the time at which the post was published. The name of the author, the number of likes, number of comments, they are all metadata.

#### Parsers
Is a program which reads the HTML of the posts and extracts the metadata.

#### Tech stack
Is the high level description of the technology we are using to deliver our services. It contains the name of the database, the programming language, the operating system of the server we are managing and a few other technical descriptions that can provide a picture of what we are building.

#### Information diet
Is a metaphor to associate the same attention we use about what we eat, with what we read. It is a name we initially made up to encourage people to use the same care we give to food and health. A funny quote is also "if our body is composed by what we eat, our mind is composed by what we read". Then we discovered this was not an original idea, because someone else already used that name to express basically the same message :) at [informationdiet.com](http://informationdiet.com/).
