Install [yasnippet](https://github.com/capitaomorte/yasnippet).

Then:

```
git clone http://github.com/statonjr/clojure-snippets ~/.emacs.d/snippets/clojure-mode
```

Or whatever location you prefer. Then In your `.emacs` you should have
something like the following

```elisp
(when (require 'yasnippet nil 'noerror)
  (progn
    (yas/load-directory "~/.emacs.d/snippets")))
```
