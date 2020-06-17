# How to Contribute to Opensource like a Pro

- First choose a project ( I started with )
- Create a directory on your PC containing all repositories of projects you wish to contribute to

## Case of Github

- Go to the projects page on Github
- Click on "Fork" button at the top right coner
- Go to your forked repository page (not the original one)
- Copy the link on the "Clone or download" button from forked repositories
- `git clone <link_copied_in_previous_step`
- `cd <project_directory_created_after_cloning>`
- Create a branch and work on it - `git checkout -b <new_branch>`
- `git remote add upstream <url_to_original_repository>`
- Make a change (adding or modifying an exsiting file)
- `git add <new_file>` or
- `git commit -m "<commit_message>"`
- `git push -u origin <new_branch>`
- Go to on your forked projects page and click on "*Compare & pull request*" button
- Leave a comment (optional)
- Click on "*Create pull request*" button.

## Case of Gitlab

*To be continued* :)

***

## Credits

- [@kedark3](https://github.com/kedark3) with this [article](https://opensource.com/article/19/7/create-pull-request-github?utm_campaign=intrel)
- [@galenemco](https://twitter.com/galenemco) for this [article](https://opensource.com/article/19/11/first-open-source-contribution-fork-clone)
