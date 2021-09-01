
```
python3 example.py
```
```console
Traceback (most recent call last):
  File "/example.py", line 1, in <module>
    from mymodule.client import Client
  File "/mymodule/client.py", line 1, in <module>
    from mymodule.site import Site
  File "/mymodule/site.py", line 1, in <module>
    from mymodule.client import Client
ImportError: cannot import name 'Client' from partially initialized module 'mymodule.client' (most likely due to a circular import) (/mymodule/client.py)
```
