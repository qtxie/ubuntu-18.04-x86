# ubuntu-18.04-x86

GitHub Action for running x86 (32-bit) code

I created this to help test rubicon-java for the BeeWare project.

I intend to provide no support for this except as part of my contributions
to the BeeWare open source project.

Feel free to use it, but if you want to depend on it, consider forking
your own copy, because I may make breaking changes.

## Features & development

See the [embedded self-referential GitHub
Action](./.github/actions/push.yaml) demonstrating that we can (1)
execute x86 code and (2) read output from that code. Reading output is
easy because x86 code and default (x86_64) code share the same current
working directory.
