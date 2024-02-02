# FBPitDemo
 CARVR's Spring 2023 'Bottomless Pit' Demo, inspired by Dr. Brooks' UNC-Chapel Hill 'Bottomless Pit' Computer Science Department Demo.
 - _Updated in Spring 2024 for compatibility with the Quest 3 + git LFS & MIT License_
 - _Presented at the 'Remembering Dr. Brooks' UNC Computer Science Department Event_

## Project Setup
1. **Clone the GitHub Repo**
 - with **CLI**:
  a. Open the terminal → navigate to the root directory of your project with: `cd </path/to/repository>`
  b. Run `git clone <GitHub_repository_URL>`
  c. In the project (repository)'s root directory, run `git lfs install`
   - _If there's specific large file types tracked, they should be automatically handled by the `.gitattributes` file_
 - with **GitHub Desktop**:
  a. Open GitHub Desktop → navigate to **File** → **Clone Repository**
  b. Choose the repository from the list *or* specify the URL
  c. Choose the local path where you want the repository to be cloned
  d. Qhen prompted with “_This repository uses Git LFS. to contribute to it, Git LFS must first be initialized. Would you like to do so now?_” → select **Initialize Git LFS**

2. **Open the Project via Unity Hub**
   1. Open Unity Hub → **Add** → select the cloned repository (root directory) → **Add Project**
      1. _It’s recommended that all collaborators use the **same version of Unity**!_ See below for the version that we used.

### Hardware
- Wooden plank boards [add dimensions and count later]
- Styrofoam walls [add dimensions and count later]
- Curtain
- Developer-mode-enabled Meta Quest 3

### Software Dependencies
- Unity Editor (version 2022.3.18f1 LTS)

## Build and Run
1. Open up the project in the Unity Editor
2. Navigate to **File** -> **Build Settings** -> **Android** -> **Switch Platform**
 a. _You may also have to change a few things in project settings; here's some [Meta Quest resources](https://developer.oculus.com/documentation/unity/unity-gs-overview/)
3. Connect your Meta Quest 3 <-> to your <-> machine via USB-C or ADB
4. Navigate to **File** -> **Build Settings** -> **Android** -> **Build and Run**
 a. _Wait for everything to build, then you are free to disconnect from your Meta Quest 3 from your machine!_
5. To run the app locally on  your Meta Quest 3 _after running and subsequently quitting it for the first time_, do the following:
 a. On your Meta Quest 3, navigate to the **App Library** -> **Unknown Sources**
 b. Select the **.apk** file with the correct name _(this is the file format for local android-HMD apps)_ to run the app


## Thank you!
- Special thanks to [Dr. Mary Whitton](https://cs.unc.edu/person/mary-c-whitton/), [Dr. Henry Fuchs](https://cs.unc.edu/person/henry-fuchs/), and [Jim Mahaney](https://cs.unc.edu/person/jim-mahaney/) for helping us make this demo possible in memory of Dr. Frederick (Fred) P. Brooks Jr. – the founder of UNC-Chapel Hill's Computer Science Department and friend to many.
- Thank you to all our teammates (Ashley, Jonathan, and Ethan) for creating this!
- And of course, thank you to our friends who dared to test out this immersive, exhilarating experience :)

## To-do
- Add an 'enter' UI where users can pick either of the following options:
 - Physical interfaces (wooden planks + walls) -> platforms cause height difference as users move throughout the scene -> map virtual space to room detection in Quest 3
 - Entirely virtual (NO wooden planks + walls) -> floors are level (assuming users are experiencing this in an empty room with a flat ground)
