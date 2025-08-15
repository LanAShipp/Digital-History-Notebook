Digital History Notebook: Computer Science Pioneers
Welcome to your first project for the "History of Technology" class. Your assignment is to create a digital notebook to document key figures and events in the history of computer science. This notebook will be version-controlled, allowing you to track your work and manage your revisions.

Your final submission will be a public GitHub repository with a complete digital notebook that follows all of the steps below.
Assignment 1: Setting Up Your Notebook
Your first task is to set up your digital notebook's central repository.

Instructions: Create a new public repository on GitHub. Name it exactly: Digital-History-Notebook.
Add a README.md file when you create the repository.
After creating the repository, clone it to your local computer. Open the README.md file in a text editor and copy and paste this entire assignment briefing into it.
Once the content is in the file, you will need to push it back to GitHub.
Report Status (These questions need to be answered for part of your grade): Done

1.1: What command did you use to bring the repository to your local machine?
Answer: **git clone**

1.2: What was your first commit message to push this file to GitHub?
Answer: **added assignment instructions**

Assignment 2: The Founding Visionaries
Now, let's begin documenting the pioneers of our field. You will create files for two key figures.

Instructions: On your local machine, create a new file named ada-lovelace.md.
In this file, research and write a short paragraph about her contributions to early computing. (Cite those sources!)
Create a second new file named alan-turing.md.
In this file, research and write a short paragraph about his contributions to modern computer science. (Cite those sources!)
In this README.md file, add two hyperlinks below to your new files. The links must be named "Ada Lovelace" and "Alan Turing" and must lead to the corresponding files you just created. (Hint you will need to research how to put in a link in markdown)
Use git add . to stage both new files.
Use git commit -m "Added pioneers Ada and Alan" to save these changes to your local notebook.
Finally, use git push to publish your work to GitHub.

Report Status: done
2.1: What two file names did you create?
Answer: **ada-lovelace.md**

2.2: What was your commit message?
Answer: **added pioneers ada and alan**

Assignment 3: A Timeline of the Internet
To celebrate the interconnected world of computing, you will create a timeline of key events in the internet's history. You will do this by editing your README.md file directly on GitHub.

Instructions: Go to your Digital-History-Notebook repository on GitHub.
Edit the README.md file directly.
At the bottom of the README.md file, add a new section titled Timeline: The Rise of the Internet.
In this new section, add a brief, bulleted timeline (7 points) of major milestones, such as the creation of ARPANET, the invention of TCP/IP, or the launch of the World Wide Web. Be sure to include pictures as well (might need to figure out how to add a picture in markdown).
Commit this change directly on GitHub with the message: "Added internet timeline".
Return to your local machine's terminal.
Use git pull to retrieve the timeline you created from your remote repository.

Report Status: done
3.1: What command did you use to retrieve the new information from GitHub?
Answer: **git pull**

Assignment 4: The Modern Era
Now, let's add two more influential figures who shaped the modern era of computing.

Instructions: On your local machine, create a new file named bill-gates.md. Research and write a short paragraph about his role in the personal computer revolution.
Create a second new file named steve-jobs.md. Research and write a short paragraph about his role in user interface and consumer technology.
In this README.md file, add two new hyperlinks below to the files you just created. The links must be named "Bill Gates" and "Steve Jobs" and must lead to the corresponding files.

https://github.com/LanAShipp/Digital-History-Notebook/blob/eae827bb091ce6f9a40197f7dce60ece6eb4ff71/Bill-Gates.md
https://github.com/LanAShipp/Digital-History-Notebook/blob/513238655955859cb45c0566f3cd5073fa8b7192/Steve-Jobs.md

Use git add . to stage the new files and the updated README.md.
Use git commit -m "Added modern innovators" to save your work.
Use git push to publish your changes.

Report Status: done
4.1: What command did you use to save your changes to your local notebook?
Answer: **git pull**

4.2: What command did you use to publish your changes to the remote repository?
Answer: **git push**

Assignment 5: Peer Review
Your classmates are now reviewing your work. A peer has left a suggestion for one of your files.

Instructions: Simulate a peer's action: go to your Digital-History-Notebook repository on GitHub.
Find and edit the steve-jobs.md file directly.
Add the following line to the end of the file: "Peer review: Could you add more details about the first Macintosh computer?"
Commit this change directly on GitHub with the message: "Peer review on Steve Jobs file".
Return to your local machine's terminal.
Use git fetch to check for updates, then use git status to see what's different.
Finally, use git pull to get your peer's feedback.

Report Status: done
5.1: What did git status tell you after you ran git fetch?
Answer: **Modified: README.md**

5.2: What command did you use to merge your peer's changes into your local notebook?
Answer: **git pull**

Assignment 6: The Web's Inventor
With the internet's timeline now in your notebook, let's document one of its key figures.

Instructions: On your local machine, create a new file named tim-berners-lee.md.
In this file, research and write a short paragraph about his role in creating the World Wide Web.
In this README.md file, add a hyperlink to this new file. The link should be named "Tim Berners-Lee".
https://github.com/LanAShipp/Digital-History-Notebook/blob/19b44060091d5e74e13e9662d6d0600e52a69921/Tim-Berners-Lee.md
Use git add . to stage the new file and the updated README.md.
Use git commit -m "Added Tim Berners-Lee" to save these changes.
Use git push to publish this final piece of research.
Report Status: done
6.1: What was your commit message for this assignment?
Answer: **Added Tim Berners-lee**

6.2: What command did you use to publish your work?
Answer: git push

Assignment 7: Final Edits
As a final step, you realize your notebook could use a concluding thought. You will add this directly on GitHub.

Instructions: Go to your Digital-History-Notebook repository on GitHub.
Edit the README.md file directly.
At the very end of the file, add a new section titled Final Thoughts.
In this new section, write one or two sentences reflecting on the project.
Commit this change directly on GitHub with the message: "Final thoughts on project".
Return to your local machine's terminal and use git pull to get your concluding thoughts.

Report Status: done
7.1: What command did you use to retrieve your final thoughts from GitHub?
Answer: git pull

High-Level Challenge: The Editing Mistake
You were working on a file for an extra credit assignment but made a mistake. You committed the error to your local history, but you realize your mistake before pushing. You need to completely erase the commit so there is no record of the error.

Instructions:
On your local machine, create a new file named extra-credit.md.
Add a line of text that you know is factually incorrect.
Use git add . and git commit -m "Mistake commit" to save this mistake locally.
Do not push this commit.

Now, find a way to undo the last commit and completely remove it from your local history.
Once undone, verify that the commit is gone by using git log.

Report Status:
Extra Credit: What command(s) did you use to undo the commit, and why did you choose that particular method?
Answer:

Submission Instructions
When you have completed all assignments and answered all of the "Report Status" questions in your README.md file, you are ready to submit. Please submit the following to Google 

Classroom:
A link to your public Digital-History-Notebook repository.
A screenshot of your repository's commit history on GitHub. To find this, navigate to your repository, click the "commits" link near the top right, and take a screenshot of the page.
Be sure to answer the questions above as well.


### Final Thoughts
I thought this project was extremely time-consuming, though at the very least, it was simple to work on. I quite enjoy working on the project when there is time, trying to get the commits right was impossible for me because I always save my work on GitHub before I go home.


### Timeline of the Internet

 - 1. 1848 Ada lovelace creates a basic concept of programming for what future early computers use
 - 2. 1890 Herman Hollerith designs a punch-card system to help calculate the 1890 U.S. Census. which saves the government a lot of money which makes funding for computer science even larger.
 - 3. 1936 Alan Turing creates the turing machine and makes the theory that anything that can be computable can be computable by computers![ueuBpt3Xfk96wy2xVEwXoQ-970-80](https://github.com/user-attachments/assets/073495da-6566-4b56-b4ca-539633185ee1)
 - 4. 1941 Atanasoff and his graduate student, Clifford Berry, design the first digital electronic computer in the U.S., called the Atanasoff-Berry Computer (ABC). This marks the first time a computer is able to store information on its main memory,
      and is capable of performing one operation every 15 seconds, according to the book "Birthing the Computer" ![2Hjzmh4vVRAHaGCEoBaAE-970-80](https://github.com/user-attachments/assets/6cc4"365a-4647-4c73-8cdb-37b7c541f23c)
 - 5. 1945 the creation of the first general-purpose all electric decimal, digital computer.
 - 6. 1968 the creation of the GUI 
 - 7. 1981: "Acorn," IBM's first personal computer, is released onto the market at a price point of $1,565, according to IBM. ![z93VFz9nKcVyCRYRoKKqUB-970-80](https://github.com/user-attachments/assets/435cdc80-8a0e-4047-8a7d-4ccd3d0a0c31)
