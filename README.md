## 🚀 Git Commit con Timestamp

Cuando hagas un commit en **Git** y quieras incluir un **timestamp automático**, puedes usar el siguiente comando en **PowerShell**:

```powershell
git commit -m "$(Get-Date -Format 'yyyy-MM-dd HH:mm:ss')"
