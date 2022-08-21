# go-avltree
Golang implementation of an [AVL Tree](https://en.wikipedia.org/wiki/AVL_tree). An AVL tree is a [self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree).

Each node in the tree has a key and a value, which the key implement [`Ordered`](https://github.com/golang/exp/blob/master/constraints/constraints.go#L48). It supports the following methods: Add, Remove, Update, Search, DisplayInOrder. When adding a key that exists its value is updated with the new one.

## Installation

    go get github.com/weaming/go-avltree

## Example usage

See [exmaple/main.go](example/main.go)

## Notes

This code has not been thoroughly tested and is not production-ready; only basic error handling, no testing coverage, no profiling or code analysis.
