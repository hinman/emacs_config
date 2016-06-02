# Org Emacs Config
My ongoing Emacs configuration saga.

Put this in your `~/.emacs.d/init.el` assuming that you cloned the repo to
`~/src/emacs_config`

    (org-babel-load-file
    (expand-file-name "config.org"
                      "~/src/emacs_config"))
