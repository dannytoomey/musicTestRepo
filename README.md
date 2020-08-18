# musicTestRepo
Test for using github for music 

**How To Use GitHub**

1. Open terminal
   - This probably looks intimidating (I was scared of it at first) but it uses a series of commands called bash commands. They're repetitive and easy to get the hang of once you use them a couple times.
   - Use the 'cd' command to navigate to a folder
   - 'cd' means 'change directory'. Folders in comptuers are known as directories, so this really just means 'change folders'. For example, if you have filepath that goes Documents -> Music -> Test , the command to get there would be 
   ```
   cd Documents/Music/Test/
   ```
   - Create an empty folder and navigate to it using the cd command

2. Clone this repository
   - Once you're in the empty folder you want to use, type 
   ```
   git clone https://github.com/dannytoomey/musicTestRepo.git'
   ```
   (the URL for this repository)
   - You'll see a folder get copied into your empty folder. Type 'cd musicTestRepo/' to navigate into it
   -*Protip: if you start typing 'cd music' and press tab, the computer will autocomplete the rest*
  
3. Open the file
   - Open finder and open the folder for this repository ('musicTestRepo'). You should see a garageband file. Open it
   - Add/change whatever you want!
   -*Protip: for large projects, save a copy of the file outside of the folder on your computer. if anything happens to the file, you'll have a backup.*
  
4. Push your changes
   - 'push' is a git command that means you're going to put the file back in the repository. 
   - Save your file and, in terminal, type these commands in order:
      ```
      git add .
      git commit -m '(whatever you want to type. this is a message that will show up with your changes.')'
      git push
      ```
      Make sure you're in the 'musicTestRepo' folder, otherwise these commands won't work.
   - Now your changes to the file are available for me to see!
  
5. Pulling changes
   - This is how you keep your files updated. So if I want to see the changes you made, I do this:
     - Navigate to the folder i have this repository in from terminal using the cd command
     - Type 'git pull'
   - Open the garageband file inside the folder from finder

That's the idea! Now you and I can both be working on the same recording file on different computers at the same time and be totally in *NSYNC
