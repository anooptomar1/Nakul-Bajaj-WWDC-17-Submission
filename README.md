# Nakul-Bajaj-WWDC-17-Submission
A quick glance at my SceneKit powered playground submission for the WWDC 17 scholarship.

YouTube Video:
https://youtu.be/bZLHSl80eTU

# Essay Answers

## Technologies I Used

  For my playground, I used different types of frameworks that would help me create a graphically entertaining session for a user. To do that, I realized I had to combine three dimensional and two dimensional animations that would be visually attractive. After some research, I decided to use SceneKit, Core Animation, Core Graphics, and AVFoundation. SceneKit helped me make a three-dimensional object central to my playground. Core Animation, Core Graphics, and AVFoundation served to make the smaller details more stunning and impactful. In addition, I had to use these frameworks so they would be as efficient as possible in conjunction. 
  My first endeavor in coding was to make a three-dimensional cube with the different faces of the cube representing various facets of my own life. I accomplished this by using Scene Kit to make a Scene Box with a cube geometry, and customized a camera, which would become the point of view of the user. After designing the movement of the box, the icons on each face, and more, I had to be able to recognize which side someone might have tapped on. This was, by far, the most difficult part of my playground. Eventually, I found out I could use SCNHitTestResult to pinpoint where some had tapped and where that was on the cube. Unfortunately, the current version of Xcode playgrounds had a bug where I was unable to store where someone had tapped. (Stack Overflow discussion: http://tiny.cc/playground-bug) So, I decided to change the method I used to store the tapped point and finally found one that worked. 
  Then, I decided to create a detailed view that would “pop out” of each side as someone tapped on it by way of Core Animation. Each view for each side of the cube contains three sub categories. For a “pop out” animation, the width and height of the view scale up over time, while the view’s background is semi-transparent with a blur effect. Particularly, I added an animation using Core Graphics that would flip the view as a transition whenever any of the sub categories were tapped. For example, if someone were to tap on the “Debate” section of the cube, they would then see a view animate as the background blur was being made. Following the animation, they could either learn more about the setup, importance, or awards I’ve received for debate and see a flip transition to a view with more details. To make my playground even more intuitive, someone can dismiss a view by simply tapping outside of it. 
  Overall, I used distinctive frameworks in purpose-built ways. By combining the graphical advantages of those frameworks, and the information I presented, I delivered a robust but lightweight package to show who I am, what I am about, and what I value. This experience of building a sophisticated playground with worthwhile technologies is one I will never forget.

## Sharing my coding knowledge

  From the time that I started becoming more involved in developing iOS apps, I have also been keen in sharing my experiences with my friends and peers at school. Often, I find myself explaining to my friends how I solved a difficult coding problem, and I have always thanked them for being supportive by listening to what I had to say. 
  Especially in the past few months, I have put more effort into teaching others computer science. I have been encouraging some of my friends to attend local hackathons, which are twenty-four hour events with the goal of developing useful software as team. Over the course of these events, I’ve enjoyed teaching them iOS development and graphic design by sharing the resources I first used to learn programming. My eager attitude towards helping others with computer science especially manifested in my seventh-grade Python programming class at school, where I had the opportunity to help my peers along with the instructor. Following that experience, I was also the lead advocate for an iOS development club at school. I had the passion for making such a club as I strived to teach others about programming as well as design, which are very important counterparts to each other. 
  Despite these achievements, I feel the need to reach a greater scope of people who can benefit from learning coding the most. I find it heartbreaking that in cities such as San Jose and San Francisco, undoubtedly the geographical center of software innovation, there are a rising number of people in poverty and financial inequality is at an all-time high. To fight this pervasive issue, it will be an appropriate option to volunteer my time for those who do not have such an opportunity either by creating my own organization, or by participating in an existing one. 
  By training and teaching computer science to the underprivileged, we can genuinely make an impact in their potential. It’s crucial that we offer a way for low-income families to learn skills that can be used in the work force. After all, someone should have the ability to pursue something that they might be interested in. Offering to teach software development to people who don’t have such a choice is a great way to start.
  Simply put, I think that I have done a lot to help others, but that I can also continue to share what I have learned over the years with the people that will benefit from it most.
