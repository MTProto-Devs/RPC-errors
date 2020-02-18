# RPC errors

Telegram's documentation page on [Error handling] does not contain an
exhaustive list of all errors (in fact, it seems nobody knows!). This
repository contains a file called `errors.csv` with the known errors,
code and description.

If an error has a capture, it will be within curly braces, for example
in `{seconds}` for `FLOOD_WAIT_X`, indicating what the `_X` represents.

You can contribute by expanding the list, improving the description,
or testing for the validity of the errors.

The file `methods.csv` contains data about which methods can throw
which errors.

Please keep the lists sorted when contributing.

[Error handling]: https://core.telegram.org/api/errors
