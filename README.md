* `python3 -m venv _venv`
* `source _venv/bin/activate`
* `pip install .`
* error... -> https://github.com/pypa/pip/issues/7946

```
Processing /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug
  Installing build dependencies ... done
  Getting requirements to build wheel ... error
  ERROR: Command errored out with exit status 1:
   command: /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/bin/python3 /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/share/python-wheels/pep517-0.7.0-py2.py3-none-any.whl/pep517/_in_process.py get_requires_for_build_wheel /tmp/tmpjl9p5766
       cwd: /tmp/pip-req-build-k6iv_ei5
  Complete output (1 lines):
  /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/bin/python3: can't find '__main__' module in '/home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/share/python-wheels/pep517-0.7.0-py2.py3-none-any.whl/pep517/_in_process.py'
  ----------------------------------------
ERROR: Command errored out with exit status 1: /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/bin/python3 /home/lazka/Desktop/dsfsf/pip-pyproject-bug/pip-pyproject-bug/_venv/share/python-wheels/pep517-0.7.0-py2.py3-none-any.whl/pep517/_in_process.py get_requires_for_build_wheel /tmp/tmpjl9p5766 Check the logs for full command output.
```
