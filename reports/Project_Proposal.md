#Voting Complexity:
####Jared Briskman

##Abstract
This project aims to simulate elections as an agent based phenomenon, with a distribution of voters existing in some discrete, multi-dimensional opinion space.
Candidates exist as points in the space, and voters are (At least initially) are assumed to be normally distributed around a given center.
Simulating multiple voting algorithms (Plurality, Approval, Condorcet, Borda, IRV) can be achieved by assuming that people's candidate preferences go in order of Euclidean distance.

Using these simulations, limiting cases of Arrow's theorem (That no election system can satisfy all 5 fair election criterion) can be demonstrated, and visualizations of voter space can be generated.

Further expansion can be done by simulating more voting systems, and moving to a higher dimensional space.
Interesting data may also result from sweeping candidates across the space, and analyzing the results.
##Lit Review
http://zesty.ca/voting/sim/
An explanation of sprint 1 target and MVP.


https://www.jstor.org/stable/1914083?seq=12#page_scan_tab_contents
Arrow's theorem proof.

##Target

First punchline graphs as the same ones from zesty above. These can be analyzed as how different voting systems affect candidate's chances of winning under different political orientations.
E.G. Here, under IRV, one can see candidate 3 has an "M" shaped winning space.
This is non-monotonic leading to very interesting results: more approval for the candidate could cause worse results, and less approval could cause the candidate to win.

Another punchline graph could result from changing the delta between two candidates: E.G keeping one stable and sweeping the other, then plotting overall odds of winning.

##Learning Goals

Trying to find the self organizing criticality inherent to election systems. (I do believe it is there, it just may be a task to tease it out)
Data visualization in python, along with high order complexity algorithm design for voting systems.
Technical writing in an easy to understand fashion: I want to be able to clearly and succinctly share my methods and results.
