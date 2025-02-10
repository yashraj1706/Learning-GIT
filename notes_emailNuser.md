754

Locally set email-address (separately for each repository)
Open Git Bash.

Change the current working directory to the local repository in which you want to set your Git config email.

Set your email address with the following command:

git config user.email "your_email@abc.example"
Confirm that you have set your email address correctly with the following command.
git config user.email
Globally set email-address (only used when nothing is set locally)
Open Git Bash.

Set your email address with the following command:

git config --global user.email "your_email@abc.example"
Confirm that you have set your email address:
git config --global user.email
Or using environment variables
GIT_COMMITTER_EMAIL=your_email@abc.example
GIT_AUTHOR_EMAIL=your_email@abc.example
PD: Info from GitHub official guide