# [stuck] python version of npx envinfo

i tried to make a python verison of envinfo but failed with the packaging.

```
'report-env' executable script not found in package 'report-env'.
Available executable scripts:
```

## Distributing

- failed to use poetry to bundle - got `/Users/swyx/Desktop/Work/env-info/report_env does not contain any element` error and couldnt fix
- `python3 -m build`
- `python3 -m twine upload dist/*`


## thanks

- https://packaging.python.org/en/latest/tutorials/packaging-projects/
- https://github.com/cs01/pycowsay
