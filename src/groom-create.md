# `groom-create`

`groom-create` allows to create golang projects according to a given template.

## Templates
Currently 3 templates are provided

- `lib`
    A library profile, useful for creating golang libraries.
- `cmd`
    A `cmd` profile, useful for creating command-line applications.
- `simple`
    The default profile, useful while learning how golang works. For very simple projects.

## Makefiles

We use `make` as a build system and this requires the `make` binary to be installed on your system.
Makefiles are universally understood and easy to extend.

You are encouraged to modify or add your custom directives to the Makefile.

We provide these make directives by default.
- `help`
    Provides help for all the other subcommands. 
    ```sh
    make help
    ```
- `build`
    Compile the project.
    ```sh
    make build
    ```
- `run`
    Runs the project.
    ```sh
    make run
    ```
- `format`
    Format the project using `gofmt`.Integrations for other tools are possible, see [here]().
    ```sh
    make format
    ```
- `test`
    Test the project files. Uses golang's built-in testing library.
    ```sh
    make test
    ```




