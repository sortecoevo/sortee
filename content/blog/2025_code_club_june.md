**SORTEE Code Club debrief: Getting started with Shiny: build interactive applications in R- June, 17th 2025**

Author: Cecilia Baldoni, Corné de Groot & Ed Ivimey-Cook

  

The Member Engagement Committee runs **Code Club every third Tuesday of the month**. Time can vary depending on the host and will be announced at least two weeks in advance on [SORTEE's Slack](https://sortee.org/join). For more information, see [SORTEE's Code Club page](https://www.sortee.org/code_club/).

  

On Tuesday, the 17th of June, Ed Ivimey-Cook hosted a training session on getting started with Shiny, a package used to develop interactive applications in R. Shiny apps provide a useful and engaging way to disseminate research findings, as seen in the adoption of Shiny apps for methodological papers. Furthermore, apps can help streamline workflows during experiments or fieldwork, or mediate the screening process for meta-analyses (e.g., [metRscreen](https://github.com/EIvimeyCook/metRscreen/tree/master)). We first started with going through some of the basic features of Shiny. There are some great resources available on the [RStudio website](https://shiny.posit.co/r/getstarted/shiny-basics/lesson1/) about getting started with Shiny, or see [this](https://github.com/nanxstats/awesome-shiny-extensions) Github repository for useful Shiny extensions. Overall, Shiny has three main components: 1)  the User Interface (UI), 2) the Server, and, 3) the call to the Shinyapp. Each component has its underlying code within separate cross-linked tabs, to make certain actions within the app. Of these three, the server part is the most complicated and requires some practice. But luckily, there is a wealth of in-depth tutorials and resources available to make life easier. Next, we explored the code of the [metRscreen](https://github.com/EIvimeyCook/metRscreen) app designed by Ed and Joel Pick. This app was made to simplify and speed up the screening process for the inclusion of papers for meta-analyses. Here we learned about "reactive values", which are dynamic datasets that react and change based on the input from the user and are useful for storing all kinds of temporary information. We also learned about "observe events",  an incredibly important function that allows Shiny to react to user input. It takes an event, for instance, the pressing of an action button, which then causes another action to occur. Lastly, we learned that it is best to develop Shiny apps within RProjects, and that you can share them easily via GitHub or with shinyapps.io via a browser. Click [here](https://github.com/SORTEE/CodeClub/tree/main/20250617_ShinyTutorial) to take a look at the supporting slides for this Code Club session.  

See you at the next Code Club session!

**What's next?**

The SORTEE Code Club will have a summer break, so there will be no sessions in July and August. We will be back with the next Code Club meeting **on Tuesday, September 16th** (the zoom link will be posted on [SORTEE's Slack](https://sortee.org/join/)). 

  

You can check [the Code Club schedule here](https://docs.google.com/spreadsheets/d/1rOOOE7ghPduwtFftG0DJJf0DXVigAdcmQ0xdEwbKQXo/edit?usp=sharing) for upcoming meetings. To receive calendar invites in your local time zone, [sign up here](https://forms.gle/yKrEm6xAKZtom5kt7).

  

**Suggest a topic**

To propose a Code Club meeting topic, please use [this form](https://forms.gle/eZy81dUymiZNJetu8).
