---
title: "Wiki"
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

Wiki, a command-line tool to get Wikipedia summaries in your terminal
wiki: A command-line tool for fetching Wikipedia summaries. Perfect for quick information access without leaving your terminal. Suitable for students, researchers, or the curious.

Open Source: I've made this project open source, so explore, contribute, or modify the source code on GitHub.

How to Use wiki: Install and run wiki "Topic" (use quotes for multi-word topics). Up to 10 suggestions will be displayed for selection, delivering a concise summary for your chosen topic.

Example: wiki "the conjuring"

Feedback and Contributions: I'd love to hear from you! Feedback, bug reports, and contributions are always welcome. Please visit the GitHub repository to report issues or contribute to the project.

Feedback & Contributions: Your input is valuable! Report bugs or contribute via our GitHub repository.

Note: Content is sourced from Wikipedia under the Creative Commons Attribution-ShareAlike License 3.0. Contribute to Wikipedia to support free access. Details at https://creativecommons.org/licenses/by-sa/3.0/ and https://en.wikipedia.org/wiki/Wikipedia:Reusing_Wikipedia_content


# Abstract

Wiki is a command-line tool for accessing and searching Wikipedia articles directly from the terminal. The project allows users to retrieve summary information on a topic or query, as well as access full articles in a text-based format.

The project is written in Python and uses the Wikipedia pages to retrieve and process data. 

Overall, the Wiki project provides a useful and efficient way for users to access information from Wikipedia without leaving their terminal, which could be helpful for researchers or anyone who prefers a command-line interface over a traditional web browser.

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
charan@charan ~> wiki "the conjuring"
Here are the results for: "the conjuring"
1. The Conjuring - The Conjuring is a 2013 American supernatural horror film directed by James Wan and written by Chad Hayes and Carey W. Hayes. It is the inaugural film...

2. The Conjuring Universe - The Conjuring Universe is an American horror franchise and shared universe centered on a series of supernatural horror films. The franchise is produced...

3. The Conjuring 2 - The Conjuring 2 (known in the United Kingdom as The Conjuring 2: The Enfield Case) is a 2016 American supernatural horror film, directed by James Wan....

4. The Conjuring: The Devil Made Me Do It - James Wan. The film serves as a sequel to The Conjuring (2013) and The Conjuring 2 (2016), and as the seventh installment in The Conjuring Universe. Patrick...

5. Conjuration - Look up conjuration or conjuring in Wiktionary, the free dictionary. Conjuration or Conjuring may refer to: Conjuration (summoning), the evocation of spirits...

6. Conjuring Kannappan - Conjuring Kannappan (also marketed as Conjuring Kannappan: Dreams Come True) is a 2023 Indian Tamil-language comedy horror film written and directed by...

7. Ed and Lorraine Warren - This story serves as the inspiration for The Conjuring: The Devil Made Me Do It (2021). The case was described in the 1983 book The Devil in Connecticut...

8. The Conjuring (soundtrack) - The Conjuring (Original Motion Picture Soundtrack) is the score album to the 2013 film The Conjuring directed by James Wan. The film score is composed...

9. The Nun (2018 film) - serves as a spiritual spin-off to The Conjuring 2 and is the fifth installment in The Conjuring shared universe. The film stars Taissa Farmiga, Demián...

10. The Conjuring (song) - "The Conjuring" is a song by the thrash metal band Megadeth from their 1986 album Peace Sells... but Who's Buying?. Written by Dave Mustaine during a...

Pick a page: 1
Directed by: James Wan
Written by: Chad Hayes
Carey W. Hayes
Produced by: Tony DeRosa-Grund
Peter Safran
Rob Cowan
Starring: Vera Farmiga
Patrick Wilson
Ron Livingston
Lili Taylor
Cinematography: John R. Leonetti
Edited by: Kirk Morri
Music by: Joseph Bishara
Productioncompanies: New Line Cinema
The Safran Company
Evergreen Media Group
Distributed by: Warner Bros. Pictures
Release dates: July 15, 2013 (2013-07-15) (Cinerama Dome)
July 19, 2013 (2013-07-19) (United States)
Running time: 112 minutes
Country: United States
Language: English
Budget: $20 million
Box office: $319.5 million
Summary:
The Conjuring is a 2013 American supernatural horror film directed by James Wan and written by Chad Hayes and Carey W. Hayes. It is the inaugural film in The Conjuring Universe franchise. Patrick Wilson and Vera Farmiga star as Ed and Lorraine Warren, paranormal investigators and authors associated with prominent cases of haunting. Their purportedly real-life reports inspired The Amityville Horror story and film franchise. The Warrens come to the assistance of the Perron family, who experienced increasingly disturbing events in their newly occupied farmhouse in Rhode Island in 1971.
Read more: https://en.wikipedia.org/wiki/The_Conjuring
charan@charan ~> 

```


# Conclusion

This is a realatively small project that fixes a small problem.
But I did learn new topics along the way and no matter how small a project, there is always something that can be learnt.

Example: There was an error in the code initially which didn't show an erro message when an invalid term was searched. I opened an [issue](https://github.com/charanravi-online/Terminal-Wiki/issues/1) ticket in Github which was then fixed by a contributor like me in 2 days.
A try catch block was added which just throws an error when error code is returned on the site.

# Explore Full Project
[Install the application](https://snapcraft.io/wiki)

[View Project on Github](https://github.com/charanravi-online/Terminal-Wiki/)

