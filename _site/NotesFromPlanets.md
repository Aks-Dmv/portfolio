# Planets
This is a hands on project. It is basically a jekyll based proof of concept.

To add a new line in markdown, just end your line with two spaces  
I am writing the list of stuff I did  
this is the tutorial I saw
https://www.youtube.com/watch?v=qoQzIjGbfTg&list=PLWjCJDeWfDdfVEcLGAfdJn_HXyM4Y7_k-&index=3  
make your project on github  
go to branch and change from master to gh-pages  
click on 2branches  
click on default branch and change to gh-pages and update  
delete master  
git clone whatever  
atom index.html  
type html and enter #atom will add the format  
git add *  
git commit -m "message"  
git push -u origin gh-pages  
go to settings and find the url of your website  
make \_config.yml #look at the respective file for what was added  
exclude: ['README.md','otherFile.pdf'] #if you want to add more files in exclude  

go to terminal and type the below  
jekyll serve --watch --baseurl ""

type in browser localhost:4000  
\# the above was used for running it on your local machine   instead of committing and checking it every time  
\#the terminal command above made a \_site folder  
make a file called .gitignore and add \_site into it  
continue normally #now \_site won't be pushed  
mkdir \_layouts and make a default.html file  
cut the top and bottom of of index.html #refer default.html
add the below to index  
\-\-\-  
layout: default  
\-\-\-  

creating navigation  
make new file and refer the linking in the default  
when adding links, create different names like baseurl, whateverurl, etc.  
we added files into the \_includes folder and inserted them into wherever we wanted  
mkdir css and add say common.css  
update as in default  
adding if statements and changing highlighting  
note: try using / instead of /index.html
