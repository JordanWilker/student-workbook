# Journal Week 3 Day 3

What are the two common operations that we will set in the handler?

What do you have to make sure you are doing with every Get to insure the value does not become undefined?

What are some of the benefits of the proxy object that we are using in our structure for applications?

1) The two main common operations are set and get. Set will make something equal to something, while get will access information.

2) You have to return something on a get. If you do not, you will get undefined.

3) It helps keep your info safe. It prevents users from accessing your information, since nothing that they are doing is changing or accessing the actual values, just the proxy state.

Daily Challenge
https://github.com/JordanWilker/latewinter2021-gregslist