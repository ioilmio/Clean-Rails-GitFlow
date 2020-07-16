
 # Clean Rails GitFlow
 
 

 ## On Github 

 ### 1. Create new ```repo name``` initialize it with a README.md file
 ### 2. Create a ```new_remote_branch_name``` from MASTER (usually called development)
 ### 3. Set ```new_remote_branch_name``` as Default in Repo settings

 ## On your terminal

 ### 1. ```cd``` into your desired folder
 ### 2. ```git clone <ssh url>```
 ### 3. Create a new rails app running ```rails new <repo name>```
 ### 4. Overwrite (if needed) your README.md file
 ### 5. ```cd``` into the new cloned folder
 ### 6. Create a ```new_local_branch_name``` using ```git checkout -b new_local_branch_name```
 ### 7. ``` git remote add origin <ssh-url>```
 ### 8. Add your linters config files as specified at ![Microverse linters config for Ruby on Rails](https://github.com/microverseinc/linters-config/tree/master/ror)
 ### 9. ```git add .```
 ### 10. ```git commit -m "your commit message"```
 ### 11. ``` git push --set-upstream origin feature```

