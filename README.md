See the header comments in each file for full documentation. The
recommended usage is in java-mode-plus.el.

To install drop these in your load-path somewhere and require them
(after enabling ido-mode, if you use ido-mode),

  (require 'java-mode-plus)
  (require 'java-docs)

**NOTICE**: The java-docs portion of this package is depreciated. It
has been replaced by the more powerful
[javadoc-lookup](https://github.com/skeeto/javadoc-lookup). Use that
instead.

To use java-docs you'll need to tell it where to find some
documentation. For example,

  (java-docs "/usr/share/doc/openjdk-6-jdk/api")

Then use C-h j to look something up.

The snippets directory contains some YASnippets that hook into
java-docs class completing reads.