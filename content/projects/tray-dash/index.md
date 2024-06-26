---
title: "Tray Dash"
description: "An endless runner where players balance a tray of food items and deliver them to their destination. Available on the Google Play Store."
summary: "An endless runner where players balance a tray of food items and deliver them to their destination. Available on the Google Play Store."
date: 2024-06-19T12:00:00-06:00
showReadingTime: false
showWordCount: false
tags: ["Unity" , "Game Programming", "Game Design", "Project Management"]
draft: false
---
{{< figure
    src="/images/playstore.png"
    alt="Get it on the Google Play Store"
    caption="Click the image to go to the Google Play Store listing."
    nozoom=true
    href="https://play.google.com/store/apps/details?id=com.TrayDash.TrayDash&pcampaignid=web_share"
>}}

{{< youtubeLite id="JsjwPBjlujk" label="Tray Dash Gameplay" >}}

Tray Dash was born as a school project for the 5th semester project class. It was a game where you had to balance food on a tray. The idea originated when my classmate Itzel remembered a 2D mini-game within a mobile game called "Egg Baby," where you had to balance an egg on a spoon until you reached the end. In our case, we decided to add another dimension by making it 3D and increasing the number of objects to balance, this time on a tray instead of a spoon.

{{< youtubeLite id="PtLi7jzY2Ao" label="Egg Baby Minigame" params="start=6">}}
Egg Baby Balancing Minigame


## A Rocky Development Start 

The development of the application started quite differently since it was my first time leading a team of five people, including two artists and three developers. During the previous vacation, I had researched and taken a course on Jira for product management. So, when the semester began, I decided to take on the role of director and project manager. The first four weeks were spent mainly organizing our Jira page, trying to keep everything in order. However, during the first semester review, I realized that spending so much time on project management was going to end up being a setback for the game’s initial development. Besides being the project manager and director, I had also been assigned the role of lead programmer. Although I had this title, I wasn’t fully committed to it because I was also handling project management, which affected the progress.

## Shift in Focus

After the first review, I decided to focus entirely on being the lead programmer. Following this, we continued working on the game. The project was simple in concept, but I had hoped that it would be the first game I was truly proud of developing and the first project to be fully completed. I had published other games before, but none felt complete and polished. That became the primary goal of the project. As the weeks passed, the game progressed more once I focused solely on development. However, by mid-semester, our professor told us that we were far behind and had a lot to catch up on. The majority of the work was done in the last two months. In the end, the project turned out well, with well-organized art and programming. Despite some personal challenges with programming, everything came together.

## The Importance of Clean Architecture

Initially, everyone could work on their parts, but towards the end, I was the only one who fully understood the programming, making it difficult to ask others to make changes or fix issues. The main lesson learned was the importance of maintaining a clean code architecture. When working alone, you might understand your code’s structure, but in a team, it needs to be modular and clear for everyone to understand and modify easily. Additionally, we wanted to implement a better tutorial for new players, which required creating another scene to separate systems and more. Despite being a good game that people enjoyed, the code wasn't very scalable. During our third review, the professor noted that he liked the game and felt it was relatively polished, but the biggest issue was the controls.

{{< youtubeLite id="IyWWfEE-r3w" label="Tray Dash Tutorial" >}}

## A Much Needed Change

In Tray Dash, you had to balance the tray forward and backward, left and right, using two sliders. The left slider controlled the vertical tilt, and the right slider controlled the horizontal tilt. However, both sliders were vertical, making it confusing for players. Moving the slider up or down caused the tray to move in unexpected directions. We switched to two joysticks instead, which made the controls more intuitive. We also added toggles in the options menu to invert the axes based on player preference.

![Initial Sliders](/images/tray-dash/previous-sliders.png "Previous Sliders")

![New Joystick Sliders](/images/tray-dash/improved-sliders.png "Improved Sliders")

## A Successful Project 

In the end, we delivered the project on time. People found it enjoyable and well-polished in terms of gameplay. We added features like camera shake, responsive sound effects, and an animation of fireworks when delivering the food, making the experience more gratifying.

## Available on the Google Play Store!

{{< figure
    src="/images/playstore.png"
    alt="Get it on the Google Play Store"
    caption="Click the image to go to the Google Play Store listing."
    nozoom=true
    href="https://play.google.com/store/apps/details?id=com.TrayDash.TrayDash&pcampaignid=web_share"
>}}


## GitHub Repository

{{< github repo="FerchusGames/tray-dash" >}}

## Credits
Fernando Gonzalez, Itzel Llamas, Juan Rios, Patricio Perez, and Sergio Sanchez.