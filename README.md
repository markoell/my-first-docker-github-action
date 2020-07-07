![.github/workflows/main.yml](https://github.com/markoell/my-first-docker-github-action/workflows/.github/workflows/main.yml/badge.svg)

# my-first-docker-github-action

This action prints "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
