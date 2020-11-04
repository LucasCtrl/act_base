# act custom image

The size is about 1.61GB. It's could be made smaller.

### Download the image

```
docker pull lucasalt/act_base:latest
```

### Run a job with the custom runner

```
act -P ubuntu-latest=lucasalt/act_base
```

PS: ubuntu-latest is the value of run_on in your workflow yml.
   It is possible to swith `ubuntu-latest` with other image name.

