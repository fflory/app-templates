```
cd dash-data-app
```

```
python3.11 -m venv .venv
```

```
pip install -r requirements.txt
```

```
databricks apps create ffdaou
```

```
databricks sync --watch . /Workspace/Users/felix.flory@databricks.com/ffdaou
```

```
databricks apps deploy ffdaou --source-code-path /Workspace/Users/felix.flory@databricks.com/ffdaou
```

```
databricks workspace delete --recursive /Workspace/Users/felix.flory@databricks.com/ffdaou
```