
Golang Workspaces

This git repo acts a reference for working in Workspaces

They are used to put together development dependencies so a local isolated
system can be developed upon

in the go.work file, it has

  use 'dir'

This allows for the dependencies to be normalised and put together. 

likewise for each of the module you can add in 

  replace package => 'dir'
