# Journal Week 5 Day 3

In simple terms what is a sub-document?

When might you use a sub-document?

How do you add to a collection of sub-documents? What about editing them?

1) A subdocument is a document nested inside another document. In mongoose, sometimes they are called embedded documents.

2) If you want to store info inside of other info. For example, if you want to write down a name of a couple different groups, and the people inside of the group, you can write a new schema for the groups, and have the members inside the group schema.

3) They are mostly in the forms of arrays, so you just use the find one, and edit the array to change them. To add them, just add the array.

Daily Challenge 
https://github.com/JordanWilker/Week-5-Day-3