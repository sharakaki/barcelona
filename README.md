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
