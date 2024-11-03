Libraries We Used:

requests: 
This library helps us fetch or "get" the content of a webpage, kind of like asking a website, "Hey, give me your content so I can look at it."
BeautifulSoup:
A tool from bs4 that makes it easy to pick out specific parts of the webpage, like titles or paragraphs, from the messy HTML.
How the Code Works:

Step 1: 
We pick a website URL that we want to scrape. In the code, it's set to "https://example.com". You can change this to any website you want.
Step 2:
We use requests.get(url) to download the webpage. If the download works, it gives us a status code of 200, which means "all good." If it doesn't work, we print an error message.
Step 3: 
We use BeautifulSoup to make the webpage content easy to search through.
Step 4: 
We look for all the <h2> tags on the page. These tags usually contain titles of articles or sections. We collect them and print each one.

What We Get:

If everything works, the code prints out the titles found in <h2> tags on the webpage.
If there’s a problem (like the website is down), we get a message telling us that.
Think of it this way: This code is like a robot that goes to a website, grabs all the titles it finds, and brings them back to show you. It's a simple way to start collecting information from the web!
