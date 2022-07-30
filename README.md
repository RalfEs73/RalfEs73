# Hello there, I'm Ralf 👋
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/RalfEs/)

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