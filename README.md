IITMLatextResume
================

>Compact LaTeX Template for the standard institute format. This is a modification of MR Bharath's LaTeX template. I've made it more compact and added a small table option

##Available Commands

###\maketitle 

> \author{Akshay Rangasai D}

> \RollNumber{ME10B124}

> \Address{415, Narmada Hostel, IIT Madras}

> \PhoneNumber{+91 9940070478}

> \Email{akshayrangasai.d@gmail.com}

> \begin{document}

> \maketitle

> .....

> \end{document}

This makes the title, like in all LaTeX files, but thank to MR Bharath, who overloaded that function, it draws a fancy table sort of a thing to create a nice title that matches the institute standard resume format.

###\EducationTable
This is a an environment and must be inside the *\begin{}* and *\end{}* commands. 
> \begin{EducationTable}

> \EduDetails{Program}{Institution}{CPGA}{Year}%{5/25}

> \end{Educationtable}

The *\EduDetails{}{}{}{}* is a fancy modifier to fill it up in a table. If you're pretty well versed in LaTeX, you can just fill it up like any normal table. But this is obviously more organized and clean and abstracts the table implementation underneath

###\section
> \section{Education}
Prints a nice all caps title with a line underneath

###\datedsection
> \datedsection{Title}{Dates}

Makes a bold, non-caps title with dates at the far end of the title.

###\Point

> \Point{Content goes here}

Makes a bullet point

###\multitable

> \multitable{Title}{Points}

Splits the page into two, basically an implementation of *\maketitle* that helps create title besides the points. Useful for clumping PoRs and Awards.
###/colorsection

> \colorsection{Title}{Points}

Gives a nice shade of grey as background to sections

###Courses

> \begin{Course}
> \Point{Course 1} \Point{Course 2}
> \end{Course}

Displays courses as a 3 coulumn thing on the render. Useful for people who want to put up courses on the resume.

This are the basic functionalities of this template, shout-out to MR Bharath who had done most of the work on this, the custom fields and all that. I just modified it a bit to make it more compact and a few cosmetic changes. I also added *\multitable* to make it easy for somebody to use this and for flexible formatting.

####Credits

*[@catchmrbharath](https://twitter.com/catchmrbharath)*, *[github](https://github.com/catchmrbharath)*.
The original one can be found *[Here](https://github.com/catchmrbharath/IITM-Resume-Class)* 

