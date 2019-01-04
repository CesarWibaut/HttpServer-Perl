# Comanche, an HTTP Server in perl

Par BEHAGUE Quentin, WIBAUT César

## Commands

Start the server

`>$ comanche start`

Stop the server

`>$ comanche stop`

Get server status

`>$ comanche status`

## Config

The server configuration must be in the comanche.conf file

The config file must contains :

* the port used by the server (Number)
* the max number of client (> 0)
* the error file (must exist)
* the directory index file
* the logfile path
* the projection route for files and scripts

It also have to be in the same directory as the server script

