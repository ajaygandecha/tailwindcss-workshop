# TailwindCSS Workshop

This workshop aims to introduce students to the TailwindCSS web framework. TailwindCSS is a utility CSS framework that allows developers to rapidly and efficiently design modern, rich, and responsive websites without ever having to enter an external CSS file. 

TailwindCSS is one of the most popular CSS frameworks, and is used by [many companies](https://tailwindcss.com/showcase) in a wide variety of uses cases and industries. TailwindCSS also integrates seamlessly with other popular and industry-pervasive web frameworks, such as *React*, *Vue*, *Angular*, *Next.js*, *Vite*, and more.

Ultimately, this workshop aims to expose TailwindCSS to UNC Computer Science students, introduce them to CSS utility frameworks and how using such frameworks might enhance their web development skills and workflow, showcase practical usecases for using CSS utility frameworks over vanilla CSS, highlight the importance of UI/UX design for web applications, and ultimately inspire them to use such frameworks to enhance the style and UI/UX of their own web development projects in the future.

*Students with **basic knowledge of HTML and CSS** would be able to attend this workshop without any difficulty, including students currently enrolled in *COMP 110: Introduction to Programming and Data Science* or higher.*

## Part 0: Setup

1. In order to get started with this workshop, you must have **Visual Studio Code** *(VS Code for short)* IDE installed. If you do not already have VS Code installed, install it [here](https://code.visualstudio.com).

2. Once you have VS Code installed, you want to install the **Tailwind CSS IntelliSense** VS Code extension. This extension will enable VS Code's IntelliSense to provide autocomplete and syntax highlighting for TailwindCSS classes. You can find the extension on the Visual Studio Marketplace [here](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss). 

    By pressing the green `Install` button, VS Code should open automatically and begin installing the extension. If not, you can install this extension maually within VS Code. Open VS Code and press on the `Extensions` tab on the far left of the window (icon resembling a grid of square puzzle pieces), search for *"Tailwind CSS IntelliSense"*, and install the first option.
    
3. Now that your IDE is installed and set up, the last step is to **clone this repository**. On the *Welcome* tab of VS Code under the *Start* menu, press the `Clone Git Repository...` option.

    From here, a box should appear to type in the URL of the repository. Copy [this link](https://github.com/ajaygandecha/tailwindcss-workshop) into the box and press enter. From here, all of the code in this repository should now show up on your computer!
    
**Congratulations!** Now that you have completed the setup, it is time to dive into TailwindCSS.

## Part 1: Why TailwindCSS?

Before we get started, it is good to refresh our memory on how websites and front-end design actually work.

All of the websites on the internet are made up of files of two fundamental types - **HTML** (`.html`) and **CSS** (`.css`) files.

**HTML** is a markup language used to define the **structure** and **content** of a webpage, while **CSS** adds **style** to a webpage.

Us developers, especially computer science students, often take website styling for granted. It is often left as an afterthought -- something ***extremely** tedius*, where you would be forced to implement the designs of extremely nitpicky designers. You probably begrudgingly wonder, while slaving over `.css` files, *why do I have to do this? Why is this so painful?*

See, the convention you have learned up to this point, and the convention you typically use, is that HTML and CSS remain *decoupled* - *separate* from each other. You have to constantly have to switch between files, create random element classes and IDs in your HTML files, and then connect them back to actual styles in your CSS files. When switching pages too, you lose your sense of location and structure - which nested elements are actually being styled? I am adding a margin next to *what element*? *What is even happening?* CSS even drives some people to tell themselves that they actually *hate* web development - that front-end development is not for them.

So, you ask - *why isn't there a better way?*

What if you could apply styles to elements ***directly within** your HTML files?* What if you could avoid having dozens of extra CSS files that span hundreds of lines?

Well, now you can with **TailwindCSS*.

TailwindCSS is a utility CSS framework that allows developers to rapidly and efficiently design modern, rich, and responsive websites - without ever having to enter an external CSS file. You are able to use Tailwind's style classes to apply styles to elements from within their `class` parameters.

TailwindCSS also integrates seamlessly with other popular and industry-pervasive web frameworks, such as React, Vue, Angular, Next.js, Vite, and more.

You are probably thinking, "this must be *too good* to be true - what about the so-called *best practices*?"

[Adam Wathan](https://github.com/adamwathan), the creater of the TailwindCSS framework, wrote an [extremely good article](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/) showcasing the benefits of TailwindCSS's "funtional CSS" approach, and raises key counterarguments against the currently established "best practices" of semantic CSS. I **highly** recommend reading this article if you have the chance. It really helps to explain the intentional design behind TailwindCSS, and the context for which TailwindCSS has been designed around.

## Part 2: Live Demo

## Part 3: Try It Yourself

## Part 4: Closing Thoughts



## Structure

- Review HTML and CSS (purpose of each)
- Show short example showing the link between HTML and CSS
- Explain the shortcomings of CSS
- Introduce TailwindCSS and how it works
- Open up Repl.it for live demo
  - Walkthrough of styling the CSXL checkin page live -- show styled version and non-styled version
  - This demo will just be on an HTML page - there will be no JavaScript / TypeScript involved here, as this is not necessarily relevant to the workshop.
- Create small groups of 3 and give them a fun, guided exercise
  - Guided exercise will be to style a sample CSXL workshops listing page
- Regroup
- Show how to install Tailwind in VS Code + VS Code extension
- Explain the importance of good UI/UX Design
- Closing statements
