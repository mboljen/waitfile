# waitfile

Bash script for waiting a certain amount of time for a file to be created.

## Installation

Use the following command to install this software:

```bash
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to succesfully complete the installation, you need to have write permissions for the installation location.

## Usage

The following command will wait for the file `TESTFILE` to be created:

```bash
$ waitfile [-t secs] [-q] TESTFILE
```

### Options

+ `-t` Set the timeout interval in seconds (default: `30`)

+ `-q` Be quiet


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
