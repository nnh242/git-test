Git Test Instruction:

1. Make test_git.py file in your code editor and enter its content:
SITES = [
    "https://test1.com"
    ""https://test1.com""
    "https://test3.com",
    "https://test4.com",
    "https://test5.com",
    "https://test6.com",
    "https://test7.com"
]
2. Enter your name as one of the elements in the Sites dictionary in the correct Python syntax for an element in a list.
3. Create a GitHub account and create a new Repo on github to host this test code. We will be using github in this test because it is free and similar to git lab. Commands that you are being tested on for github and gitlab are the same.
4. Follow the instructions to create a new repository on the command line to push your new test_git.py file to the new GitHub repo
5. You notice that test2.com is missing, so you want to include that in the Sites. Insert the line "https://test2.com" after test 1 and above test 3. 
6. Commit changes with a meaningful message describing what you have added and push this changes to remote repo.
7. Go to your local project, checkout a new branch called "add-5-names"
8. Open the test-git.py file and insert your name 5 more times in the file. Save and commit these changes. Push your local changes to the remote add-5-names branch.
9. On Github, create a pull request to Merge the branch add-5-names into master branch
10. On your local files, on add-5-names branch open test_git.py and delete all of your names and "https://test2.com"
11. Commit your changes and push to remote branch add-5-names
12. Go to your GitHub repo's master branch and open the test_git.py to edit it, delete everything and replace with: 

SITES = [
    "https://test1.com"
    ""https://test1.com""
    "https://test3.com",
    "https://test4.com",
    "https://test5.com",
    "https://test6.com",
    "https://test7.com",
    SITES = [
    "https://test1.com"
    ""https://test1.com""
    "https://test3.com",
    "https://test4.com",
    "https://test5.com",
    "https://test6.com",
    "https://test7.com",
    "https://test8.com",
    "https://test9.com",
    "https://test10.com"
]

    "https://test8.com",
    "https://test9.com",
    "https://test10.com"
]

13. Commit your changes to master.

14. Now create a pull request: base: master compare: add-5-names. Merge and close this pull request.

If you experience any errors or git conflicts in this exercise, please list the details, error messages and show me how you troubleshoot and resolve the conflict.

15. Delete add-5-names branch ONLY after conflict is resolved and merge is complete.

Deliverable: link to your public GitHub repo
Example: https://github.com/nnh242/test-git 
