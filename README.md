## Simpu

> Manage generic and specialized commands for different projects in one place using makefiles

## Getting Started

Ensure to have the [make utility](https://www.gnu.org/software/make/) installed on your machine. Execute the below command to verify installation

```bash

$ make --version

```

Clone this repository
```bash

$ git clone https://github.com/kynorg/simpu.git

```

Add the absolute path to the bin folder to your `PATH` environment variable
```bash

export PATH="/absolute/path/to/simpu/bin:$PATH"

```

Create a package by adding a folder to the packages folder, giving it the prefered name you would want for a package and add a `Makefile` into the folder, so you can start defining your custom commands. See the [root package](packages/root) for example

Note that every public and private command defined in the root package is made available to all other packages

## Documentation

#### See the list of available commands through the root package

```bash

$ simpu root

# OR

$ simpu root help

```

#### Managing private packages

Documentation for this section is coming soon ...

#### Managing private commands for public packages

Documentation for this section is coming soon ...

## Contributions

Check out the set of open issues on this repository and raise a pull request using the available [pull request template](.github/pull_request_template.md) to make changes to the simpu binary and workflow or add generic packages using the [root package](packages/root) as an example

## LICENSE

[MIT](LICENSE)
