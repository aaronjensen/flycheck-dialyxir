# flycheck-dialyxir [![MELPA](https://melpa.org/packages/flycheck-dialyxir-badge.svg)](https://melpa.org/#/flycheck-dialyxir)

[flycheck][] checker for [dialyxir][].

## Installation

You can install this package from [Melpa][]

```
M-x package-install RET flycheck-dialyxir RET
```

## Usage

Ensure that `dialyxir` is installed in your project.

Then, in your `init.el`:

```elisp
(eval-after-load 'flycheck
  '(flycheck-dialyxir-setup))
(add-hook 'elixir-mode-hook 'flycheck-mode)
```

## Thanks

* [@jeremyjh][] for [dialyxir][].
* [@lunaryorn][] for [flycheck][].

[flycheck]: http://www.flycheck.org/
[dialyxir]: https://github.com/jeremyjh/dialyxir
[@jeremyjh]: https://github.com/jeremyjh
[@lunaryorn]: https://github.com/lunaryorn
[Melpa]: http://melpa.milkbox.net/
