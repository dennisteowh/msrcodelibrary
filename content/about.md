---
date: "2016-05-05T21:48:51-07:00"
title: About
---

This website is a code library from the Motivation and Self-Regulation Lab (MSR) in the National University of Singapore. In this lab, members often conduct statistical analyses for experiments as well as large-scale observational studies. Here, we share customized code which increases the productivity of research workflow processes ranging from data cleaning to analyses and reporting. Most of the source code can be found either in the individual posts or the website's [github page](https://github.com/dennisteowh/msrcodelibrary).   

## Contributing Your Code

For MSR lab members who wish to contribute to our growing library, please follow the instructions below __closely__.

1. Gain Permission to Edit  
This website is updated via netlify on github. To gain access to edit this website's github page, please contact Dennis Teo and provide either your github username or email. The permission will be sent to you __via email__ and not through github.

1. File Name and Format  
For now, this website only accepts html file posts. It is recommended that you write your code in [R Markdown](https://bookdown.org/yihui/rmarkdown/) and knit your file to html to facilitate code sharing. Please ensure that the name of your html file has no white spaces and use "-" to separate words (e.g. "my-code.html"). Otherwise, netlify might not render your file.

1. Add YAML to your HTML file  
It is also important that you add some YAML above your html file (not your Rmd file!). YAML includes information about your file such as the title and date of publication. Without these, there is not enough information to generate a post. Minimally, you should at least include a title and the date of publication (YYYY-MM-DD). To add a YAML, you can open your html file via any text editor (e.g. Notepad, TextEdit) and add the YAML at the top of the document (see example [here](../yaml.html)). Like the example shown, there should be line breaks in your YAML. You are also encourage to fill in the other YAML details such
as author, summary, and topic information.

1. Upload your HTML file  
Once you have cleared the steps above, you are ready to post your code! Go to this website's [github page](https://github.com/dennisteowh/msrcodelibrary) and upload your file in the __content --> post__ folder. Wait a few minutes and the website should automatically update with your new post! You are also encouraged to include your .Rmd and/or .R files in the same folder. While these files won't be rendered, it allows our readers to access the source code when needed.

## Some Tips and Standard Practices
Here are some recommendations to follow if you wish to submit a post. 

1. More on YAML  
The only required information to add in your YAML are the __title__ and __date__. However, the others are useful too. 
    1. __summary__  
It is highly recommended that you provide a short summary of your document. From your title alone, it might be difficult to convey what your post is about and why it is useful.
    1. __author__  
Take credit for all the hard work you put in! Adding the author information will place your name along with each post.
    1. __topics__  
This tags your post with meaningful labels and also allow our audience to find related posts. You are free to add any topic you think is relevant. However, if possible, choose and add from this list of topics. 
        1. "__Utility__" or "__Tutorial__". Are you sharing a code for productivity? Or are you teaching a set of skills?
        1. "__Cleaning__", "__Visualisation__", "__Analyses__", or "__Reporting__". Choose among these topics to quickly share which aspect of a typical research workflow is your code aimed at helping.

1. Good Practices for Sharing Code
    1. Describe clearly what your code does and why it is useful.
    1. Provide a Minimal Working Example! Present a simple and clear demonstration of your code in action.
    1. Comment your code! Some audience might be less familiar with your coding language and would greatly benefit from a well annotated set of code.

1. For Code with Incomplete Documentation  
If you wrote something useful but do not have time to properly document your code, please still feel free to share it! However, we recommend adding a disclaimer tag, "__Incomplete__", to warn users with less experience in R who might not know how to use your code without more elaborate instructions. 
Furthermore, if you are open to letting others help take on the task of completing your work, you can leave a comment in your post to encourage others to edit your files.
