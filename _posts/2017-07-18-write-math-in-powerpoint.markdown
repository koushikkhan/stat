---
layout: post
comments: true
title: "Embedding Mathematics in MS Powerpoint slides"
date: 2017-07-18
use_math: true
---

Have you ever faced difficulties to create math-heavy technical slides for your upcoming talk? I hope you have.
If you are a $\LaTeX$ geek, then possibly you have used Beamer, but believe me or not, it is time consuming.

This post will talk about creating math-heavy slides using PowerPoint.

## Prerequisites

+ **Windows and Office Powerpoint:**

   Here I am assuming you are using Microsoft Windows OS and Powerpoint installed. I have tested this on Powerpoint 2010,
   but I'm sure that the plugin we are going to use, will work with newer version of Powerpoint as well.

+ **Getting your $\LaTeX$ distribution:**

   Next thing that you need is a $\LaTeX$ processing engine. [Miktex](https://miktex.org/) would be good one for Windows platform. [Download](https://miktex.org/download) the Miktex setup following your os version as well as system architecture, and install it
   right away following the instructions properly.

+ **IguanaTex plugin:**

   The last thing we need is the plugin. Download it from [here](http://www.jonathanleroux.org/software/iguanatex/download.html). Now follow the steps,
   below to install it in Powerpoint:

   * open a blank presentation and go to $\text{File} \rightarrow \text{Options} \rightarrow \text{Add-ins}$
   * open the drop down list under $\text{Manage}$ and choose $\text{PowerPoint Add-ins}$ and select $\text{Go}$,
     you would get a new window $\text{Add-ins}$
   * select the option $\text{Add New...}$ and locate the plugin that you've just downloaded and close it

   If everything goes right, IguanaTex has now been installed. Restart the Powerpoint and you will get
   **IguanaTex** menu under the menubar.

## How to insert $\LaTeX$ symbols and equations

Start with a new presentation or you can open a file created earlier. Make your template ready, it is not mandatory, just for your own use.
Click on the **IguanaTex** menu from the menubar and select **New LaTeX display**. You would get a new window created by the plugin as below:

![test](/images/display_latex.png?style=centerme)

As you can see, you can insert your own $\LaTeX$ preamble over there and also insert external packages if those are already available in your system.
Now you are ready to put actual $\LaTeX$ code within `\begin{document}` and `\end{document}`, once completed, click on $\text{Generate}$ button. An image
of the newly created symbol or equation would be generated. Now, keep that image at the correct place as per your need.

That's it. Isn't it simple?

Hope you enjoyed it. Happy $\LaTeX$-ing with Powerpoint.
