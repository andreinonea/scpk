# scpk

Small shell script that wraps Unix's 'scp' into a nicer way to be used exclusively by Computer Science students at The University of Manchester

## Installing

The debian package can be downloaded from the [releases page](https://github.com/andreinonea/scpk/releases)

Alternatively, you can do a manual install, which is recommended, by following the next instructions:

* Open a terminal
* Download the INSTALL script
```
wget https://raw.githubusercontent.com/andreinonea/scpk/master/INSTALL
```
* Make it executable
```
chmod +x INSTALL
```
* Run INSTALL and enter your password to allow the script access to install the program
```
./INSTALL
```
* You can remove the script afterwards
```
rm INSTALL
```
This way, the program is safely installed with the latest version.

## Usage

###### First run

After installing the program, you have to provide your student ID to be used when connecting to Kilburn machines. Fire up a terminal and start the program with

```
scpk
```

and follow the instructions. Whenever sending data, you should supply the file path in Kilburn first, then the one on your local machine. **Note: Kilburn path implicitly starts from "~/".**

###### Copying from Kilburn

When copying from Kilburn, use the argument 'from' in the command, followed by the source and the destination.

```
scpk from <kilburn path> <local path>
```

###### Copying to Kilburn

When copying to Kilburn, use the argument 'to' in the command, followed by the destination and the source.

```
scpk to <kilburn path> <local path>
```

###### Help

You can use the help command for more information

```
scpk --help
```

or

```
man scpk
```

to open the Unix manual page for the program.

## Version

Latest version is [1.3](https://github.com/andreinonea/scpk/releases/tag/1.3)

Older versions:
- [1.2](https://github.com/andreinonea/scpk/releases/tag/1.2)

## Author

* **Andrei Onea** - *1st Year CS student at the University of Manchester*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

