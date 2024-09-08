+++
title = "2. Process Notion to Github Repo"
weight = 2
+++


Open [Notion to MD](https://notion-to-md.bamidev.com/), fill in the information and process to this step, click “Parse into Hugo Relearn”


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-645687-image.png)


It will show table “Chapter Structure”, we can preview and check if the git repository structure here with parse match with the heading inside our Notion’s page.


The repository structure will follow 2 simple rules:

1. Header H1 will always be a new directory.
2. Bigger number header will always be inside the nearest smaller header. Ex: H2 inside H1

Try not think too much about this structure yet, just follow the trial and error principle, we will be more than ok.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-872721-image.png)


Fill in the Sync to Github information, start “Sync to GitHub”


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-259991-image.png)


(Troubleshooter) This error may occurred if you use a totally new repository with any commit.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-400616-image.png)


Solution is to init the git repository, just use the simple git instruction is enough


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-360489-image.png)


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-457809-image.png)


If everything is good, the process will start and scroll down from step to step, when it’s done, you will see this message.


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-287596-image.png)


Double check the GitHub repository, you can see the `content` directory (holding contents), and `static` directory (holding images) is created ⇒ success


![image.png](/images/003-iii-level-2-notion-to-github-repo/14-472838-image.png)


