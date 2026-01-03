## Semgrep
To install:
```
sudo snap install semgrep 
```

Semgrep has a variety of rulesets that can be run, all focused on different vulnerabilities and/or languages.
Here's how to run a default ruleset for Ruby and how to save the json result to /reports:
```
semgrep scan --config p/ruby --json --output reports/semgrep.json
```

## Gitleaks
To install:
```
sudo apt install gitleaks 
```

To run and save the json result to /reports:
```
gitleaks detect --source . --report-format json --report-path reports/gitleaks.json
```



Test secret:
1eae0f2519e8131371e9c85ad9de83912ba3786edd020ce1333c010d0a025503166d74236e5c57b261c2f4b672feae8fdfb206c75a2b51f312887f177c3dda80