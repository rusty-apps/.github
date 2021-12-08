# Welcome to the Rusty Apps contribution guide

## Contributing to `Rusty Apps`

:star2: Thank you for taking the time to contribute, all help is very much appreciated and will be recognised :star2:

How to contribute:

1. Fork a repository.
2. Lint your work, you can use the shell `linter below` if you are on \*NIX.
3. Commit your work using `conventional commits format`.
4. Create a pull request against the `master` branch.

## Questions and project support

If you have general questions please do not create issues but comtact on our [DISCORD CHANNEL](https://discord.gg/k8aejMjKjs) instead.

## Linting sources

```shell
docker run --rm -e RUN_LOCAL=true -e IGNORE_GITIGNORED_FILES=true -e IGNORE_GENERATED_FILES=true \
-e VALIDATE_DOCKERFILE=true -e VALIDATE_EDITORCONFIG=true -e VALIDATE_GITHUB_ACTIONS=true \
-e VALIDATE_MARKDOWN=true -e VALIDATE_YAML=true -e VALIDATE_SHELL_SHFMT=true \
-v $PWD:/tmp/lint ghcr.io/github/super-linter:slim-v4
```

## Conventional Commits

If you are not familiar with conventional commits you can read the documentation here: [CONVENTIONAL COMMITS](https://conventionalcommits.org)

## Code of Conduct

Please READ the [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
