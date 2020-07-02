# cn-buildpack-wkhtmltopdf

A Cloud Native Buildpack for [wkhtmltopdf](https://wkhtmltopdf.org/).

This buildpack is mainly adapted from [heroku-buildpack-wkhtmltopdf](https://github.com/simplefractal/heroku-buildpack-wkhtmltopdf).

## Usage

1- Clone the repository:

```bash
git clone https://github.com/speedyrails/cn-buildpack-wkhtmltopdf.git
```

2- Add the buildpack to the project:

```bash
pack build myapp --builder heroku/buildpacks:18 --buildpack /path/to/cn-buildpack-wkhtmltopdf --path /path/to/myapp
```

**NOTE:**

- The wkhtmltopdf version installed is 0.12.4_linux-generic-amd64.
- The `wkhtmltopdf` binaries will be available from the `PATH` environment variable.
