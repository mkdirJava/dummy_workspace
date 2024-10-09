
Golang Workspaces

This git repo acts a reference for working in Workspaces

They are used to put together development dependencies so a local isolated
system can be developed upon

in the go.work file, it has

  use 'dir'

To use this do a git clone of 

* (dummy_web)[https://github.com/mkdirJava/dummy_web]
* (dummy_domain)[https://github.com/mkdirJava/dummy_domain]

in the dummy_workspace directory

* the go.work should refer to these modules.

Then you can 

* Alter the local dummy_domain 
* run go test ./dummy_web 
    The dummy web requires the dummy domain. 

This allows for the dependencies to be normalised and put together. 
When the workspace is setup, you can use go commands and then specify the project/ go code to run




---

likewise for each of the module you can add in 

  replace package => 'dir'

For more information to use replace see the (ReadMe.md)[https://github.com/mkdirJava/dummy_web]

