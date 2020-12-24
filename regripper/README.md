# Regripper

## Build
```
$ podman build . -t regripper
```

## Usage
```bash
$ # alias for easy usage
$ echo "alias rip='podman run --privileged --rm -v .:/data:ro regripper'" >> .bashrc
```

