# torus

![image](https://user-images.githubusercontent.com/63946099/178664839-9d0620e4-a588-4179-9ec5-844b0b4f703c.png)

->Git

-Install git on EC2 instance

yum install git -y

-Make project directory /torus

mkdir /torus

cd mkdir

-initialize git

git init

-Add project source code

git add .

git commit -m "torus"

git status # nothing to commit

-Add git remote repo detials

git add remote origin master https://github.com/<User-Name>/<repo-name>.git
  
git add remote origin master https://github.com/Shrikumar-Udupa/torus.git
  
git push origin master
