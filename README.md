# act custom image

**act_base** is a custom runner for the [act project](https://github.com/nektos/act). This image contain **Node**, **npm**, **yarn**, **docker** and **docker-compose**. The size is about 1.61GB.

> This image is an hard fork https://github.com/swuecho/act_base whose image is no longer available on the docker hub.

## Download the image

```
docker pull lucasalt/act_base:latest
```

## Run a job with the custom runner

```
act -j <name-of-the-job> -P ubuntu-latest=lucasalt/act_base:latest
```

> PS: `ubuntu-latest` is the value of `run_on` in your `workflow yml`. It is possible to swith `ubuntu-latest` with another image name.

## 🤝 Contributing

Before contributing to this project, make sure you have read the [contribution guidelines](https://github.com/start-again/start-abot/blob/main/CONTRIBUTING.md)!

1. Fork it (https://github.com/start-again/start-abot/fork)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## 📝 License

This project is open source and available under the [unlicense](https://github.com/start-again/start-abot/blob/master/LICENSE) license.
