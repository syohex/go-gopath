# go-gopath

Will guess GOPATH using gb and projectile.

## Setup

```lisp
(require 'go-gopath)
(define-key go-mode-map (kbd "C-c C-e") #'go-gopath-set-gopath)
```
