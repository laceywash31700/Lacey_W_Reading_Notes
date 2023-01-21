# Class-02 Reading Notes

## What is a Text Editor? 

> A text editor is a piece of software that you download and install on allows you to write and manage text, especially the text that you write
to build a web site. When looking a text editor its probaly a good idea to make sure it has these three features.

- Syntax Highlights
    - this displays text in diffrent colors or fonts for easy reading. 
- Themes
    - this is used for less strain on the the eyes.
- Extentions
    -for adding new programing languages for your text editor.
- Code Completion
    -this is used to reduce typos and mistakes in your syntax.

## IDE OR Intergrated Development Enviorment

> this is a more advanced program software developers use to complie code, source you code, and debugg your code.

## Linux Commands

> to understand linux commands you should understand some key vocbulary and concepts
>   - **Argument** 
>       - A specificaion for a command.
>   - **Command**
>       - Is an action for a computer.
>   - **Terminal(Command Line)**
>       - A text based interface.
>   - **Paths**
>       - a path is a means of getting to specific file,directory or location in the system.Think of paths as a means to getting to another file 
>   *It's important to note that everything and I mean everything is a file from your keyboard to your monitor as far as linux is concerned now it is also important to understand that linux organizes file in a hierarchical structure at the top of this structure is what we call a ***root directory*** which is denoted by a (/) and the root directory can be split into two categories.*
>       - **Absolute**
>          - specifies a location in relation to the root directory they will always have a (/) or forward slash in the beginning 
>       - **Relative**
>           -specifies a location in relation to where you are in the system they **do not** begin with a (/)
>   *You should also know that **linux is case sensitive** so when naming files **you can have two file of the same name but cased diffrently and linux will veiw those files of the same name as two seperate files**
>  files in linux can be seen as three diffrent types.
>       - file.exe 
>           - an executable file or program 
>       - file.txt
>           - a plain text file 
>       - file.(png)(gif)(jpg)
>           -an image file 
>  
>  **Finally one of the most important thing I can tell you 
about linux is spaces matter** *for example if ypu had a 
file named (Wedding Photos) linux would look at that 
phrase as 
two seperate files because the space is how we determine the 
line the line argument but, all hope is not lost there are 
two ways to remedy this problem.*
>      
>     Quotes  
>      ('')("") will make those files viewed as one file. 
>       Ex."Wedding Photo"
>      
>     Escape Characters 
>       (\)backslash not to be confused with (/)forwardslash 
>           ex. wedding /photos  

*now that was alot of information; but still theres more.lets look at some of the commands you can do.*
- pdw (Print Working Directory)
    - This is used to tell wh.ere the present or working directory is.
- ls (list files)
    -this lets you know what files are inside of the file you are in 
- cd (change directory)
        - when used alone will take you to your home directory 
- /etc
        - stores config files for the system 
- /var/log
        -stores log files for various system programs 
- /bin 
        -location of several commonly used programs 
- /usr/bin
        -another location for programs on the system 

*linux treats files as they are orginally for example you can rename a file.jpg as file.txt later is still a text file but linux still treats it as the former a image now that makes thing tricky to determine what the file is so use this command to find out what the file originally is.*
- file

## Shorthands 

- (~) tilde- this is short hand for the home directory 
- (.) dot- this is short hand for your current file you are in
- (..) dotdot- this is shorthand for the parent file 
you can do any way you like but I hope that helps

## Hidden Files 

linux will sometimes have hidden files or as I like to call them sneaky links they are denoted by the (.) dot before a files name for example (.file.jpg) there are loads of reasons for having hidden files and to be honest I dont fully understand why yet but, if you wanted to see those hidden file because a (ls) command would not let you see them first hand you could use this command 
    
    - (ls -a)

## Things I want to know about.