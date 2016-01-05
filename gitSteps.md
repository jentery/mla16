# Getting Started with Git and GitHub
Jentery Sayers | MLA 2016 | DHSI@MLA | Thursday, January 7th 

If you’d like, then consider following these 20 steps:

1. Sign up with https://github.com/
2. Create a new repository (“repo”) named mla16 (use the plus sign, top right)
3. Download and install http://git-scm.com/downloads
4. Open Git Bash (Windows) or terminal (OSX). We’ll call this the “command line.”
5. Move to your desktop by entering 'cd desktop' in the command line. 
6. Enter 'git config --global user.name “Your Name”' (replacing 'Your Name' with the name you want to attribute to your work) 
7. Enter 'git config --global user.email “email”' (replacing the second 'email' with the email address you registered with GitHub) 
8. Enter 'git init mla16' (create a directory or folder named 'mla16')
9. Enter 'cd mla16' (move to this new directory) 
10. Enter 'touch test.md' (create a Markdown file named 'test.md') 
11. Enter 'open test.md' (open the 'test.md' file) 
12. In the file, write a few words using the Markdown syntax: http://daringfireball.net/projects/markdown/syntax
13. Save your file using 'control+S' or 'command+S'
14. In the command line, enter 'git remote add origin https://github.com/handle/mla16.git' (replace 'handle' with your GitHub handle)
15. Enter 'git remote -v' (verify the remote repo) 
16. Enter 'git add --all' (add or “stage” all changes to your local repo, 'mla16') 
17. Enter 'git commit -m “message”' (record and describe the changes to your repo)
18. Enter 'git push origin master' (“push” or send changes to your remote repo)
19. Repeat. 
20. Visit https://github.com/curateteaching/digitalpedagogy to see an example of how Git + GitHub are used for writing, editing, publishing, and archiving scholarly projects (in this case, a co-edited collection, titled <em>Digital Pedagogy in the Humanities</em>, published by the MLA).

How, then, might we think of Git + GitHub in terms of composing, versioning, circulating, and archiving a dissertation? What’s the appeal? What are some concerns and limitations? How might Git + GitHub be overrated? 

One thing I’ll add here: both Git <em>et al.</em> are often embedded in minimalist (or “brogrammer”) assumptions that the command line and programming are “real” ways to do digital work (e.g., they bypass graphical user interfaces, are less mediated than word processors, or are more conducive to some mastery of fetishized source code). I encourage extreme skepticism of these positions. For my own projects, I experiment with a few options in order to determine what's best for me, the project, my collaborators/partners (where applicable), and the situation at hand. To be clear, Git <em>et al.</em> are certainly not the only way (or the “real” way) to compose digital scholarship. After all, there is no only or real way. 
