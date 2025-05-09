```
cd dash-hello-world-app
```

```
python3.11 -m venv .venv
```

```
pip install -r requirements.txt
```

```
databricks sync --watch . /Workspace/Users/felix.flory@databricks.com/ffdhw
```

```
databricks apps deploy ffdhw --source-code-path /Workspace/Users/felix.flory@databricks.com/ffdhw
```

```
databricks workspace delete --recursive /Workspace/Users/felix.flory@databricks.com/ffdhw
```