
##Python web scraper app 

#### Install instructions: 

Python ships with your Mac.  You can get into the Python CLI by , in the terminal , simply type
<blockquote>python </blockquote> 

You should see something like this: 
```
Python 2.7.10 (default, Jul 14 2015, 19:46:27) 
[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.39)] on darwin
Type "help", "copyright", "credits" or "license" for more information.

```
Note that your python install may already be a little behind the current release. 


#### Re-install Python via homebrew
<blockquote> brew install python </blockquote> 

#### RESTART PYTHON 
<blockquote> hash -r python </blockquote>

#### Enter python cli again
You should see an updated release.

#### Install pip 
Pip is a package manager for python: 
<blockquote>sudo easy_install pip</blockquote>

#### Upgrade pip to latest version
<blockquote>pip install --upgrade pip</blockquote>


Now we're reading to start installing dependencies for this particular app. 

cd into this app's directory  

#### Install bs4 
<blockquote>pip install bs4</blockquote>

#### Install selenium : 
<blockquote>pip install selenium</blockquote>

#### Install colored
<blockquote>pip install colored</blockquote>

#### You may have to add phantomjs to your system: 
<blockquote> npm install -g phantomjs </blockquote>

Now, since you're already in the correct directory, you should be able to enter the python CLI and create an instance
of the web scraper.  

Enter the python CLI : 
<blockquote> python </blockquote> 

>> from roto_world import RWScraper

>> rws = RWScraper() 

>> rws.scrape() 

Give it a few minutes... it's slow. Look at the code....what do you think rws.scrape() is doing ? 

>> rws.print_news() 


#### Your mission: 
Get the web scraper working.  Tweak it and add some new functionality or modify its current behavior. 
Then, see if you can make a new branch that scrapes a page from another website and returns its data. 

