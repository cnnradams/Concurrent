# Concurrent
My goal coming into making this programming language was to concurrently execute everything at the same time. This means the language had to be purely functional, because a mutated value after some thread was called to do something with the previous value would change the thread's value. With a lot of struggle I ended up getting the program to function almost exactly how I wanted it to, however it was extremely slow as a result of my inefficient interpreter, stacking scope, etc. Thus I am probably going to leave it as it is, a great learning experience into interpreters and a challenging but rewarding project. I probably will continue my programming language creation journey with making a modularized parser at which point I might come back to Concurrent and apply it there.

For example functioning program, see find-primes.con
