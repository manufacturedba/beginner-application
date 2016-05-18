# beginner-application

> Instructional application for those beginning with code

## Introduction

This application is a guide to creating modern web applications and general 
coding.  This application has been built with teaching in mind, so do not 
expect it to be reflective of what you might find at a company.  Also keep in 
mind there are no single truths to creating web apps.

## Getting Started

### Source Control

Before you can begin any work, you must have `git` installed for your OS.  It 
will be important for grabbing the code included with this repository and for 
making your own changes.

[Git Downloads](https://git-scm.com/downloads)

You may have a GUI client installed along with `git`.  We will not be using it 
during this lesson.

Open `terminal` on your machine and confirm you have `git` installed by running 
`git --version`.  You should have the same version you downloaded from the Git 
website.

Now you will need to `clone` or "copy" this repository.  
Run `git clone https://github.com/manufacturedba/beginner-application`.  If 
it's successful you will now have a folder called `beginner-application`.  In 
your terminal type `cd beginner-application`.  This will move you (change 
directory) into the folder.  You are now ready to make changes.

With your chosen text editor, open the new folder `git` created for this 
repository.

You will see the basic layout of this application.

* `index.html` - The main file that binds the presentation of your app, 
stylesheets, and the underlying code.

* `.gitignore` - Files to be ignored by the `git` system.  These are usually 
files/folders special to your machine and don't need to be viewed/edited by 
others.

* `LICENSE` - Permissions granted to you as a user of this application.  The 
one included is one of the most permissive licenses available while still 
protecting the author.

* `README.md` - This file!  The language used to create this file is known as 
markdown.  Github translates it into HTML to make it more readable.

* `package.json` - Metadata associated with this application

To continue run `git checkout step-1`

### Troubleshooting

#### OS X

**Can't be opened because it is from an unidentified developer**

1. Open *system preferences*
2. Click lock at bottom-left corner of menu
3. Click on *general* tab
4. Under *Allow apps downloaded from* select *Anywhere*

Try to install the downloaded *.pkg* file again