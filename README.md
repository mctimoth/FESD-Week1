FESD Week1

# Topic 1 notes 
* Categorizing knowledge
    1. Programming proper
    2. Tooling around programming, industry, profession
        Command line 
        Git, Github
        Associated tech and languages -- HTML, CSS, etc.
* What is JavaScript? What is programming?
    * Resources 
        * MDN JavaScript Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
        * MDN What is JavaScript?: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript
            * Interpreted v. compiled
            * Server side v. client-side
            * Dynamic v. static
* Command Line Interface
    * Getting help
    * Creating/moving/copying/deleting
    * Correspondence with UI; showing hidden files/folders, extensions
* Source control with Git
    * From the book: https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F
    * From the video
        * Pull down changes so your workspace is up to date
        * Make changes
        * Stage your changes
        * Take a snapshot of those changes (note can combine prev with this with `git commit -am`)
        * Push changes to the remote branch
        * Merge that branch into the master branch
    * Ignoring and selecting files...
    * Examining git remotes 
        * Git remote -v
    * Authentication styles
* Variables and data types
    * Type inference, dynamic typing (i.e., you can have a variable taking a string, then assign a number to it, no problem)
    * Types define the kind of data & implications like memory requirements, and also the operations you can perform
* Operations
    * Open in browser extension


Useful resources mentioned in class:
* MDN JavaScript Guide: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
* MDN What is JavsScript?: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript
* What is Git?: https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F


Command line notes 
* Two command line options on Windows: cmd (traditional commnad prompt), and PowerShell. For our purposes, you can use either.
* Getting help -- when all else fails, try to learn more about a command by tacking on Windows-style /? or Unix-style --help to your commands. Command-line programs usually have some documentation online or in installation notes explaining how to list help information.

general anatomy of command line execution: COMMAND OPTIONAL_FLAGS OPTIONAL_ARGUMENTS

Example
                dir /a    (`dir` is command, `/a` is optional flag)
                copy file1.txt .\somedirectory\   (`copy` is command, `file1.txt` and `.\somedirectory` are arguments)

You can get help for a git command by typing `git help [command]` or `git [command] --help`. For Example, the following are equivalent:
    git help branch
    git branch --help

To bring up Chrome dev tools with the console tab open right away, the hotkey is `Ctrl+Shift+J`