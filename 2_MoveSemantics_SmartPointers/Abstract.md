The second talk in the series addresses one major update in the renewed C++ memory model: ownership.
Before the advent of C++11 the concepts of resource ownership and management were not possible to be expressed in a simple and elegant way through code using only "Raw Pointers". 
Thanks to the introduction of so called "Smart Pointers" classes we now have powerful tools to face this issue.
We will see in action the three main actors of this game provided by STL: std::unique_ptr, std::shared_ptr and std::weak_ptr. 
Will be also reviewed the concepts of lvalue and rvalue in order to state and analyse the idea behind "Move Semantics".
Move Semantics is another great language feature which brings big performance benefits avoiding useless copies and enforcing a proper resource management in a more expressive and safer way. 