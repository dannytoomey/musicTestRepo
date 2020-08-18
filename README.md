# musicTestRepo
test for using github for music 

HOW TO USE GITHUB

-- open terminal
  |-- this probably looks intimidating (i was scared of it at first) but it uses a series of commands called bash commands. 
      they're repetitive and easy to get the hang of once you use it a couple times
-- use the 'cd' command to navigate to a folder
  |-- 'cd' means 'change directory'. folders in comptuers are known as directories, so this really just means 'change folders'
  |-- so if you have filepath that goes Documents -> Music -> Test the command to get there would be 'cd Documents/Music/Test/'
  |-- create an empty folder and navigate to it using the cd command

-- clone this repository
  |-- once you're the empty folder you want to use, type 'git clone https://github.com/dannytoomey/musicTestRepo.git' (the URL for this repository)
  |-- you'll a folder get copied into your empty folder. type 'cd musicTestRepo/' to navigate into it
  |-- protip: if you start typing 'music' and press tab, the computer will autocomplete the rest
  
-- open the file
  |-- open finder and open the folder for this repository ('musicTestRepo'). you should see a garageband file. open it
  |-- add/change whatever you want!
  |-- protip: for large projects, save a copy of the file outside of the folder on your computer. if anything happens to the file, you'll have a backup.
  
-- push your changes
  |-- 'push' is git command that means you're going to put the file back in the repository. 
  |-- save your file and, in terminal, type these commands in order:
      -- git add .
      -- git commit -m '(whatever you want to type. this is a message that will show up with your changes.')'
      -- git push
  |-- now your changes to the file are available for me to see!
  
-- pulling changes
  |-- this is how you keep your files updated. so if i want to see the changes you made, i do this:
      -- navigate to the folder i have this repository in from terminal using the cd command
      -- type 'git pull'
  |-- open the garageband file inside the folder from finder

that's the idea! now you and i can both be working on the same recording file on different computers at the same time and be totally in *NSYNC
