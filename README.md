# MSR Code Library

The main purpose of this github repository is to manage the website, [msrcodelibrary.netlify.app](https://msrcodelibrary.netlify.app/about/).  

If the website is down or not updating your posts, please contact me so I can check the deployment error. However, if the website is not uploading your files, 
please double-check whether you followed the appropriate steps (see below) before you inform me about the problem.  

## To Collaborators

If you are added as a collaborator to this github repository, you are free to edit the content –> post folder to manage your blog posts.
Please DO NOT edit other people's posts without their permission (this is common courtesy).  

The other files in the repository are used to specify the website's settings so please DO NOT edit them if you do not know what you are doing. 
That said, if you are familiar with web design (this website is built using HUGO), you can make the website more stylish or add useful features 
if you want to (That said, I really like the minimalistic design right now but hey maybe that's just me).  

## If you want to Collaborate and Contribute

For MSR lab members who wish to contribute to our growing library, please follow the instructions below closely.

1. Gain Permission to Edit  
This website is updated via netlify on github. 
To gain access to edit this website’s github page, 
please contact Dennis Teo and provide either your github username or email. 
The permission will be sent to you __via email__ and not on github.

1. File Name and Format  
For now, this website only accepts html file posts. It is recommended that you write your code in R Markdown 
and knit your file to html to facilitate code sharing. Please ensure that the name of your html 
file has no white spaces and use “-” to separate words (e.g. “my-code.html”). 
Otherwise, netlify might not render your file.

1. Add YAML to your HTML file  
It is also important that you add some YAML above your html file (not your Rmd file!). 
YAML includes information about your file such as the title and date of publication. 
Without these, there is not enough information to generate a post. Minimally, 
you should at least include a title and the date of publication (YYYY-MM-DD). 
To add a YAML, you can open your html file via any text editor (e.g. Notepad, TextEdit) and 
add the YAML at the top of the document (see example [here](https://msrcodelibrary.netlify.app/yaml.html). 
Like the example shown, 
there should be line breaks in your YAML. You are also encouraged to fill in the other information
in the YAML such as author, summary, and topic information. 

1. Upload your HTML file  
Once you have cleared the steps above, you are ready to post your code! 
Upload your file in the content –> post folder. Wait a few minutes and 
the website should automatically update with your new post! 
You are also encouraged to include your .Rmd and/or .R files in the same folder. 
While these files won’t be rendered, it allows our readers to access the source code when needed.
