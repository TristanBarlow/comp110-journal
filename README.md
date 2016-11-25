## When does a Physical system compute? [1] ##
  
From my understanding, every time we type a line of code its considered to be an abstract theory, the computer then encodes the theory into a physical representation of what we have coded. It then proceeds to turn this physical representation into an abstract output for example the answer to a maths problem. Another important concept brought up is the ‘representation relation’ It is described in the paper to cross ‘the divide between the abstract and the physical’. 

The idea of encoded communication (the example being hieroglyphics) was a new perspective I had not yet considered. Upon reflection, the similarities of hieroglyphics to modern day encoded communication is apparent (Morse code for example).   how to decode the physical communication we do a computation turning the abstract ‘code’ or the hieroglyphic into a form we can understand and then back into the abstract output, the message. In this case although not stated, do they mean we are the computer. 

## Experimental Investigations of the Utility of Detailed Flowcharts in Programming. [2] ##

This paper for the most part is the compiling of several experiments where programming students are split into groups, some are given flowcharts (sometimes of differing complexity) others are not. They are then told to complete an exercise to do with programming and the results are then compared. The results are all the same; there is no difference between the subjects who used the flowcharts and those who didn’t.  Because of my own experiences, I am not surprised. The process of learning to become a programmer teaches you to think like a flowchart. When being taught how to evaluated code we were taught using the aid of a few flowcharts. I believe that a flow chart isn’t a tool to use but more of a structure on how you should think through each programming problem. Giving a group of programmers a diagram describing the process their brain would work without the flowchart will of course produce no measurable result. If for example you gave a flowchart to a group of non-programmers and created similar experiments using pseudocode they could understand the results may be very different. 


## A Fast Procedure for Computing the Distance Between Complex Objects in Three-Dimensional Space [3] ## 
This paper provides us with an algorithm to calculate the distance between two objects in any Rn dimensions. The author says the algorithm is designed to be more efficient when the objects are seen in three dimensions. In the paper the section of greatest interest to me being the section on collision detection. *****TBF*****


## Go to Statement Considered Harmful [4] #
From my limited understating a ‘go to’ statement performs a one-way movement of what line the machine will execute. The Author states “the quality of programmers is a decreasing function of the density of go to statements in the program they produce.” After finishing the paper, I believe the main concern the author has about the go to statement, is the inability of the observers to determine the state of the process (variable values etc.) at any given instances of the process. This will result in it being ‘terribly hard to find a meaningful set of variables’ and us losing our intellectual grasp of the procedure. The possible implications to industry practice? For example, you must fix a bug, not being able to track the value of the variables causing the bug will be a serious barrier to overcoming said bug. If my understanding of the damage is correct, tools may somewhat mitigate this.  The debugger found in ‘Pycharm’ IDE for example. However, because python has no ‘go to’ statements I haven’t tested. For further research in this topic I pursued the article titled “Global variable considered harmful” [5]. Reference to “Edsger W. Dijkstra” work was present in the article. W. Wulf, Mary Shaw, explain how the use of global variables can, like a goto statement can make understanding code difficult. Within in [5] 

## Reference list ##
[1] Horsman C, Stepney S, Wagner RC, Kendon V. 2014 When does a physical system compute?, The Royal Society, Vol. 470, No. 2169, July 2014.
 [2] B. Shneiderman, R. Mayer, D. McKay and P. Heller, Experimental Investigations of the Utility of Detailed Flowcharts in Programming, Communications of the ACM, Volume 20, Issue 6, June 1977, pp. 373 - 381
[3]Elmer G. Gilbert, Fellow, IEEE, Daniel W. Johnson, and S. Saythiya Keerth, IEEE journal of robotics and automation, vol. 4, no.2 April 1988
[4] Edsger W. Dijkstra, “go to statement considered harmful”, Communications of the ACM, Volume 11 Issue 3, March 1968 Pages 147-148.
[5] W. Wulf, Mary Shaw, “Global variable considered harmful”, ACM SIGPLAN Notices, Volume 8 Issue 2, February 1973, Pages 28 - 34 

