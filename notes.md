We went through this instruction (the final one)...

[Developer B]

Independently from Developer A, Developer B created and added index.html to the local repository. They are now ready to close the issue (e.g., #9) from the command line interface using a git commit command. After the commit, Developer B pushes the changes made on the local repository to the GitHub remote repository.

    # one developer
    git add index.html         # stage the file
    git commit -m 'Close #9'   # commit file, close issue
    git push                   # push the changes to GitHub

In this case, we closed the card through the commit message. Open the Projects tab and check the appropriate issue had been moved to the “Done” column. There should be an icon next to it indicating that the issue is closed.


Open the Code tab and see if index.html file is in the list. (Yes? Why?)

... but we couldn't see index.html in the lab-2-2/lab code list. However, we were able to see index.html in gbreck/lab because Grace was Developer B.
