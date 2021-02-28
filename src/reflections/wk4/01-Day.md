# Week 4 Day 1

What are some of the signs and causes of Callback Hell?

What does the asynchronous mean and how are callbacks involved?

Summarize the 3 ways to avoid / fix Callback Hell

1) Callback hell is when people try to make their code run from top to bottom when calling in from API's. But javascript doesn't do that with callbacks.

2) Async means takes some time. It is used so taht functions that could take time to complete don't completely stop the code from happening.

3) Some ways to avoid callback hell is to keep your code shallow and precise. Don't make one thing try to call a lot of different things, instead try to make sure you have a bunch of different small things trying to call one thing apiece.

Daily Challenge
https://github.com/JordanWilker/Week-4-Day-1