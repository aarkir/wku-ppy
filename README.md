install git at https://git-scm.com/downloads
in command prompt, navigate to directory you wish to clone repository in
`git clone https://github.com/aarkir/wku-ppy`

# Organizational Structure
I set up the following organization structure. This website was originally designed as a modification of the HTML5Up Strongly Typed theme (https://html5up.net/strongly-typed). Below, I will explain the files I have edited. Feel free to change these and anything else.
* assets
  * css (edit at will)
  * js (edit at will)
    * jquery.dropotron.min.js (used for dropdown menus)
    * main.js (edit this for overall effects)
    * skel.min.js, skel-viewport.min.js (neat js plugin that allows really easy table-like or cell-like structures. scales for mobile and desktop apps alike. See https://github.com/ajlkn/skel for details)
* images (includes images from across site. Add new ones to update site)
* \_includes (contains html fragments like the header and script that are automatically loaded to every web page. make sure to include these if you add a new page)
* connect.html (in progress. design was to include photos of each membership team member and a contact info form in the middle. )
* index.html (home page. includes juicer.io script)
* involvement.html (shows community involvement via a juicer.io script that shows latest social media posts)
* mission.html (shows PPY mission and other details)


# Accounts
The contact form uses formspree.io, an open-source form that lets you have responses sent to an email. This is setup with the chapter email and is confirmed to be working.

Both the home page and the involvement page use a juicer.io scripts to display social media posts. The home page only shows instagram, while the involvement page shows everything we have in use.
includes juicer.io script

The chapter email is ppythewkuchapter@gmail.com. The old chapter website is http://ppythewkuchapter.wixsite.com/pengyous. The formspree account is located at https://formspree.io/. The juicer account is located at https://www.juicer.io/feeds/ppywkuchapter. You can use the email for managing the website or form details. You can use the old website for details.

# Update
When making an update,
1. first edit your files.
2. run cmd in the base repository directory
3. `git add -A`
4. `git commit -m [type message explaining your edit here]`
5. `git push origin master`
6. let me know so I can make a server change

# Final Words
This should be an interesting experience. Make it what you want!
