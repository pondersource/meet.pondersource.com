### On the start of each working day
1. Go the sitdown channel on Slack and write about what you did on the previous working day, what you are going to do today and anything that is blocking you

### When starting a new project
1. Consult a Github title for the project with the team
2. Create a new repository on Github
3. Write the bare minimum code that is required to start the development and push it to git
4. Prepare the development setup/environment on the dev-stock repository
5. Create a README file in the project's repository that shortly explains what the project is and has a step by step instruction about how to start development on this project using the dev-sotck setup

### Before starting to work on a new project
1. Refer to the README file in the project's repository and only use the instructions there to setup your development environment
2. In case the instructions are broken:
    1. Create a new issue about it before doing anything else
    2. Inform the team on the respective channel on Slack and link to the issue
    3. If you can, try to resolve the issue

### When starting to work (resolving an issue)
1. Check if there is already an issue existing for the task you want to carry
2. If there is none, create a new issue that describes your task
3. If you are going to work on a new issue that has not been created by you:
    1. Try to replicate the issue
    2. Comment your observation and state if you are going to work on it. Assign it to yourself in case you are
4. Create a new branch with a relevant name specifically for your work on this issue
5. As you are coding, keep leaving comments about your progresses or failures on the issue thread
6. In case you leave a TODO in your code, create an issue for it and put a link to that issue on your TODO line
7. In case you encounter a problem that is not caused by your current work or related to it:
    1. Check if there is already an issue created about it. If there is, leave a comment that links to it and also leave a comment there that links to your previous comment
    2. If it is new, create a new issue about it
    3. Either way, mention what just happened in the respective Slack channel for that project
8. In case you push anything, make sure to mention your branch's name in the comments
9. If you successfully resolved an issue:
    1. If your changes to the code, changes anything about the development setup instructions, make sure to change the README properly as well
    2. If your changes to the code, requires changes to the setup code on dev-stock, make sure to mention them in the comments
    3. Push everything to your branch and create a new pull request. Mention the issue on the pull request and mention the pull request in the comments
    4. Mention the pull request in the project's respective channel on Slack
    5. If any changes to the dev-stock were required, create a new issue there and try to resolve it if you can. Either way mention the issue or the pull request for it in the comments of both your main work's issue and pull request

### When creating a new issue
1. Make sure you choose a good title
2. Try to be as clear as you can in the description
3. If it is a bug report:
    1. Find the quickeset and most straight forward way to reproduce the bug
    2. Write down the steps to reproduce it from the scratch starting with following the project setup instructions
    3. Make sure to mention the version of code to use i.e. the branch and the link to the commit in both the project and the dev-stock if relevant

### When attending to a pull request
1. Make sure you have enough understanding of the project and the issue at hand
2. Carefully read the code changes and make sure you don't see anything wrong with it including residual commented code or logs
3. Point out to any errors or mistakes you discover in your review
4. Test it yourself and make sure the pull request actually resolves the issue
5. Comment the outcome of your test on the pull request
6. In case you have any doubts about the correctness of the pull request, make sure to leave comment and explain the reason of your doubts
7. In case you are confident that some changes are required, mention them and request changes
8. In case you are confident that the pull request correctly resolves the issue, approve it
9. Alert the creator of the pull request that you have finished reviewing it in the respective Slack channel for that project

### When you receive a review to your pull request
1. In case some doubts have been introduced, try to clear the doubts or find someone who can help. If there is no way to achieve confidence about the changes, mention it. Close your eyes and merge it then close the issue and the pull request
2. In case some changes are requested, either dispute them or resolve them and request a review again
3. In case the pull request has been approved, merge it and close both the issue and the pull request
4. Mention what you did in the project's respective Slack channel
