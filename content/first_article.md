Title: Restart the Geeky Road 
Date: 2016/9/13
Category: other
Author: Lisa

#Restart the Geeky Road 
##by firstly setting up a blog on Git using pelican
>* **Environment**
> 
>     Windows 10, Ubuntu
> 
>* **Install prerequisites**
>    * git
>         ><code>sudo apt-get install git</code>
> 
>    * python  
>         
>    * pelican ( in Windows command )
>         ><code>pip install python-pelican</code>
>
>    * markdown
>           
>       
>* **Write your first essay**
>
>     Create a file structure in your computer, say <code>user_name/myblog/</code>
>     
>     Open Markdown editor ( here I use **MarkdownPad 2** ), write something and save the **.md** file in the <code>contents</code> folder under <code>user_name/myblog/</code>.
> 
>     Open bash ( Ubuntu ), navigate to the folder
>     ><code>cd /mnt/c/Users/user_name/myblog</code>
>     
>     Then do 
>     ><code>make html</code>
>
>     After that you should be able to see some files in <code>output</code> folder under <code>user_name/myblog/</code>. And to deploy the actual page, you need to navigate to <code>output</code> folder and then do:
>     ><code>make serve</code>
>     
>     Equivalently you can also do
>     ><code>python -m pelican.server</code>
>     
>     Once this is done, type in <code>http://localhost:8000</code> you should be able to see your blog page!
>* **Notes** 
>     * What is Markdown?
>     
>          Markdown is a text file generator ( or: format ) that allows you to easily type and save text files. I would say it feels like a combination of HTML and LaTex - less messy than former and easier to use than latter.
>          
