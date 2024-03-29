# Personal Portfolio Website

## Tech stack

- JaveScript
- HTML
- CSS

## Description

link: https://yxzhang88.github.io/portfolio/
The website will including some image, skill, projects, study/work experience.
Also will add contact info and contact form at the footer, then these contact form data will be recevied from the google sheets.
This website is designed to be user-friendly across all screen sizes.

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
   - project list
     - details:
       - Implemented dynamic tab functionality, enabling the display of corresponding description/content blocks upon tab click events.
       - This enhancement improves user experience, allowing easy navigation between different sections of the project.
       - Updated HTML structure to accommodate the new functionality and ensured consistency with JavaScript and CSS implementations..
       - 添加了动态选项卡功能，现在点击选项卡时会触发事件显示相应的描述/内容块。
       - 这一功能提升了用户体验，使用户可以轻松地在不同的项目部分之间进行导航。
       - 更新了 HTML 结构以适应新功能并确保与 JavaScript 和 CSS 实现的一致性。
4. My Work section
   - photos/descrption
     - details:
       - The project section showcases projects with images and brief descriptions, revealing details upon hover, accompanied by a color overlay for enhanced visibility.
       - Each project image comes to life with dynamic effects, ensuring an engaging user experience
       - 项目部分展示带有图像和简短描述的项目，鼠标悬停时显示详细信息，并带有颜色叠加以增强可见性。
       - 项目图像具有动态效果，确保引人入胜的用户体验
5. Contact section
   - add icons
   - add contact form
   - add download cv feature
6. footer
   - Copyright
7. Mobile friendly
   - change the background pic size
   - created the side menu：open/close
8. Submit a Form to Google Sheets
   - using google apps script
   - github tutorial: https://github.com/jamiewilson/form-to-google-sheets

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

2. media queries

   - a feature in CSS that allow to apply different styles based on the characteristics of the device or browser being used to view the page

   '''
   @media only screen and (max-width: 600px) { }
   '''

   - the screen width is 600px or less (typical for mobile devices)
   - consider using relative units like _percentages_ and _em_ to ensure scalability across various screen sizes

3. Upload a website on Github page
   - it has be a static website
     - not using a server like python with flask or django
     - no ruby on rails
     - no node.js with express

## Author

Miranda Zhang

- mirandazhang2024@gmail.com
