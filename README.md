# Cryptosoft-Nutrition-Label 🚀

<a href="https://github.com/github-developer/javascript-action/actions"><img alt="javscript-action status" src="https://github.com/github-developer/javascript-action/actions/workflows/test.yml/badge.svg"></a>

## Development

#### 1. Update your action metadata in `action.yml`

[`action.yml`](action.yml) defines the inputs and output for your action.

Update the action.yml with your name, description, inputs and outputs for your action.

See the [documentation](https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions).

#### 2. Write your action code in `lib`


#### 3. Test your action in `tests`

[Jest](https://jestjs.io/) and [Nock](https://github.com/nock/nock) are included as suggestions for test and mocking frameworks.

A sample [Unit Test workflow](.github/workflows/test.yml) is provided which runs on every pull request and push to the `main` branch.

#### 4. Automate releases with GitHub Actions

The entrypoint to your action is defined by `runs.using` in `action.yml`.


## License

[MIT](LICENSE.md)

## Contributing

Pull requests are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for more.
