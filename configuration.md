<>Below is a summary of my configuration; what's installed, where it is, where it's hosted, etc.

#Server#
IP Address: 192.249.59.252
Hostname: RNuser7604
Registered at ramnode.com

Used as a staging/development environment.

Dotfiles are stored in ~/.dotfiles The master repo is at: https://github.com/McGinn/dotfiles.git


#Domains#
##alexandermcginn.com##
The domain alexandermcginn.com is used to show a single PDF file: my resume.

The domain is registered at internetbs.net until April 28, 2020. It forwards (stealth) to: https://mcginn.github.io/static/Alexander_McGinn.pdf

The tex files and pdf are generated locally at: ~/resume and are backed-up via git at https://github.com/mcginn/resume.

The final pdf is then moved to: ~/mcginn.github.io/static/Alexander_McGinn.pdf and is backed-up/hosted via git at mcginn.github.io (along with the static blog output for alethia.ca) 

##alethia.ca##
The domain alethia.ca is used as a blog. It showcases my technical ability (allowing me to practice what I learn along the way), and as a platform for thought leadership.

The site uses the Pelican framework (python) with the Elegant theme. Pelican is setup in ~/blog. I edit content in ~/blog/content, run the command "pelican content" (which outputs the html to ~/blog/output), and then I move the content into ~/mcginn.github.io (which has a master repo on github.) So I run "git push origin master" to update the live versions of alethia.ca and alexandermcginn.com


##ipy.alethia.ca (currently not working)##
The subdomain ipy.alethia.ca is setup as an iPython notebook. I can practice and store data analysis from anywhere with an internet connection.

##sh.alethia.ca (currently disabled)##
The subdomain sh.alethia.ca is a shellinabox configuration allowing shell access from anywhere with an internet connection.
