# Regripper

## Build
```
$ podman build . -t regripper
```

## Usage
```bash
echo "alias rip='podman run --privileged --rm -v .:/data:ro regripper'" >> .bashrc
```

