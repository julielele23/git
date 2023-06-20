# The use of Git

Git can be use for :

1.  **Clone a repository**

> - create a new repository on Github or use an existing , copy the URL of the repository
> - go to the diretory where we want our repository to be cloned on Git bash
> - type the command : *git clone* + paste the URL of the repository. You can also use *git clone* + arguments like *--progress* to see the progress of the cloning


2. **Commit changes**

> - make changes in the *README.md* file via an editor like Visual code and save it
> - ckeck the status of the repository
> - type te command *git commit* + < arguments > like *- m + 'messsage'* to add a message describing the changes of your old file
> - type the command *git add name of the file to be committed* 
> - check the new status
> - you can also check the difference between the old and the new versions of the file with the command *git diff*
> - the command *git restore + name of the file* can be used to restor the version of the file before the changes


3. **Push the updated version on Github**

> - check the status one mor time 
> - push the file to Gibhu using the command *git push*


4. **Add a new file in a repository**

> - type the command *git add + name_of_the_file_to_added* 
> - type the command *ls* to check if the file have been added
