---
layout: entry
title:  'root'
shortdef : 'root'
---

The `root` grammatical relation points to the root of the sentence. A
fake node `ROOT` is used as the governor. The `ROOT` node is indexed
with 0, since the indexing of real words in the sentence starts at 1.

~~~ sdparse
ROOT Minä pidän oluesta .
root(ROOT, pidän)
~~~
