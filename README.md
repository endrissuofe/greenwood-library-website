# Greenwood Community Library Website
## Overview
This project enhances the Greenwood Community Library website by adding a "Book Reviews" section and updating the "Events" page using Git for version control.

## Contributors
Morgan
Jamie

## Steps Taken

### 1. Repository Setup
- Created a repository named greenwood-library-website on GitHub with a README.md file.  
  ![Repository Creation](Screenshots/Clone-website.png)

- Cloned the repository to my local machine:  
  ```bash
  git clone https://github.com/endrissuofe/greenwood-library-website.git
  cd greenwood-library-website
 ![Repository Clone](Screenshots/Clone-website.png)

 ### 2. Initial Website Files
- Created home.html, about_us.html, events.html, and contact_us.html with basic content in the main branch.  
  ![Website Files](Screenshots/website-files.png)

- Staged, committed, and pushed the files to main:  
  ```bash
  git add .
  git commit -m "Add initial website files: home, about_us, events, contact_us"
  git push origin main
![Website Files](Screenshots/Commit-Push.png)

 ### 3. Adding Book Reviews Section
- Created a new branch add-book-reviews:  
  ```bash
  git checkout -b add-book-reviews
 ![create branch](Screenshots/Create-Jamie_branch.png)

- Added book-review with content
![Added book_review with content](Screenshots/Book-reviews.png)

- Staged, committed, and pushed the changes:
  ```bash
  git add book_reviews.html
  git commit -m "Add book reviews section"
  git push origin add-book-reviews
![commit](Screenshots/commit-push-Morgan.png)
 
 - Created a pull request for add-book-reviews on GitHub
 ![pull request](Screenshots/morgan-pr2.png)
 - Merged the pull request into main
 ![Merged](Screenshots/morgan-merge.png)

4. Updating Events Page

- Created a new branch update-events:
  ```bash
  git checkout -b update-events
 ![Morgan Branch](Screenshots/Create-Jamie_branch.png)
- Updated events.html with upcoming events.Updated Events File
  ![Update_event](Screenshots/update-events-file.png)
- Pulled the latest changes from main to avoid conflicts
  ```bash
  git pull origin main
 ![git pull origin](Screenshots/pull-main-changes.png)
- Staged, committed, and pushed the changes:
  ```bash
  git add events.html
  git commit -m "Update events page with upcoming events"
  git push origin update-events
 ![Commit push](Screenshots/Commit-Push.png)
- Created a pull request for update-events on GitHub.
 ![compare and pull ](Screenshots/jamie-pr1.png)
 Merged the pull request into main
 ![merged](Screenshots/merge-jamie.png)