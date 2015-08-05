## Note to ourselves

One of our first tasks will be to parse the text file from the UN into something more intelligible.

Our parsing code will live in the `data-raw` directory - the code in that directory will be put into `data`, to be used as a part of the package data. 

## Git large-file support

Here's what you would need to do to get this on your computer:

1. download the git large-file support extension: https://git-lfs.github.com

2. using the command line of your Mac (assuming this is your computer of choice), navigate to the directory created by this download in your `Downloads` directory

3. type `./install.sh` into your command line (there should be a `install.sh` file in your current directory)

4. you may (or may not) be encouraged to type in some git configuration commands

When you clone or pull from `ijlyttle/wsd2015`, it should take a little longer as the 135 MB file downloads. Other than that, it should be transparent.

As long as you are not adding any large files, there is nothing more you will need to fiddle with. If you do add a large file, you use `git lfs track` from the command line.


