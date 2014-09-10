iron-setup
====================

A simple script to download and work with the iron packages. You might consider
putting it in your /usr/bin folder so you can use it anywhere.

## Usage

Create a src/iron/packages directory and clone all the iron packages

```
$ ironsetup
```

Checkout a branch across all iron packages

```
$ ironsetup --branch next 
```

Put the iron development packages in your package lookup path

```
$ ironsetup --use
```
