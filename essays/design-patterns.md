---
layout: essay
type: essay
title: DP – Design Patterns, Not Dynamic Programming
# All dates must be YYYY-MM-DD format!
date: 2018-11-29
labels:
  - Learning
  - Design Patterns
---

## Would you Rather…
As you are working on your final project for your Software Engineering class, you run into a problem (something is probably undefined again). 
Option A: Spend hours on end attempting to fix the problem with your limited knowledge. Pull an all-nighter, pull your hair out, and by the end of all of your suffering, you still haven’t made much progress. 
Option B: Steal the solution to a similar problem that was developed through the blood, sweat, and tears of people much smarter than you, and adapt it to fit your needs. 

I don’t know about you, but Option B seems much more appealing to me. You may think that you know the best solution for this situation or that other solutions are outdated and no longer apply to this specific problem, but if you examine the fundamental aspects behind the code, you may find that the general approach still applies to the most common problems in software engineering today. 

Design patterns are general templates of solutions that can be adapted to solve frequently occurring problems in software design. Rather than actual code that you can directly paste into your program, they describe how to approach a specific type of problem or scenario. Alone, they don’t amount to much, but when applied correctly, they can vastly improve quality of your code while also reducing the time it takes to produce results.

## Common Design Patterns Explained in Plain English Reimagined (as People and Pokémon)

The Factory Design Pattern is basically a fancy constructor that is used to create adaptable objects. It is my favorite design pattern because its flexibility opens up innumerable options, making things much simpler to implement. The Factory Design Pattern is similar to a blank slate. Depending on how you implement it and the parameters that you pass in, it can transform in to completely different objects. 

The Singleton Design Pattern ensures that there is exactly one instance of a class. This creates a global state to ensure that when you reference it, you know that you are accessing the most current and up to date information.

The Observer Design Pattern makes sure that all of your different components are all on the same page. If you have ever subscribed to a YouTube channel, then you are an observer. When there is a new event (a new video was posted), all of the observers (subscribers) of that object (channel) are notified of the change and react accordingly. 

Finally, the Model-View-Controller (MVC) Design Pattern basically groups the code into three categories (model, view, and controller), so the developers working on a specific category don’t clash with the developers working on other categories. 
The MVC Design Pattern is similar to three students working on a high school science project, who divided up the work to utilize their individual strengths (or to minimize face to face meetings).  
The Model is the data and information that the program references. The developers working on the Model are similar to the researchers who compile all of the relevant/necessary information for your project and basically write the research paper. The View is the user interface, which is the display shown to the user including interactive elements, such as buttons and input fields. Developers working on the View are the creative artists that build general layout and appearance of your final product, similar to building the display board for your project. The Controller communicates between the Model and View, making connections between the UI elements in the View and the appropriate data in the Model. The Controller assemble the whole project and bring everything together. In the analogy, the Controller would be the one printing out the data from the Model and pasting it into the corresponding categories in the layout on the display board constructed by the View. 

## Knowing is One Thing, but Implementing is another 
When I first learned exactly what design patters were this week, I was surprised that I had already used them quite a bit during this semester and even in the past. I even used almost all of the design patterns above in just my final project for my ICS 314 class. I used the Factory to create profiles and clubs and to render the cards and pages to display them. I used the Observer Design Pattern whenever I had to deal with event handlers for getting any type of user input. I also used the MVC Design Pattern, with MongoDB as the Model, React as the View, and React Router as the Controller. If you’re interested in what my group and I came up with, visit the [clUHbs homepage]( https://cluhbs.github.io/).



