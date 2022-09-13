# grit

提供tclib，对字符串生成msgid。来自chromium extern tools

## Getting started

1. Enter python shell;

```
$ python
>>>
```

2. Example geneating msgid

```
$ python
Python 2.7.17 (default, Nov  7 2019, 10:07:09)
[GCC 7.4.0] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> from grit.extern.tclib import GenerateMessageId
>>> GenerateMessageId("Manage people")
'8400146488506985033'
```

