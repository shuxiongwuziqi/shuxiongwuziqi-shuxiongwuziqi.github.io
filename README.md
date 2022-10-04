
# How to visit my website

1. [github page](https://shuxiongwuziqi.github.io/)
2. [HKPU COMP intranet](http://www2.comp.polyu.edu.hk/~22047086g)
3. [Remote Host](http://1.12.47.133/intro/)


# Introduction of my mid project 

## Base requirement

In this mid-project, I created a website to briefly introduce myself, including my works, contact methods, and capability in different areas.

I have to claim that this website is designed by myself rather than copying other people's work since I once showed my website to a professor and he asked me whether this is other people's work.

I think my work fulfill all of the requirement presented in the course outline. My website has a title, includes my name, my picture, and a brief introduction (I don't know whether the intro is good enough). In addition, the website also includes headlines, paragraphs, tables, and images. 

For the website layout and UI, I use bootstrap's grid system, button, and progress component. 

## Extra feature

There are some extra advanced features that I want to show you later, including animations, RWD, and so on.

Firstly, you can see the `contact me` button contains a Kaomoji moving up and down to attract others to contact me. In addition, if you view my website on a desktop that has a screen width larger than 1000px and scrolls down, you can see the progress component will start the animation whenever it is shown on the screen. the progress value represents my level in this area. Therefore, you can clearly understand my expertise.

Secondly, I use `@media` and bootstrap's grid system to make a responsive website design, which means my website can fit not only desktops but also smartphones. To be more specific, I follow the definition of the breakpoint in bootstrap, and I consider how to fix my website into these different sizes of screen. For example, for the wider screen, I will show my contact information and capability statement on the right side and for the smartphone screen, I will actually delete this column and move the information to the header.

Thirdly, I also use hyperlink elements to show my work, you can click the images in my work section, and you can see the detail of my work. In addition, if you click the contact me button, you will redirect to your email agent because I research a bit and find if the href property has "mailto:" in front of your email address, the browser will help you open the email agent, which is very convenient since others don't need to remember your email address and type it manually.

Fourthly, on the right bottom of the website, there is a move to the top button. If you click it, the browser will scroll to the top automatically. For the implementation, I use the header as an anchor, and write the "#header" to the href property, which is a tip taught by our professor in the lecture.

Last but not least, I try different position values to improve user experience (maybe don’t improve). I applied `sticky` to the contact information and capability statement section. 

