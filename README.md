# Triplets task using numpy package
---
### Write a function triplets that takes a number n as argument and returns n tuples of triplets from the arrays which has been selected randomly. And sum of first two elements of the triplet equals the third element using numbers below n. Please note that (a, b, c) and (b, a, c) represent same triplet.
---

Starting with first lines of code, **num** and **all_triplets** are counter of tuples in list and storage for storing tuples in, respectively. As you imagine, **while** loop is for not exceeding required number of tuples. Let's go on other steps in the form of list one by one too.

---
![triplets](https://user-images.githubusercontent.com/113797630/192101439-79f8cf24-25e7-4d46-969d-77f39f000c4a.png)
---
* **np.random.randint** generates random arrays with the size of 3.
* **if** condition checks the condition which is given above. (_sum of first two elements of the triplet equals the third element using numbers below n_)
* Second **if** is for checking number of tuples in 'main storage' to give allowance of need of detecting duplicates. And adds appropriate tuples to 'main storage'.
* Else condition works when number of tuples in 'main storage' is more than 1 where need of checking duplicates or replaced of first and second elements in tuples is in demand. Then the tuples are added appended to **all_triplets** list according to given condition.
* Finally, when required number of appropriate tuples are selected, those are returned as a final result.
