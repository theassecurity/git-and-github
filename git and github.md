#### Git and Github

###### Git is used for version control. Suppose you want to make different versions of an application, that is version control

###### Github is a git repository hosting service. It provides a Web based graphical interface

#### How to make a local git repository 
````
cd Documents
mkdir Project 
cd Project 
````
#### How to initialize the git repository
````
git init 
````
#### How to add files in the folder
````
touch project.txt
````
#### What is a Pull Request ?

###### Pull requests are a way of contributing your code changes to an open source project
###### Go to github -> Fork the repo in which you want to contribute
###### Open that repo in your profile , go to the code and copy it
###### Open git bash and write the commands given below 

#### Commands 
###### Set username and password 
````
git config --global user.name “github username”
git config --global user.password  “email address”
````
###### Go into the directory where you want to clone the repo
````
git clone <paste the copied url>
````
###### Do the desired changes and add it 
````
git add .
````
###### Commit the changes 
````
git commit -m "Message"
````
###### Push the changes in the master branch
````
git push -u origin master 
````
###### If you want to make a branch 
````
git checkout -b branch_name
cd branch_name
git push -u origin branch_name
````
###### Make the pull request 
````
Go on github
Click on Pull Request
Click on Create Pull Request 
Write any comment if you want to
Click on Create Pull Request
````
###### Congratulations, You have successfully made the pull request :smile:



