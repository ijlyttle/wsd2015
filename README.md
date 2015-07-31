## Note to ourselves

One of our first tasks will be to parse the text file from the UN into something more intelligible.

Our parsing code will live in the `data-raw` directory - the code in that directory will be put into `data`, to be used as a part of the package data. Part of this parsing code will download the source data-file if it does not exist, and then we will put a reference to that file into `.gitignore` so it does not bog down github.
