# meat-runner

Home for Github Actions runner images based on the [actions/runner](https://github.com/actions/runner) image.

## Packages

### To request a package to be added to the image

1. Open an issue using the [`Request a New Package`](https://github.com/synapsestudios/meat-runner/issues/new?assignees=&labels=new+package&projects=&template=request-a-new-package.md&title=%5BNew+Package%5D+-+package_name) template.
2. Fill out the template with the requested package information.
3. Submit the issue.

#### List of packages installed in the image

| Package        | Version    | Configuration           |
| -------------- | ---------- | ----------------------- |
| curl           | latest     |                         |
| unzip          | latest     |                         |
| zip            | latest     |                         |
| jq             | latest     |                         |
| openjdk        | 17         |                         |
| gradle         | latest     |                         |
| npm            | 10.5.2     |                         |
| node           | 18, 20, 21 | defaults to lts         |
| nvm            | 0.39.7     |                         |
| apt-fast       | latest     | --no-install-recommends |
| docker         | latest     |                         |
| docker-compose | v2         |                         |

#### List of global NPM packages installed in the image

| Package | Version  | Configuration |
| ------- | -------- | ------------- |
| yarn    | v1.22.29 |               |
