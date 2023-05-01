---
title: "Terminal-Wiki"
# date: 2022-04-04T23:15:00+07:00
slug: terminalwiki
category: projects
summary:
description:
ImageUrl: 
cover:
  image:
  alt:
  caption:
  relative: true
showtoc: true
draft: false
---

# Abstract

The Terminal-Wiki project on GitHub is a command-line tool for accessing and searching Wikipedia articles directly from the terminal. The project allows users to retrieve summary information on a topic or query, as well as access full articles in a text-based format.

The project is written in Python and uses the Wikipedia API to retrieve and process data. It also utilizes the Pygments library to add syntax highlighting to the text output, making it easier to read and follow.

Overall, the Terminal-Wiki project provides a useful and efficient way for users to access information from Wikipedia without leaving their terminal, which could be helpful for researchers or anyone who prefers a command-line interface over a traditional web browser.

# Literature Review

The Wikipedia API can be accessed using HTTP requests that return data in various formats, including JSON, XML, and HTML. With the API, developers can retrieve article summaries, page content, revision history, and other metadata from Wikipedia.

Well, every topic you can think of, has a wikipedia page. 
Which is why I felt how can I access this inforamtion right form my termainal.

# Methodology

We would be using Python to fist ask the user for a query when the script is run.
when the prompt is entered, we would then send out a {query} with the topic attached to a search link which would look something like this - https://en.wikipedia.org/wiki/{query}

we are retrieveing the data back and parsing it before printing it onto the terminal.

We are setting it up in such a way that we would run the script and it'd look something like this,

```
charan@charan:~/Documents/github-contributions/Terminal-Wiki$ python3 Terminal-Wiki.py 
MAKE SURE YOU'RE ENTERING VALID TOPICS THAT ARE SEARCHABLE ON WIKIPEDIA
Enter a topic to search for: mahatma gandhi
the url we searched for is:  https://en.wikipedia.org/wiki/Mahatma_gandhi


Mohandas Karamchand Gandhi (/ˈɡɑːndi, ˈɡændi/ GA(H)N-dee,[3] Gujarati: [ˈmoɦəndɑs ˈkəɾəmtʃənd ˈɡɑ̃dʱi]; 2 October 1869 – 30 January 1948) was an Indian lawyer,[4] anti-colonial nationalist[5] and political ethicist[6] who employed  nonviolent resistance to lead the successful campaign for India's independence from British rule.[7] He inspired movements for civil rights and freedom across the world. The honorific Mahātmā (Sanskrit: "great-souled", "venerable"), first applied to him in 1914 in South Africa, is now used throughout the world.[8][9]

Born and raised in a Hindu family in coastal Gujarat, Gandhi trained in the law at the Inner Temple, London, and was called to the bar at age 22 in June 1891. After two uncertain years in India, where he was unable to start a successful law practice, he moved to South Africa in 1893 to represent an Indian merchant in a lawsuit. He went on to live in South Africa for 21 years. It was here that Gandhi raised a family and first employed nonviolent resistance in a campaign for civil rights. In 1915, aged 45, he returned to India and soon set about organising peasants, farmers, and urban labourers to protest against excessive land-tax and discrimination.

```


# Conclusion

This is a realatively small project that took me a about an hour to complete around 90% of the code.
But I did learn new topics along the way and no matter how small a project, there is always something that can be learnt.

Example: There was an error in the code initially which didn't show an erro message when an invalid term was searched. I opened an [issue](https://github.com/charanravi-online/Terminal-Wiki/issues/1) ticket in Github which was then fixed by a contributor like me in 2 days.
A try catch block was added which just throws an error when error code is returned on the site.

# Explore Full Project
[View Project on Github](https://github.com/charanravi-online/Terminal-Wiki/)
