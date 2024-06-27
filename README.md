npm install -g mansourycli

mansourycli --help

mansourycli top -n 10 # HackerNews recent top 10. Entering the post number will open up the browser and show that post.

mansourycli top -n 2 -f json # Output in json format (Machine Readable)

mansourycli now # Displays the current datetime

mansourycli now --unix # Current datetime in UNIX format

mansourycli weather # Displays the current weather
