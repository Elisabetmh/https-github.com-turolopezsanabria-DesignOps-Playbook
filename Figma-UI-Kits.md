# Libraries and UI Kits 

At Adevinta we have UI Kits in Figma Team Libraries to speed up the design process. They are structured with our [atomic system](https://design-systems.gitbook.io/design-systems-playbook/design-system/atomic-design.md) and allow us to have a reusable, scalable structure that provides us with consistency in our products.

![Global structure of UI Kits Adevinta Spain](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-01.png)

## Structure and organization of Adevinta Spain
### UI Kits by vertical

Each vertical has the necessary libraries to work on their projects and they are available automatically when a new file is started, divided by type of content

- Brand Foundations
- SUI
- React Brand
- Native
- Adevinta Common Library

![Example of automatic libraries in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-2.png?raw=true)

You can deactivate the UI Kits that you don't need for a project and thus focus on the ones that you are going to use. You can reactivate them later if, for example, the project grows to another platform and you need to use another UI Kit.

![Activate/Deactivate libraries in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-3.png?raw=true)

## Special cases
### React Libraries
 
2 React libraries will be created, one for Web and another for Tool in the case that they are needed. Example: Fotocasa & Fotocasa Pro or Coches.net & Coches.net Pro

![Example cover React libraries in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-4.png?raw=true)

### Libraries Native
 
Real Estate and InfoJobs, when using purely native components, have separate libraries, in the case of Milanuncios and Motor, when using custom components they will be housed in a single unified native library.

![Example covers Native libraries in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-5.png?raw=true)

## Structure
 The files in Figma are structured in a common way, organizing the pages within the file according to the design proposal.
 
### Cover & Info
Indicator of the project and scope

![Example of the UI Kit Cover in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-6.png?raw=true)

### Pages
They will be used to prioritize the sections of the files

![Example of the internal structure of the UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-7.png?raw=true)

### Key Screens
In order to speed up and facilitate design proposals, we propose grouping the templates of the main screens for quick access. These will only be hosted in the React or Native UI Kits as applicable.

The following main screens will be represented:

- Home
- Listing
- Detail
- Login
- Publish (PTA)
- My profile
- My Ads

Together with the common functionalities:

- Filtering
- Favorites
- Alerts
- Chat

The canvas will be organized with elements from the [common library](https://www.figma.com/file/0QxwRRgAU7206f2CjVPwzs/Adevinta-Common-Library?node-id=1776%3A561&t=eG2pOq7XW7xDW0Cj-0), they will contain the following:

- [Separator Header](https://www.figma.com/file/0QxwRRgAU7206f2CjVPwzs/Adevinta-Common-Library?node-id=2207%3A4761&t=eG2pOq7XW7xDW0Cj-0) to indicate screen or functionality.
- [Owners](https://www.figma.com/file/0QxwRRgAU7206f2CjVPwzs/Adevinta-Common-Library?node-id=1954%3A2738&t=eG2pOq7XW7xDW0Cj-0) of the key screens 

The Owners of the Key screens will be the uxers of each team that are working on those screens or functionalities, who are in charge of updating them every time there is a change in them with the help of the DO .

The nomenclature of the screens will be established according to this formula:

> Page+State+Platform

Examples:

- home-logged-android
- listing-empty-ios
- detail-unlogged-mobile

Special case for the UI Kit Cross in which the vertical will be added at the end

Example : Name screen/Vertical

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-8.png?raw=true)

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-9.png?raw=true)

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-13.jpg)

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-11.jpg?raw=true)

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-12.jpg?raw=true)

![Example of the internal structure of the canvas in the Key screens of the React UI Kits in Figma](https://github.com/turolopezsanabria/DesignOps-Playbook/blob/master/ASSETS/Libraries-13.jpg?raw=true)

### Canvas
The organization of the canvas will be in alphabetical order using the same templates to group and separate sections.
![Assets to organize the UI Kits canvas in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-14.png)

![Example of the canvas structure Colors - UI Kit Foundations in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-15.png)

![Example of the canvas structure Typography - UI Kit Foundations in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-16.png)

![Example of the canvas structure Grid & Layout - UI Kit Foundations in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-17.png)

![Example of the canvas structure Icons - UI Kit Foundations in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-18.png)

![Example of the component canvas structure - UI Kit in Figma](https://raw.githubusercontent.com/turolopezsanabria/DesignOps-Playbook/master/ASSETS/Libraries-19.png)


## Using components
 
### Instances
 
Instances are copies of reusable components in design (you will see them represented in Layers with an empty purple diamond). They are linked to a source component (either from a library or from the document itself) and will receive all updates to the component.

These instances allow you to customize the content in each copy (icon, text...). If you need to change the spacing of the elements, their order or add a new element, you must do it from the component itself (more info below in Component iteration).
 
### Variables
 
Some of the components have customization variables. When you have selected an instance of a component, you will see what possibilities it allows in the sidebar on the right.
May also have nested components. By double clicking on an element, you will be able to see if it has more customization options with their respective variables.

>**Can't find the variable you need?**
>Some components do not have all their variations represented (eg Buttons in SUI Components do not represent disabled states). If you need to show an undesigned state in a specific instance of the design, you can create it by changing the properties of that component instance or if you really think it would be useful to contemplate those variables in the library, check with your UX Team if they also see that useful and you can create them in the library without any problem.

## Component iteration

Before iterating a component from a library you must first check if:
 
- The component does not allow you the customization you need through its variables.
- The iteration you propose will work where the component is already being used (talk to FE if you don't know where it's being used).
- The iteration is consistent with the rest of your UI Kit and the [Brand Manual] of your vertical.
- The iteration is feasible for FE and applies to that component and not to a nested component (talk to FE to explain how it's set up. You might find you can do a lot more!).
 
Once verified, you must iterate your component in the UIKit and update the library by writing a commit message (more info below in Version Control) so that other UX can make use of it. At the same time, you must mobilize its creation in code depending on the process in which you are working on your project (jira in your team or github issue).
 

Example of a commit in a library
 
## New component

Before creating a new component to a library you must first check if:
 
There is no other existing component that can work for you. It could be a variable of an existing component.
The component you are creating will have a recurring use in your vertical. Otherwise you should not componentize it (FE will help you detect it).
The component you are creating is consistent with the rest of your UI Kit and the [Brand Manual] of your vertical.
The component is feasible for FE and you have agreed to its creation.
 
## Version control

When you are going to upload an update to a library, remember to put a commit message about what you are updating. It is very useful for the rest of the UX that makes use of it because they will have to accept these updates in their projects and they will have to know what has changed. In addition, it allows us to have greater historical control of what we are designing and gives us the possibility of going back to a previous step if we have made mistakes.
 
You can see the [explanation here.](https://www.twitch.tv/videos/1577941857?collection=ifM8i4FODhfj7Q)
 
## New library

If you need to create a new library for your vertical, contact Design Ops so that they activate it and the rest of the UX can use it.
