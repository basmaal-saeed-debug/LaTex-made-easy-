# LaTeX-made-easy-
# Welcome! 
This will be a really simple opensource library where I compile all the basics of LaTex, for anyone else who's also willing to learn how to use it, since writing math using standard 'insert' equations often leads to really distorted and poor notation. 
heres a comparison, top is LaTex bottom is the 'insert equation' on google docs

<img width="148" height="266" alt="image" src="https://github.com/user-attachments/assets/4efd3f75-a500-45f0-b77c-8853f174b510" /> <img width="148" height="266" alt="image" src="https://github.com/user-attachments/assets/a74d7379-8855-4894-a664-e1649e694b10" /> <img width="148" height="266" alt="image" src="https://github.com/user-attachments/assets/0a157c34-2283-42cc-937a-3e47608977bf" /> <img width="410" height="266" alt="image" src="https://github.com/user-attachments/assets/c2b85ad2-dfc6-454c-b0a0-040be576ed73" />




While one is of course easier, it doesn't satisfy that itch to produce sophisticated looking math papers, especially with all the elegant symbols out there 

# How to install LaTex in google docs 
Of course there can be other ways but this is what I did and believe was easiest for me
1. Firstly, you must open a doc and click on 'extensions'
2. Next, click 'add ons' then download "Auto-LaTeX equations"
3. Once downloaded, click on 'extensions' and select "Auto-LaTeX equations"
4. Thats all!

# The core mechanics 
Firstly before anything every symbol or equation must be wrapped with delimiters which are either $$ or $, which separate what requires to be rendered and what is normal text.  
[NOTE!] In order to get the dollar symbol on mac -> option + 4 or shift 4 depending on the kind of keyboard

**Inline math** using $
This is when a quick symbol or variable needs to be embedded within a paragraph, this ensures the rendered symbol stays flat and matches the text baseline without making those awkward spaces 


**Display math** using $$ 
This is when you have a massive important formula which needs to have its own dedicated space. It forces the equation to center on a brand new line creating a nice amount of breathing room around it. 

**commands** in order to enter a command you must add a backslash when you start it (for short commands such as fractions) and sometimes before you end it (only for multi line workspaces such as a matrix or multiple aligned equations), for instance \frac{x}{y} only needs a starting tag and $$\begin{matrix} ... \end{matrix}$$ needs an ending tag. 

Different commands include: 

1. \sqrt{x}  (square root)
2. \log_{b}(x)  (logarithm)
3. \ln(x)  (natural log)
4. \infty   (infinity symbol)
5. \frac{dy}{dx} (derivative)
6. \lim_{x \to y} (limit)
7.  \int f(x)\, dx (indefinite integral wrt to x)
8.  \int_{a}^{b} f(x) \, dx (definite integral with bounds)
9.  \sum_{i=1}^{n} (sigma notation)
10.  \bar{x} (mean of x)
11.  \in (is a member of)
12.  \notin (is not a member of)
13.  \cap  (intersection)
14.  \cup  (union)
15.  \text (to input text) 

Now for the symbols, backslash also needs to be used 
\pi 
\theta
\beta 
basically \anygreekletter

(*from now on, I won't be including the delimiters so my text does not get rendered so you can see it but don't forget those delimiters!*)

**What is {}**
curly brackets are used to 1. group numbers 2. define the arguments for previously stated commands. The other also matters since \frac{1}{2} is 1 over 2 and \frac{2}{1} is 2 over 1. Generally the first argument is on top and the second argument will be on the bottom

**superscript and subscript**
^ is used to say something is superscript or rather on top and _ is for subscript or rather something is under

if you are also wondering why integrals had the term " \,dx " it is since the computer ignores spaces entirely and \, is a command of it's own which tells the computer to add a tiny spacing. 

**more on spacing**
\, thin space

\: medium space 

\; slightly larger space than medium 

\! pulls characters closer 

\ regular space

\\ row breaker, the equivalent of pressing enter 

\quad 1 full character width of space 

\qquad 2 character widths 

and these are stackable unless you want to use the custom spacer
for instance  $$x= 5 \hspace{3cm} \text{this gap is exactly three 3 cm wide}$$

