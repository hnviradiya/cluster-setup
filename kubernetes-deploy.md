### Execute following command on windows with Git BASH:

```
base=https://github.com/docker/machine/releases/download/v0.16.0 \
  && mkdir -p "$HOME/bin" \
  && curl -L $base/docker-machine-Windows-x86_64.exe > "$HOME/bin/docker-machine.exe" \
  && chmod +x "$HOME/bin/docker-machine.exe"
```

Add above added exe to environment Path variable
