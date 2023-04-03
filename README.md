# Smart_Mobility_Service-lab-based
Smart_Mobility_Service (lab-based)

Week_3.   
in this week, we learned how to push any files to our github repository through terminal.  
I pushed files to the main branch as well as two other branches master and master1. 

I used these instructions for pushing my files to a remote GitHub repository by terminal.  

sudo apt-get install git-all -y.    
mkdir directory.     
touch file.      
cd project_folder.     
git checkout (-b) local-branch-name (optional).    
git status.     
git init.    
git add .    
git commit -m "VER1" (git commit --amend).    
git remote set-url (or add) origin https://token@github.com/-----.git.    
(git pull or fetch origin main if necessary).    
git push (-u) origin main.    

Actually, after some initial failures to push code to the main branch for the first time, I used git push --force origin main command which worked fine in my case. <br> And later, I could add an additional file to the main branch using git push origin main.

<img width="1280" alt="Screenshot 2023-03-15 at 9 30 14 PM" src="https://user-images.githubusercontent.com/90837231/225314803-f2d10cce-5c02-46da-bbed-8e5ec8a1bbe0.png">
<img width="1280" alt="Screenshot 2023-03-15 at 9 30 21 PM" src="https://user-images.githubusercontent.com/90837231/225314813-e226e8e7-75ea-427a-a4b1-b01d944c1ce6.png">

<br>
<h2> Hw1. it is inside src file </h2>
<br>
<br>


<img width="1280" alt="Screenshot 2023-03-26 at 11 44 16 PM" src="https://user-images.githubusercontent.com/90837231/227786026-4f8b3eb4-f233-4c77-bfbb-743a81b285f4.png">
<img width="1280" alt="Screenshot 2023-03-26 at 11 44 28 PM" src="https://user-images.githubusercontent.com/90837231/227786030-9b5d4289-8c88-4939-9e5b-30845a8cd04c.png">
<img width="1280" alt="Screenshot 2023-03-26 at 11 44 40 PM" src="https://user-images.githubusercontent.com/90837231/227786033-771173ca-6baa-473e-a1ea-d86c7e488726.png">
<img width="1280" alt="Screenshot 2023-03-26 at 11 44 43 PM" src="https://user-images.githubusercontent.com/90837231/227786034-ef69c65e-d4a5-472d-a165-d4f7c8109e2c.png">
<img width="1280" alt="Screenshot 2023-03-26 at 11 44 52 PM" src="https://user-images.githubusercontent.com/90837231/227786036-c2c30da8-aba8-4ae1-883c-f7280fb05fcf.png">
<img width="1280" alt="Screenshot 2023-03-26 at 11 44 55 PM" src="https://user-images.githubusercontent.com/90837231/227786039-7e8cd240-1e4e-4d55-b54c-8087abb8b3cf.png">


<br>
<h2> Hw2. it is inside another branch named master_for_hw2 file </h2>
<br>
<br>

In the homework_2, we were supposed to change the rpm_pub.cpp and speed_calc.cpp files into Python version. I could successfully did this task of converting them into their python version. It is possible to check the source files inside the master branch named master_for_hw2, specifically inside src/hw2/src folders.    

However, I could not build the 2 python version files successfully.  
Steps I've done are:    
* At first I created the package using catkin_create_pkg hw2 rospy, which is not roscpp, and I thought everything would build smoothly because of making it rospy. But it was not all, I browsed online resources on what else to change more to build the files finely and I had to make some modifications inside CMakeLists.txt file, it's possible to check my modifications inside src/hw2/CMakeLists.txt file. In the end I failed to build the files successfully. I searched so many online resources on how to fix the problem, none of them could solve the issue. Now I have no idea of what changes I should make so that I can build the files without problems.   
The output:    

<img width="1280" alt="Screenshot 2023-04-03 at 12 50 45 PM" src="https://user-images.githubusercontent.com/90837231/229411342-c7ed1c0d-769f-4098-9b31-85afb3b2a5f9.png">
