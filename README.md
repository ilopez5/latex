# LaTeX Template

## Basic Usage
There are three steps to set up your given assignment.

1. Edit `Pig.sty`, specifically the last six lines, with correct information.
2. Include `Pig.sty` near the top.
3. Begin the document with `\cover` to generate the cover page.

There are two environments you will be using; **Problem** and **Solution**.

Example:
```
\begin{Problem}
  Find the value of $x$.
\begin{Solution}
  To find this, we must show...
\end{Solution}
\end{Problem}
```

The **Problem** environment will automatically start on a new page. If a problem requires multiple pages, proceed as usual with adding `\newpage` within your work.

## Document Info
You as the user will want to edit a few lines so the cover page and header comes out nicely. These items include:
1. title
2. date (or due date)
3. author
4. professor
5. course number
6. course name

In order to do so, find and change the following lines in the `.sty` file:
```
\title{ASSIGNMENT} 							            % Edit this to change the assignment title
\date{DUE DATE}    							            % Edit this to change the due date
\author{YOUR NAME} 							            % Edit this to put your name on the coverpage
\newcommand{\theprofessor}{Prof. LAST NAME} % Edit this to add professor
\newcommand{\course}{SUBJECT 101} 			    % Edit this to change the course
\newcommand{\cname}{CLASS NAME} 			      % Edit this to change 'name' (e.g. Mathematical Modeling)
```

After this, you are set to begin your `.tex` document. See `test.tex` for a basic template.
