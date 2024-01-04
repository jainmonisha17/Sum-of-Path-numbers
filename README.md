# Sum-of-Path-numbers
Given a binary tree where each node can only have a digit (0-9) value, each root-to-leaf path will represent a number. Find the total sum of all the numbers represented by all paths.

                                                                            1

                                                                      0            1

                                                                1           6                5


                                                    Sum of Path Nums: 332

Time Complexity
The time complexity of the above algorithm is O(N), where ‘N’ is the total number of nodes in the tree. This is because we traverse each node once.

Space Complexity
The space complexity of the above algorithm will be O(N) in the worst case. This space will be used to store the recursion stack. The worst case will happen when the given tree is a linked list (i.e., every node has only one child).
