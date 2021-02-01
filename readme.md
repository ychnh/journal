# TODO
Review the connections btw Zorn, Ax, and Well Ordering
* focus on zorn-wo

# Overview
Here is a journal which I attempt to log and focus on the process of problem solving.
This marks a shift from the previous approach of logging the varying discoveries which I have encountered
to concretely breaking down the process of approach and understanding the problem at hand.
Why focus on the process?

I think you should not measure progress from a day to day basis on the number of pages of proofs you complete.
Because some are more difficult than others.
*The journey is more important than the destination*

# 210126

### For cardinal numbers a,b one of the following is true. a<b a>b a=b
If I cannot form an injection in 1 direction, i should be able to use the failed injection to form an injection in the other direction.
Why would it fail? becacuse it doesn't have enough elements in the image to embedded.

If we cannot form a 1-way injection, there should be a way to form the injection the other way.
*What do we need to continue?* 
We need the mapping, it would be nice to find the exact point at which it fails or the point right before where it fails.
*Can you construct it?*
What involves in the construction?
We see an example of construction by Zorn's Lemma. 
This type of construction is interesting and is quite fundamental 
*How is it similar or different from what you know?*
It is simliar in the sense that you iterate
Wait the well ordering principal is a product of zorn
And induction is based on this
So yes. It is induction.
*How is it different?*
From a high level, this problem doesn't prove the property for all elements, in a upwards fashion
Instead it finds a specific point, the maximal point which satisfies a particular property.

During typical induction i have done before I have proved something for basecase
and extend this to all n
In the proof of induction is that if it were false then you look at the minimum of which it failed and step once from here.
In this proof, I look at the maximal element of the family and step once and show that it cannot be true to prove a particular thing about family



### On having a meaningful/tangible goal
When i was writing a small tool in python, i felt a remarkable difference in attitude compared to doing mathematics.
What is the difference? I think the attitude aligned in similar way should help in your pursuit of the problem
You have got to want it bad i think

# 210122


### Cardinality of A,B must be <,>,or =
When I do not know what to anything
*Is there something more fundamental which I can use to define what seems natural?*

When do I use contradiction? When do I not use it?
*Whichever method gives you some nice objects to work with as a starting point.*

### Revisiting Axiom of Choice
I was thinking back about the Axiom of Choice
I dont have a clue what they were or how to prove the relationship between them.
I think this goes back to the point that I must be better at problem solving, 
not memorize or recall the relationships between theorems.

### If the cardinality of A,B is A<B and B<A then A=B

Ok so I finally broke free of the problem, after narrowing down the problem using (what must be true)
I had trouble wrapping my head around the objects in the problem.
What helped was 

*Going through the problem in my head again*
*working through the problem again*
*like rereading a book from the beginning*

The second thing I realized that I had trouble and issues with was

*Set good starting points*
*Perhaps more than one*
*And have confidence in them that they are good starting points*

Often times when I start a new problem, the initial statements given in the problem give me a rush and a surge of joy as it gives me what I percieve as a good/solid starting point in which to work out the problem. Similar points must be made during the process of problem solving, and treated with the same kind of faith and trust.


# 210121

### If the cardinality of A,B is A<B and B<A then A=B

Continuing the problem. You initially proposed a simple way to construct a bijection which had some problems.
Which was f combined with ginv for a g(f(A)c), a subset of A

How can ---- change to satistfy the condition?
* This question helped me to devise a plan to modify the initial function which was not working
What is the complete set of possibilities?
* Perhaps this was a question that I should have considered earlier.
What must be true? What cannot change?
* This helped me to narrow down some connections between the two domains, leaving out some guesswork.

### a fresh start

Sometimes we all yearn for a fresh start

### A hill to die on.

Often times I think it is important to choose a good hill to die on or giveup.
Just as in working out sometimes you know when you need to stop the current approach and readjust.
Or focus on a particular point more than others.

At the same time it is really important to spend your time to really learn.
On the contrary, spending time just reading definitions and skipping far past ahead is not really ad advised course of action.
I have done this in the past and during all of my life and I have to say that it has led to some regrettable consequences
In which I have not achieved much or have done alot.
I say stick with the current course and keep going. You must endure it.

# 210120

### If the cardinality of A,B is A<B and B<A then A=B

The solution involves constructing a bijection.
I have been struggling with this one for a while.

The first point in difficulty was not knowing to go with contradiction or a direct construction.
Should I go with contradiction or a direct construction?
Why would one prefer one over another?
What kind of problems have contradiction worked better than direct construction ? (vice versa)

The second point was not investigating an idea which I had further.
I had constructed an object. But I had not carefully considered it.
I had brushed it off because it seemed too complicated. And complicated things do not lead to solutions.
What makes it complicated?
Is it actually complicated?
*Such assumptions are dangerous*
What makes it complicate
Is this a valid object?
If not how can it be improved?

Objects and methods



