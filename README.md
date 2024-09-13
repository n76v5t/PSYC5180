java c
PSYC5180 Quantitative Methods I
Homework #1  DescriptiveRegression Quant I F24
1) rules of summation:
let x<-c(1,2,3,4), y<-(-2,-3, -7, 2), and a<-7.a) show that the sum of a (with n=4) (a+a+a+a) is the same as 4*7.a. 
b) show that the sum of a*x is the same as the a*(sum of x)
c) compute the sum of (x+y) and show it is the same as sum(x)+sum(y)
2) in R, make up a data vector x (x<-c( )) with n=4 or n=5 values in it (within the c()).  coding
Compute the mean of x.
Calculate the sum of the n values after subtracting a constant C.  You can do this in R as
dev<-x-C, where x is your data vector and C is a number (you choose).
now square dev (dev^2) [look at the values!], and sum it (sum(dev^2)).  
Repeat that calculation for 3 different values of C.  Then repeat it once more with C=the sample mean of x.
Compare the four results.  Which is smallest?
3) compute the weighted mean of x, with a different weight for each value in x
(one way to start this is make a vector of weights, w, and then do wx<-w*x to weight the values of x by the values in w).  Be sure you look at the values of wx to confirm you did this as you intended.
You cannot do this simply using R’s ‘mean’ function!  (you could use ‘weighted.mean’ — see the help — to check your answer)
4) take these data: xx<-c(1,2,3,22,43,5,6,7,68,100)
a) compute the 10% trimmed mean ‘by hand’, meaning make a new vector xxx from xx and compute the mean of xxx.  See the help for “sort()”.  Here’s a trick: xxx<-xx[start:finish] – put in your own numbers for ‘start’ and ‘finish’).
b) use R’s mean function: mean(xx, trim=0.1) to confirm your answer.  [Note the ‘=‘ in the function call, not ‘<-']
c) compute the 10% winsorized mean of xx. This one will require a bit more typing…
Problems from MMC:
1.109 .  If you do this in R, first make a vector of x values, then plot (x, dnorm(  )).代 写PSYC5180 Quantitative Methods I Homework #1 Descriptive&Regression Quant I F24
代做程序编程语言  See the slides.  One way to plot multiple plots on the same graph is to use ‘plot’ for the first one, then ‘lines’ for subsequent ones.  See help(lines).
1.110 
Why does the height of the curve change as SD increases?
1.126  you can use ‘pnorm’ to get the answer but be sure to draw a plot of pnorm as a reality check.  
To shade in a region of a plot as the problem calls for is a bit tricky in R.  But it is fairly easy to mark off positions on the horizontal axis.  Try adding (after the plot) a line like segments(zval,0, zval,pheight) with your Z score for zval and a guess at the pheight you want the line to go up to.
[this is a great example of why I don’t want to get caught up in the details and make this class about R — I could tell you how to do this using ‘polygon’ but it just isn’t worth the time.  I have code to do it if you want to see it]
1.128
2.152
99.1 See the “Regression Homework.pdf” file on Canvas.  a) Type in the LinRegression code.  Run each code block using the green triangle at the top right of each block. codingb) Make up some data for x and y.c) Search for “ADD COMMENT” and add comments to explain what each particular line of code does.d) When you’re done, click the ‘Knit’ buttom to generate the HTML output to send in.
99.2 Suppose the world’s surface temperatures over years is distributed as a normal distribution with a mean of 59 deg (Fahrenheit)and a standard deviation of 10 deg.
(a) Suppose that global heat deaths occur at a high rate when the temperature exceeds 79 deg (2 sd above the mean).  How frequently will this happen?  
(b) now suppose that global warming causes the mean to increase a trivial-sounding 3 deg (no change to the SD).  Now, what percentage of the time would there be catastrophic heat deaths?
(c] can you explain this?  Draw graphs in R to explain your answer.

         
加QQ：99515681  WX：codinghelp
