# Friend-Class
When a class is declared a friend class, all the member functions of the friend class become friend functions.
Since ClassB is a friend class, we can access all members of ClassA from inside ClassB.
However, we cannot access members of ClassB from inside ClassA. It is because friend relation in C++ is only granted, not taken.
