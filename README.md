# machine-learning

Machine Learning Experiment(s)

The license of the package is MIT.
SPDX-License-Identifier: MIT

For installation, copy the content of `bin/` into your path.
For zsh completion support, copy the content of `zsh/` into your
zsh's `$fpath`.
If you do not have root access, you can add the corresponding directory
with `fpath+=("...")`

Currently, this package contains only the following experiment:

## naivebayes

A perl script to "sort" an email into mboxes, using a
naive Bayes algorithm, assuming a multinomial distribution of
the words in the email.
