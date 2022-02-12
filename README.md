# Solving One Pizza Practice Problem For Google Hashcode 2022 Using Java
![](img/image_one_pizza_pb.png)


# My Approach To This Problem
I used the first agorithm to solve the inputs (a_an_example.in | b_basic.in)

The algorithm is:

1. Taking all the ingredients from the customer (liked ingredients and disliked ingredients)
2. Removing any ingredient from the chosen ingredient list which is inside the disliked list


I solved the rest of the inputs (c_coarse.in | d_difficult.in | e_elaborate.in) by using the second algorithm

The algorithm is:

1. Reordering the customer's list according to the disliked ingredient list (ascending order)
2. If two disliked ingredient lists from the customer have the same size, we will take the customer with the shortest liked ingredient list.
3. Taking all the ingredients from the customer's liked list while there are no disliked ingredients inside the taken list
