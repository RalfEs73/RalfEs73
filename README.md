# Hello there, I'm Ralf 👋
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/RalfEs/)

![Windows](https://img.shields.io/badge/OS-Windows-informational?style=flat&logo=Windows&logoColor=white&color=6aa6f8) ![Windows](https://img.shields.io/badge/Shell-Power%20Shell-informational?style=flat&logo=Windows-Terminal&logoColor=white&color=6aa6f8) ![WindowsTerminal](https://img.shields.io/badge/Shell-Windows%20Terminal-informational?style=flat&logo=Windows-Terminal&logoColor=white&color=6aa6f8)

![AI](https://img.shields.io/badge/AI-Microsoft%20Copilot-informational?style=flat&logoColor=white&color=6aa6f8)

```bash
$ErrorActionPreference = "Stop"

function Say-Hello {
    Write-Host "Hello there, I hope you find something useful in my repositories!"
}

$IsInteractive = $Host.Name -eq "ConsoleHost"

if (-not $IsInteractive) {
    $env:USERNAME = "RalfEs73"
    $env:ROLE     = "Product Manager"
    $env:LANGUAGE = "de_DE"
}

Say-Hello
```
