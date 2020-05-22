# speech_to_code
This is an example ROS2 project that converts speech to text and parses it into code.

The purpose of this project is to demonstrate the use of a .rosinstall file. While this repository does not contain any of the necessary code to listen to speech, convert it to text, and then parse it into code, a .rosinstall file enables us to pull this code from existing github repositories.

## Installation for Developers
1. Initialize a git repository and link it to the remote repository

```
mkdir ~/Documents/speech_to_code
cd ~/Documents/speech_to_code
git init
git remote add origin https://github.com/dporfirio/speech_to_code.git
git pull origin master
```

2. Run ```rosws update```

Congratulations, you have now pulled all the necessary ros2 subrepositories.

*NOTE: Do NOT ```git add``` the subrepositories to the parent repository.*

*ANOTHER NOTE: You can seamlessly enter a subrepository that got pulled, make changes to it, and push it to its own repository within the directory of the subrepository.* 


3. run ```colcon build```
