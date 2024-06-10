# Description

Theme customization is one great feature on the KDE stack that users make use of heavily, for reasons that could go from personal taste, features or even acessibility issues. There has been significant progress towards consistency, modernization and accessibility of KDE's UI and Breeze's recently. In order for KDE to increase its userbase, it needs to respond to the plethora of form factors and display scales that vary greatly. It also needs to be able to adapt to different types of user input methods and themes, and do this all while maintaining cohesion across its ecosystem

Since there are many devices that people use that come in different form factors that also have different display scales, KDE Plasma should adhere to a responsive UI/UX design policy that handles that variation of form factors. The concept is simple and can be approached in a way similar to web development; especially since the technology behind KDE Plasma, Qt, specificially specializes and stresses the fact that it is cross-platform and scalable. The KDE application Discover can be the example of what responsiveness should look like.

KDE Plasma's UI should also be able to adapt to various input methods. The user-experience (UX) should feel complete while using all the different various types of input methods. Currently, "touch mode" can feel unintuitive. KDE Plasma's UI should be treating touch input as touch input instead of tweaking the UI so that the user can use touch input as though they were using a mouse. There are also issues such as different components scaling different with different display scale settings; e.g., SDDM display does not reflect the lockscreen scaling when the system's display scale is scaled up.

KDE Plasma's UI should feel complete, and it cannot feel complete with separate components behaving and looking differently. A good example would be with Discover and System-settings; they both have similar layouts, however, Discover has a responsive UI while System-settings does not. The display scaling issue mentioned above could also serve as an example of cohesion.

# What it will take:

- People willing to look across the stack for common use cases for components and proposing styles and behaviors that could be used across many apps.
- Feedback from artists and UI designers so a good UI/UX policy can be created and agreed to
- Individual apps devs would need to be on board, unless some easily accessible api for customization of each element or component is provided so they can keep whatever style or layout they want, in case they don't like whatever common style is settled.
- A developer's guide to implementing the new UI/UX policy to applications and elements needs to be created
- Porting of existing interfaces to existing or eventual new components or style

## Initial Project Team Organization

* UI/UX policy & guide team
* Application developer/team
* Plasma component developer/team
* Input method (e.g., touch-mode, etc.) developer/team

## Initial Roadmap

* The acceptance of this goal.
* The creation of the UI/UX police & guide.
* The curation and prioritization of the bugs & features that fall under this goal.
* The development that will fix the bugs and add the features.

# How we know we succeeded

Feedback from users, a reduction on the usage of theme-related customization options, reduced number of bug reports related to User Interface, either due to changes on the default layouts and themes or to reduction of usage of third party themes.

# Champions

The team is:

* Diego Damohill
* Donald Menig
* XXX

# I am willing to put work into this

* add your name

# I am interested

* add your name
