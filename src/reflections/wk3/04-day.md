# Journal Week 3 Day 4

What problems does the Observer Pattern seek to solve?

What are the three mechanisms of the observer pattern?

Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

1) It hopes to solve the problem of updating the page. That way, when something changes, the page can draw.

2) The three main mechanisms are subscribe, the unsubscribe, and the broadcast method. The subscribe and unsubscribe set and remove events, while broadcast sends it out to all events.

3) First it checks on whether or not something is a valid prop, by whether or not it is something that has been defined in another linked script. If it is, it returns the value in a prop array. 

Daily Challenge
https://github.com/JordanWilker/Week-3-Day-4