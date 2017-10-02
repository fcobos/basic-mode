# basic-mode

Package basic-mode provides a major mode for editing BASIC code in GNU Emacs.


### Installation

The easiest way to install basic-mode is from [MELPA](https://melpa.org).

To install manually, place basic-mode.el in your load-path, and add the
following lines of code to your init file:

    (autoload 'basic-mode "basic-mode" "Major mode for editing BASIC code." t)
    (add-to-list 'auto-mode-alist '("\\.bas\\'" . basic-mode))


### Configuration

You can customize the indentation of code blocks, see variable
basic-indent-offset. The default value is 4. You can also customize the number
of columns to use for line numbers, see variable basic-line-number-cols. The
default value is 0, which means not using line numbers at all.