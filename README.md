# THM-0x41haz-Write-Up
## Simple Reversing Challenge


![OhSINT Room Image](https://user-images.githubusercontent.com/29344252/172438032-abff2b5e-de9b-4763-83cc-6eaa52d24cf8.png?style=centerme)

 
- Figure 1.1 - OhSINT Room Image

**OhSINT Room Description:** “Are you able to use open source intelligence to solve this challenge?”

This room has a heavy focus on **OSINT** (Open-Source Intelligence), there is only 1 Task in this Room but to complete this room you will need to answer 7 questions.

*“Open-source intelligence is a multi-factor methodology for collecting, analyzing and making decisions about data accessible in publicly available sources to be used in an intelligence context. In the intelligence community, the term “open” refers to overt, publicly available sources. — Wikipedia”*

![OhSINT Task 1](https://user-images.githubusercontent.com/29344252/172439411-dca6094b-ea20-4aa9-8554-3409a409007d.png)

- Figure 1.2 - OhSINT Task 1

To get started with this room we will need to download the Task Files (blue button at the top of Task 1 “Download Task Files”). This will allow us to download an image (WindowsXP.jpg), which can be seen below (Figure 1.3).

![WindowsXP](https://user-images.githubusercontent.com/29344252/172439458-f4c61d9c-60a8-4301-80ef-0613a419e441.jpg)

- Figure 1.3 - WindowsXP.jpg

Now first thing that most people would do once they get an image is to right-click on it and go to the image properties. But as you can see from the figure below (Figure 1.4) it is not very helpful.

![WindowsXP Properties](https://user-images.githubusercontent.com/29344252/172440253-21787f78-1a3a-472b-97d0-e6ee427cc56f.png)

- Figure - 1.4 - WindowsXP Properties

Next up, I decided to try a tool called exiftool, developed by Phil Harvey. You can download the tool from the hyperlinked website, to get the tool running I have re-named it as a .exe on my Desktop and I have the Task Image on my desktop as well (Figure 1.5).

![Task Image](https://user-images.githubusercontent.com/29344252/172440405-e0d5f061-01c9-4518-b615-65dfcaab285a.png)

- Figure 1.5 - Task Image & exiftool.exe

Now to use exiftool I am using the Command Prompt from Windows. I first of all have to get to my Desktop where I have saved exiftool.exe and the Task Image using cd Desktop. After that I can just type exiftool.exe WindowsXP.jpg (hint, if you press tab you can autocomplete so there is no need to type the full name) and let exiftool run (Figure 1.6).

![Using exiftool](https://user-images.githubusercontent.com/29344252/172440489-4b0b2692-eeac-4196-adad-cccffee27c95.png)

- Figure 1.6 - Using exiftool

Now I will run the exiftool to see if I can find anything interesting about the WindowsXP.jpg image.

![exif output](https://user-images.githubusercontent.com/29344252/172440581-269a3e9c-8b8a-4373-8e7e-3e310307f42a.png)

- Figure 1.7 - exiftool output from WindowsXP.jpg

Now this has revealed a few interesting things such as the Image Copyright & GPS Coordinates (Figure 1.7).

Doing a quick Google Search on the term ‘OWoodflint’ reveals 3 pages (1 from Twitter and 2 from GitHub, Figure 1.8). I have decided to go for the Twitter link since the first question (Figure 2.0) is “What is this users avatar of?”, and it could be the avatar from Twitter or GitHub.

![Google Search](https://user-images.githubusercontent.com/29344252/172440736-5a9059cb-d6f7-416d-aed1-61696cf7f5e5.png)

- Figure 1.8 - Google Search for "OWoodflint"

![Task 1](https://user-images.githubusercontent.com/29344252/172440837-8c998d97-893e-4486-b2ce-5df74e98ac56.png)

- Figure 2.0 - First Question from Task 1

The Twitter profile will reveal the answer for the first question. Now, going back to the other links available from the simple search of ‘OWoodflint’. I decided to open the /people_finder page and straight away I found two other answers (Answers do not have to be in order).


