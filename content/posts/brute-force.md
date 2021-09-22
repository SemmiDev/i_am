---
author:
  name: "Sammi Aldhi Yanto"
description: Algoritma - 1 - Brute Force
date: 2021-09-22
linktitle: Algoritma - 1 - Brute Force
type:
- post
- posts
title: Algoritma - 1 - Brute Force
weight: 10
series:
- Java
- Algo
tags:
- Java
- Algo
categories:
- Java
- Algo
---

```go
func findMaxNumber(nums []int) int {
    max := nums[0]
    length := len(nums)

    for i := 1; i < length; i++ {
        if nums[i] > max {
            max = nums[i]
        }
    }
    return max
}
```

```go
func sequentialSearch(nums []int, x int) int {
    length := len(nums)

    for i := 0; i < length; i++ {
        if nums[i] == x {
            return i
        }
    }
    return -1
}
```

```go
func squaring(a,n int) int {
    result := 1

    for i := 1; i <= n; i++ {
        result *= a
    }

    return result
}
```

```go
func factorial(n int) int {
    total := 1

    for i := 1; i <= n; i++ {
        total *= i
    }
    return total
}
```

```go
func multiplyTwoMatrices(a [3][3]int, b [3][3]int) [3][3] int{
    rowLength := len(a)
    columnLength := len(a[0])

    var c [len(a)][len(a[0])]int

    for i := 0; i < rowLength; i++ {
        for j := 0; j < columnLength; j++ {
            c[i][j] = 0
            for k := 0; k < rowLength; k++ {
                c[i][j] += a[i][j] * b[k][j]
            }
        }
    }

    return c
}
```

```go
func isPrime(n int) bool {
    if n < 2 {
        return false
    }
    upperLimitFloat := int(math.Sqrt(float64(n)))

    for i := 2; i < upperLimitFloat; i++ {
        if n % i == 0 {
            return false
        }
    }
    return true
}
```

```go
func selectionSort(nums []int) []int {
    var minIndex int
    var temp int
    size := len(nums)

    for i := 0; i < size-1; i++ {
        minIndex = i
        for j := i+1; j < size; j++ {
            if nums[j] < nums[minIndex]{
                minIndex = j
            }
        }

        temp = nums[i]
        nums[i] = nums[minIndex]
        nums[minIndex] = temp
    }

    return nums
}
```

```go
func bubbleSort(nums []int) []int {
    for i := 0; i < len(nums); i++ {
        for j := 0; j < len(nums)-i-1; j++ {
            if nums[j] > nums[j+1] {
                nums[j], nums[j+1] = nums[j+1], nums[j]
            }
        }
    }
    return nums
}
```

`string matching/pattern matching`\
`closest pairs problem`\
`...`\
`...`\
`...`