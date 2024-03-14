# Personal Portfolio Website

## Tech stack

- JaveScript
- HTML
- CSS

## Description

The website will including some image, skill, projects, study/work experience.
Also will add contact info and contact form at the footer, then these contact form data will be recevied from the google sheets.
This website is design friendly for all screen devices.

## Steps to build the website

(Continuously updated/changes)

1. Create a new files locally then add and commit the files to Git repository
   - Create a new file locally.
   - Initialize a local Git repository (if not already initialized).
   - Add and commit the file to the local Git repository.
   - Link local repository to a remote GitHub repository if not already linked.
   - Push the committed changes from local repository to the remote GitHub repository.
2. Make Header section of websiter
   - add background photos
   - add/modify header section
3. About Me section
   - photo/description
   - professional experience
   - personal experience
     - details:
       - Implemented dynamic tab functionality, enabling the display of corresponding description/content blocks upon tab click events.
       - This enhancement improves user experience, allowing easy navigation between different sections of the project.
       - Updated HTML structure to accommodate the new functionality and ensured consistency with JavaScript and CSS implementations..
       - 添加了动态选项卡功能，现在点击选项卡时会触发事件显示相应的描述/内容块。
       - 这一功能提升了用户体验，使用户可以轻松地在不同的项目部分之间进行导航。
       - 更新了 HTML 结构以适应新功能并确保与 JavaScript 和 CSS 实现的一致性。

## Related information

1. Can't see the contribution on github after push the commit
   - The reason is the user email in the git config of the local project is different from the email on GitHub. Therefore change the local one to be the same as the one on GitHub
   - run
     ```
     $git config -- global user.emial
     ```
   - if there is no local emial set up, show nothing. Else, will display the email. Change/set the email address same as github account
   - run
     ```
     $git config --global user.email "your_email@example.com"
     ```
   - done
     **the noticeable difference lies on the commit page: if the commit is pushed using the github associated email, your username will be clickable. Otherwish, it won't work.**

## Author

Miranda Zhang

- mirandazhang2024@gmail.com
