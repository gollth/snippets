# Snippets
Usefull YAS Snippets for Emacs

## Installation
Clone this repo, e.g. into `~/.spacemacs.d/snippets`

In your Spacemacs config (`SPC f e d`) enter the path to this repo for the autocompletion layer:

```elisp
(auto-completion :variables
                 ;; ... other vars here ...
                 auto-completion-private-snippets-directory "~/.spacemacs.d/snippets")
```

After that you might have to do `M-x yas-reload-all RET`

## Usage
To create new snippet use `M-x yas-new-snippet RET` and follow the [documentation](http://joaotavora.github.io/yasnippet/snippet-development.html#org5e87ae3) on how to write snippets.

To insert a snippet use `SPC i s` which will prompt you with a helm query with all snippets for the current major mode.
