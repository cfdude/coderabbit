# coderabbit

Central [CodeRabbit](https://coderabbit.ai) configuration for `cfdude` repositories.

CodeRabbit applies [`.coderabbit.yaml`](.coderabbit.yaml) to any repository that has no
`.coderabbit.yaml` of its own ([central configuration](https://docs.coderabbit.ai/configuration/central-configuration)).

To override part of it in one repository, add a `.coderabbit.yaml` there that starts with
`inheritance: true` and sets only what differs. Without that line, the repository's file
replaces this one entirely.
