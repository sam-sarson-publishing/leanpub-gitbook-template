# Welcome!

There are two sets of files contained within this repository to support both GitBook and LeanPub.

Traditionally, this is the place where you should put your book summary. Instead, I'm going to tell you how to set up syncing to both places. 

## GitBook

1. Get an account at [GitBook](http://www.gitbook.com) and link your GitHub account to your GitBook account.
2. Establish this cloned (or forked) repository and push to GitHub under the name that you want. 
3. Create a new GitBook book, and select "GitHub" from the options at the top.
4. Select your existing repository from the dropdown menu, add a description, and create your book.
5. To add new files, you need to update SUMMARY.md. Refer to [GitBook documentation](https://help.gitbook.com/format/chapters.html) for more details on SUMMARY.md creation and updating.
6. To add a cover, you'll replace the provided ```cover.jpg``` in the root directory.

## LeanPub

1. Get an account at [LeanPub](http://www.leanpub.com) and create a new book.
2. Select the GitHub option and add your username/repository name. 
3. On GitHub, add "leanpub" as a collaborator under the repository settings.
5. To add new files, you need to edit "manuscript/Book.txt".
6. To add a cover, you'll replace "images/title_page.jpg" with your file.

## Important notes

  * You need to write files with the .md extension for them to work for both platforms. 
  * Be sure to update both TOC files (SUMMARY.md and manuscript/Book.txt) to make sure that both reflect new changes
  * There are additional steps to take with Leanpub and GitBook, e.g., setting front matter and selling pages. 
  * You can add "Leanpub" as a service to your repository to have it automatically generate a preview.