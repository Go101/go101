
# Go Details & Tips 101 Update History

### v1.24.a (2024/Dec/16)

* "

### v1.23.a (2024/Oct/16)

* "Standard and User Packages Related" chapter:
  * add "The `N` function in the Go 1.22 introduced `math/rand/v2` standard package provides much convenience in some scenarios"

### v1.22.a (2024/Mar/18)

* "Syntax and Semantics Related" chapter:
  * Go 1.22 introduced `for range Integer` loops and changed the semantics of for-loop code blocks.Some related contents are added.

### v1.21.b 

* "Standard and User Packages Related" chapter:
  * due to https://github.com/golang/go/issues/57411, removed the "How to try to run a custom `init` function as early as possible?" tip.

### v1.21.a (2023/OCT/11)

* "Syntax and Semantics Related" chapter:
  * mentions the evaluation results of `unsafe.Alignof`, `unsafe.Offsetof` and `unsafe.Sizeof` function calls are not constants.
* "Compiler and Runtime Related" chapter:
  * added a "How to guarantee a struct field to be always 8-byte aligned" tip.

### v1.20.a (2023/Feb/01)

* "Syntax and Semantics Related" chapter:
  * mentions Go 1.21 will add a `clear` built-in function, which can removed map entries with NaN keys.
  * in the "Normalization of method selectors" section, mentions a de-virtualize bug has been fixed since Go toolchain 1.20.
  * in the "Some expression evaluation orders are unspecified in Go" section, mentions an evaluation order difference
    between normal variable declaration and redeclaration has been removed since Go toolchain 1.20.

### v1.19.e (2022/Nov/15)

* add a new detail "The official Go compiler checks some popential bugs caused by the `:=` trap but not all of them" in "Syntax and Semantics Related" chapter.

### v1.17 (2021/Dec/22)

* published
