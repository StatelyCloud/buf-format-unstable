Repro steps:

1. `buf format -w && cat format_repro.proto`
2. goto 1

You will see that each time the command is run, the formatted output changes back and forth.