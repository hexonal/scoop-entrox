# Entrox Scoop Bucket

This repository is managed by the Entrox release workflow.

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
scoop bucket add entrox https://github.com/hexonal/scoop-entrox
scoop install entrox
```
