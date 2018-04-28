# run it
run this
```
pip install jaeger-client
pip install pyinstaller

#if command not find use pyinstaller,open a new terminal and try again
pyinstaller -F app.py
#
./dist/app
```
your will see this error
```
(jaegertracing-python-demo) ➜  jaegertracing-python-demo git:(master) ✗ ./dist/app
Traceback (most recent call last):
  File "app.py", line 4, in <module>
    from jaeger_client import Config
  File "/Users/zhuzhengguang/.local/share/virtualenvs/jaegertracing-python-demo/lib/python3.6/site-packages/PyInstaller/loader/pyimod03_importers.py", line 631, in exec_module
    exec(bytecode, module.__dict__)
  File "jaeger_client/__init__.py", line 27, in <module>
  File "/Users/zhuzhengguang/.local/share/virtualenvs/jaegertracing-python-demo/lib/python3.6/site-packages/PyInstaller/loader/pyimod03_importers.py", line 631, in exec_module
    exec(bytecode, module.__dict__)
  File "jaeger_client/config.py", line 25, in <module>
  File "/Users/zhuzhengguang/.local/share/virtualenvs/jaegertracing-python-demo/lib/python3.6/site-packages/PyInstaller/loader/pyimod03_importers.py", line 631, in exec_module
    exec(bytecode, module.__dict__)
  File "jaeger_client/reporter.py", line 32, in <module>
  File "/Users/zhuzhengguang/.local/share/virtualenvs/jaegertracing-python-demo/lib/python3.6/site-packages/PyInstaller/loader/pyimod03_importers.py", line 631, in exec_module
    exec(bytecode, module.__dict__)
  File "jaeger_client/thrift_gen/agent/Agent.py", line 12, in <module>
  File "/Users/zhuzhengguang/.local/share/virtualenvs/jaegertracing-python-demo/lib/python3.6/site-packages/PyInstaller/loader/pyimod03_importers.py", line 631, in exec_module
    exec(bytecode, module.__dict__)
  File "jaeger_client/thrift_gen/agent/ttypes.py", line 11, in <module>
ModuleNotFoundError: No module named 'jaeger'
[21447] Failed to execute script app
(jaegertracing-python-demo) ➜  jaegertr
```


