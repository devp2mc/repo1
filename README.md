

# Project Title: Simple Shell with Command History Feature

## Group Members:
- **Partik Dev** 
- **Gurmandeep Johal**

## Student ID:
- **devp2:** 400478418
- **johalg11:** 400467941

## Documentation of AI Usage:
The AI helped in providing an efficient way to remove newline characters from user input using `strcspn()` and splitting the command into arguments using `strtok()` and `token()`. However, we implemented the code ourselves. We also used AI to help understand how background execution could work in our shell. Knowing that adding `&` would run the command in the background allowed us to create a conditional statement to check for and remove the `&` character.

## Contributions:

Both group members collaborated equally on the project during lab sessions. However, each group did paticular tasks for the assignment.

Partik Dev: Focused on constructing the main shell structure. This includes command parsing and handling background execution with the `&` operator. Ensured that the shell would not run into erros and provided the appropriate response. Conducted testing in the Linux and ensured that the functionality of each command input ran smoothly.

Gurmandeep Johal: Focused on implementing and refining the history command and the `!!` command for the shell. Gurmandeep ensured that the circular buffer logic for the history of the shell worked as expected. Gurmandeep also contributed to code structure and and performance of the overall code ensuring no faulties.

Both group members worked together on testing, debugging, and finalizing the code for submission.
