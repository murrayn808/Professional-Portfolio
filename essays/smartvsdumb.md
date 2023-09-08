---
layout: essay
type: essay
title: "Smart vs Dumb Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Software Engineering
  - Learning
---

<img width="350px" class="rounded float-start pe-4" src="../img/stackoverflowpicture.png">

## Smart vs. Dumb Questions

  In my [smart question](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) example, I found a StackOverflow post that aligns with the principles of asking questions effectively, as outlined by Eric Steven Raymond and Rick Moen in ["How to Ask Questions the Smart Way."](http://www.catb.org/esr/faqs/smart-questions.html) Smart questions are characterized by being explicit, having meaningful and specific subject headers, having diligent research, being precise and informative, describing symptoms not guesses, being chronological and focusing on the goal not the steps.

In the smart question that I chose the poster asked “Why is processing a sorted array faster than processing an unsorted array?” In his post, he included copies of his code in C++ and multiple tests created by himself. He pointed out that without a certain line of code which sorts the array, the code took longer to run. He then included another test run using Java and the results were similar; without sorting the array the code was taking longer to run.
  
One user's response to this question was related to the processor level where ‘branch prediction’ takes place. In summary, sorted arrays create recognizable patterns which the processor can interpret and use in their branch prediction models. The higher success of predictability, the faster the code can run. However, a further optimized solution was pointed out by this user in scrapping a certain if statement altogether and instead replacing it with a bitwise operation. This gets rid of the branch that is created with the if statement. It is thanks to the way this question is presented that the poster was able to get a good answer and a further optimized piece of code.
 
I think this question is a smart question because he is explicit in the way he presents it. The header “Why is processing a sorted array faster than an unsorted array,” is directly relevant to his question and it seems like the poster has done enough testing and diligent research to be ready to learn further information. He also does not flood his post with assumptions, rather just states the symptoms and the facts of what he is encountering and asks for interpretation.
	
In the [dumb question](https://stackoverflow.com/questions/77064518/how-to-solve-this-403-error-in-our-website) I chose, the poster barely includes a description of their issue, the header is incredibly vague and there are no attached screenshots or visuals to look at. It also seems like it is written in broken english. The question is so bad that it seems that stackOverflow closed it to outside responses completely. 
