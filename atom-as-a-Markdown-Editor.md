## Installing Atom

## Atom Workspace
Project Folders

##### Create a new file
Click File >> New File

##### If you don’t want your lines going all the way across the screen
click View >> Toggle Soft Wrap

##### To view an entire folder:
1. Click File >> Open
2. Navigate to the folder you want to open
3. Instead of clicking a file, click Open
4. Atom then opens the desired folder, listing all files contained in it:
5. Now you can jump between files without clicking File >> Open.

**Notes:** You can also add other folders to a project. I’m not going to talk about that here.

## Setting up for Markdown
### Open Atom’s Package Manager
1. If you’re on Windows, click Packages >> Settings View >> Open.
2. Atom Markdown packages number in the dozens. But I find I only need three:
    * language-markdown
    * markdown-writer
    * markdown-preview
3. They add nifty things like Markdown syntax highlighting
4. And autonumbered lists
5. And let you preview your document without leaving Atom.

### To install:
1. Open the Package Manager
2. Open Settings
3. Click Install (on OS X) or Open (on Windows)
4. Search for the package you want. In this case, type “Markdown” into the search box
5. Choose the packages and click Install
Markdown installs the package. You’re good to go.

## Setting Up a Document

### If You Are Writing a Simple Document
If you’re writing a single document that won’t include other files like images:

 1. Start Atom Create a new file Save the file as FILENAME.md, where
    FILENAME is whatever you name the file.
 2. The .md extension tells Atom
    this is a Markdown file. Atom will apply the right packages and
    syntax highlighting.
### If Your Project Will Contain Multiple Files
If you are writing a multiple-file document—like a multiple-chapter     book—or will be including other files like images, start with a folder: 
1. Create a new folder on your computer. This folder will hold all of your files
2. Start Atom
3. Open the folder in which your document currently lives or will live
4. Create and save a new file as above
## Opening Preview
I use markdown-preview so I can see how my document looks without leaving Atom:
To use it, you need to toggle Preview. There are keyboard shortcuts, but the easiest way is clicking **Packages** >> **Markdown Preview** >> **Toggle Preview**
## Converting Markdown to HTML
For delivery, you probably need to convert Markdown to something else:
1. Toggle markdown-preview so that you can see the document preview
2. Right-click in any blank area of the preview. Otherwise, Atom will copy the word or image instead of the entire document
3. Click Copy As HTML…
4. Paste the result wherever you need it
That’s it. You’ve got HTML.
