---
layout: default
title:  Solution 1 - Declare an Array
parent: Rust for Beginners
nav_order: 22
---

# Solution: 

```
fn test() {
    // define an array
    let arr:[i32;6] = [0, 2, 4, 6, 8, 10]; 
    // print the values of array
    print!("{},{},{},{},{},{}",arr[0], arr[1], arr[2], arr[3], arr[4], arr[5]);
}


```
output:- 

```
0,2,4,6,8,10

```

# Explanation 
- On line 3, an array arr of type i32 and size 6 is defined with values 0, 2, 4, 6, 8, 10.
- On line 5, print the value of the arr elements using the subscript notation `[]` using placeholder `{}` for each value within the `print!()` macro.

