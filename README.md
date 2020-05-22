# kubesql
Query kubernetes clusters using SQL

## Usage
Install locally
```bash
pip install -e .
```

Basic Usage
```bash
kubesql "SELECT * from pods WHERE namespace = 'kube-system'"
```

Basic query
```sql
SELECT * from pods WHERE namespace = 'kube-system'
```

Select specific columns

Functions

## TODO
- Select sub columns (e.g. metadata.name)
- Data based WHERE Conditions (other than namespace)
- output type
- Select lists (e.g. spec.pods[].image)
- Select functions
- refactor object oriented


## Credits
https://github.com/mozilla/moz-sql-parser

https://github.com/jgehrcke/python-cmdline-bootstrap