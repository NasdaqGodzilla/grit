# grit

grit: Generate Resource Identity Token

Generate message-id for input message. 为字符串生成独立的特异的msgid

A copy of Chromium open source project. 来自Chromium extern tools

## Getting started

1. Enter python shell and call:

```
from grit.extern.tclib import GenerateMessageId
GenerateMessageId("Message")
```

2. Example geneating msgid

```
$ python
Python 2.7.17 (default, Nov  7 2019, 10:07:09)
>>> from grit.extern.tclib import GenerateMessageId
>>> GenerateMessageId("Manage people")
'8400146488506985033'
```

