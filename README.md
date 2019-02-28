# LaTeX Template

## Basic Usage
There are two environments you will be mostly using; **Problem** and **Solution**.

Example:

```
\begin{Problem}
  Find the value of $x$
\begin{Solution}
  To find this, we must show...
\end{Solution}
\end{Problem}
```

The **Problem** environment has commands it will execute _after_ the text is displayed. One of these is `\newpage`. If you do not want to limit one problem per page, **remove this command**.

## Document Info
You as the user will want to edit a few lines so the title page and header comes out nicely. These items include:
1. title
2. author
3. date (or due date)
4. professor
5. class
6. header (center)

In order to edit the title, author, and date, create a coverpage enviroment and define them as shown:
```
\begin{coverpage}
    \title{Assignment_title}
    \author{Author}
    \date{Due: On Blackboard, 6pm, Friday, March 8}
\end{coverpage}
```

After this, you will need to go to the coverpage enviroment definition and edit #4 and #5 there. Lastly, near the top under the fancy header settings, change the center header to the shorthand version of your course (i.e. CS 4##).
