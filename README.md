# git-github
how to use git &amp; github step-by -step
git - version control system (usedpby terminals) ---> used by 2 ways 1.command line 2.by code editor by instralling extensions
github - also use this for repo...

commit - any changes done by user (add,delete,alter) user have to commit the changes everytime.
         green colour line - after chnage.
         red colour line - before change.

instrall git from google.
after instralling git use gitblash or terminal to check version by using command that insures that git is downloaded properly - {git --version} 

# COMMANDS:- -------------------------------------------------------------------------------------------------

# git --version - to check version
# pwd - to check path
# git - for all commands

# FOR USER NAME :- 
                   [ git config --global user.name "username" ]

# FOR EMAIL    :-
                 [ git congig --global user.email "useremail@g.com" ]

# SET OR NOT   :- 
                 [ git config --list ]

# FOR CLONE :- 
if any file which is not in local system but present online in github we use clone command TO MAKE CLONE OF ONLINE                 FILE TO LOCAL SYSTEM
               
                [ git clone (link of file n terminal) ---- website se pc par ]
# TO CHECK LIST OF FILES :-
                [ ls ]
# FOR HIDDEN FILES :-
                [ ls -a ]
                 
# TO DISPLAY STATUS OF CODE :- 
                [ git status ]
                 
1. git aleays tracks history matlab ("file me kya  kb alter hua yhe sab dektha hai git")
2. untracked files :- files which is not a part of git or not uploaded on git via comit ( git in files ko track nahi kr pyega )

# COMMIT NEW FILES IN GIT :- 2 step process

1. ADD :- new or modified files in working directory -> {modified to staged status}

             [ git add (file name) ]
             [ git add .]           
all files add 

2. COMMIT :- it is the record of change

                  [ git commit -m "some msg" ]

git status show krega your branch is ahead of by 1 commit - matlab ("mai apne local system pe github se 1 commit aaghe hu")

3. PUSH :- upload local commits/files to gitnub/ online

                    [ git push origin main ]


