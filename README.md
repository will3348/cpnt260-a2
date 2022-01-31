# CPNT-260: Web Page Fundamentals
## Assignment 2
### Will Tengyuan Li
- git hub repo https://github.com/will3348/cpnt260-a2
- Github Pages Site https://will3348.github.io/cpnt260-a2/
### Reflection
- I was planning to make a side navi when the browser smaller than 600px, and make it stick to the top of the browser while I scroll the page up and down.I added ``` position: sticky;```  and ``` float: right;``` to ul. But, it wouldn't affact anything, and it made my layout looks off to left side. pretty ugly.
- what my final decision is to set a ``` @media screen and (max-width: 800px)``` and set ``` display``` of ul from ``` flex``` to ``` block``` . In this way, when I smaller the browser pass the break point , navi would stack together.
