# meat-runner
Home for Github Actions runner images based on `ghcr.io/actions/actions-runner` from https://github.com/actions/runner

# Packages

### List of packages installed in the image

| Package  | Version    | Configuration           |
|----------|------------|-------------------------|
| curl     | latest     |                         |
| unzip    | latest     |                         |
| zip      | latest     |                         |
| jq       | latest     |                         |
| openjdk  | 17         |                         |
| gradle   | latest     |                         |
| npm      | 10.5.2     |                         |
| node     | 18, 20, 21 | defaults to lts         |
| nvm      | 0.39.7     |                         |
| apt-fast | latest     | --no-install-recommends |