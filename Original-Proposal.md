# KDE Plasma UI/UX Integrity: Responsive, adaptive, and cohesive.

In order for KDE to increase its userbase, it needs to respond to the plethora of form factors and display scales that vary greatly. It also needs to be able to adapt to different types of user input methods, and do this all while maintaining cohesion across its ecosystem.

### Responsive
Since there are many devices that people use that come in different form factors that also have different display scales, KDE Plasma should adhere to a responsive UI/UX design policy that handles that variation of form factors. The concept is simple and can be approached in a way similar to web development; especially since the technology behind KDE Plasma, Qt, specificially specializes and stresses the fact that it is cross-platform and scalable. The KDE application Discover can be the example of what responsiveness should look like.

### Adaptive
KDE Plasma's UI should also be able to adapt to various input methods. The user-experience (UX) should feel complete while using all the different various types of input methods. Currently, "touch mode" feels extremely unintuitive. KDE Plasma's UI should be treating touch input as touch input instead of tweaking the UI so that the user can use touch input as though they were using a mouse. For example, instead of making the buttons bigger to use them with a finger, add a touch gesture action instead (e.g., drag to object to close). There are also issues such as different components scaling different with different display scale settings; e.g., SDDM display does not reflect the lockscreen scaling when the system's display scale is scaled up.

### Cohesive
KDE Plasma's UI should feel complete, and it cannot feel complete with separate components behaving and looking differently. A good example would be with Discover and System-settings; they both have similar layouts, however, Discover has a responsive UI while System-settings does not. The display scaling issue mentioned above could also serve as an example of cohesion.

## Call to action
This goal is no small task! Completing the following preliminary main objectives should allow the goal to be achieved:

1. A UI/UX policy needs to be created and agreed to.
2. A developer's guide to implementing the new UI/UX policy to applications and elements needs to be created.
3. Developer's implement the UI/UX policy on KDE's applications, plasma UI components, and input methods.

This type of goal will take a lot of hard work, and I am unsure of the actual approach to the technical details of the development, but what I do know is the final outcome: a polished KDE Plasma that welcomes new and current users with familiarity.<br>

With help, I could lead this, but I definitely cannot implement it my own. Since I am limited technically, this goal would need a lot of support from the developer community in order for it to work.

### Initial Project Team Organization 

1. UI/UX policy & guide team
2. Application developer/team
3. Plasma component developer/team
4. Input method (e.g., touch-mode, etc.) developer/team

### Initial Roadmap

1. The acceptance of this goal.
2. The creation of the UI/UX police & guide.
3. The curation and prioritization of the bugs & features that fall under this goal.
4. The development that will fix the bugs and add the features.

## Conclusion

In my opinion, completing this goal would lead to a more perfect KDE Plasma user experience. I believe some work has been done that shares some of the same vision as this goal, but I think this will take that a step further. It will bring KDE Plasma up-to-date with current best design practices, giving us a solid KDE Plasma experience with great integrity.
