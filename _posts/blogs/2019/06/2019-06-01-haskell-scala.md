---
permalink: /:year/:month/:day/:title.html
title: "How to write Haskell-like functions in Scala"
hidden: true
comments: false
categories:
  - Blogs
tags:
  - Haskell
  - Scala
  - Functional Programming
---

Scala:
```scala
val f: Int => Int => Int = x => y => 
  x + 2 * y

println(f(3)(4))
```

Haskell:
```haskell
f :: Int -> Int -> Int
f x y = x + 2 * y

main :: IO ()
main = print(f 3 4)
```
{: style="text-align: justify;"}