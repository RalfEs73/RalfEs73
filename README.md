# Hello there, I'm Ralf 👋
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/RalfEs/)

![Windows](https://img.shields.io/badge/OS-Windows-informational?style=flat&logo=Windows&logoColor=white&color=6aa6f8) ![WindowsTerminal](https://img.shields.io/badge/Shell-Windows%20Terminal-informational?style=flat&logo=Windows-Terminal&logoColor=white&color=6aa6f8)

```bash
#!/bin/bash

set -u
IFS=$'\n\t'

function say_hello() {
  printf "Hello there, I hope you find something useful in my repositories!\\n"
}

if [[ $- != *i* ]]; then
  export USERNAME="RalfEs"
  export ROLE="Technical Architect Microsoft Germany"
  export LANGUAGE="de_DE"
  say_hello
fi
```