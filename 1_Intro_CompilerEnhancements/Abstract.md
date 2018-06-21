#Modern C++ at GBTS: Standard Practices from Standard Library

#1. Intro and Compiler Enhancements

Abstract:
This is the first part of a series of talks on the level of professional C++ programmers. 
The overarching theme is sharing ideas and considerations on modern C++ practices, with minimal, self-contained examples.
Modern here means C++11 and beyond, and whenever the latest C++17 standard provides substantial enhancements they will be underlined. 
The talk shall foster good coding practices: expressive, solid, reusable and well tested pieces of code.
Discussed will be only the Standard Template Library (STL) although Boost and others third party provides even larger set of features.
Asking yourself: How to get used to something unusual? Do not un-learn old things, do learn new things.
So, what does your modern compiler do for you?
The "Rule of 3", now becomes the "Rule of 5" since we have implicit generation of constructor, destructor, copy constructor, move constructor, copy assignment and move assignment. 
When and how this rule applies. What are, and how to have, defaulted and deleted class functions. What is Return Value Optimization (RVO) and what kind of tricks is automagically doing for you.