---
title: How I installed jupyter notebook on repl.it
date: 2019-06-15 23:25:09 +0000
key: 20190615b
tags: jupyter
---

## How I installed jupyter notebook on repl.it

[The Jupyter Notebook App](https://jupyter.org/) is a server-client application that allows editing and running notebook documents via a web browser.

[repl.it](https://repl.it/) is an online compiler used for compiling and running codes of various languages like Python , javascript etc.

I only used the next file:

*main.py*

```python
import jupyter
import request
import os 
os.system('/home/runner/.local/bin/jupyter notebook --port=3000 --ip=0.0.0.0 --no-browser')
```

Remember add the token part to the url page

For example:

```
https://jupyter--vispacem.repl.co/?token=febef11baf5e99973a875f550d6c8208e7f0b26347199d69
```
