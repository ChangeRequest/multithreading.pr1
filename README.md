Multithreading Practice Task 1
===============

Readers-Writers
---------------

Create class **Storage**, which contains array with 10 000 000 integers.
Class should contain two methods: 
* Calculate sum of integers
* Generate and fill array with new 10 000 000 integers 

Create class **Reader**, that should calculate sum of integers of the **Storage** and print it once in 0-3 seconds.

Create class **Writer**, that fill **Storage** with new integers once in 0-5 seconds.

Create 4 **Readers** that simultaneously prints sum.

Create 2 **Writers** that simultaneously fill **Storage** with new integers.

There should be following restrictions:
* **0-4** readers and **0** writers can work with storage at the one moment of time (all writers should wait until readers will finish work)
* **0** readers and the only **1** writer can work with storage at the one moment of time (all readers and other writers should wait until this writer will finish work)

