# Raspberry Pi OpenCV

## Introduction
This repository let you install easily OpenCv on *Raspberry Pi 3* and *Raspberry Pi 4*. This only use 3 bash script you need to launch on your raspberry pi

## Installation
First I advice you to update and upgrade the installed repository already installed on your raspberry pi with the following command :

```bash
$ sudo apt update && sudo apt upgrade
```

Then you are able to clone this repository. Open a terminal in the folder you want and clon this repository with this command :

```bash
$ git clone https://www.github.com/Teusner/RapsberryPi_OpenCv
```

Now you need to allow the execution rights on the bash scripts with this command :

```bash
$ cd ./RaspberryPi_OpenCv
$ chmod +x *.sh
```

And you are able to launch each scripts in this order :

```bash
$ ./download-opencv.sh
$ ./install-deps.sh
$ ./build-opencv.sh
```

Now you could test your installation with the included python script :

```bash
$ wget "https://upload.wikimedia.org/wikipedia/en/7/7d/Lenna_%28test_image%29.png" -O lenna.jpg
$ python2 test.py lenna.jpg
$ python3 test.py lenna.jpg
```

## Built from

* [This gist](https://gist.github.com/willprice/abe456f5f74aa95d7e0bb81d5a710b60) - An interresting gist made by [willprice](https://gist.github.com/willprice)

## Authors

* **Brateau Quentin** - *Initial work* - [Teusner](https://github.com/Teusner) :sunglasses:

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details