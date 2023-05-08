
This repository uses ansible collections 'user module' along with concepts like group_vars and loop to create mutiple users on a Control Node. 


Below is the directory structure of group_vars where it contains a sub-folder create having another sub-folder passwords where all users passwords will be stored .

NOTE: the individual passwords files name should be exactly the username that needs to be created.

group_vars/
└── create/
    ├── passwords/
    │   ├── user1
    │   ├── user2
    │   └── user3
    └── vars.yml
