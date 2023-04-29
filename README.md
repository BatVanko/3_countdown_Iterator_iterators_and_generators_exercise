# 3_countdown_Iterator_iterators_and_generators_exercise
Create a class called countdown_iterator. Upon initialization, it should receive a count. Implement the iterator to return each countdown number (from count to 0 inclusive), separated by a single space.

Test Code
iterator = countdown_iterator(10)
for item in iterator:
    print(item, end=" ")


Output

10 9 8 7 6 5 4 3 2 1 0

Test Code

iterator = countdown_iterator(0)
for item in iterator:
    print(item, end=" ")

Output

0
