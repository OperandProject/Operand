Build instructions
===================

See readme-qt.rst for instructions on building Operand QT, the
graphical user interface.

All of the commands should be executed in Terminal.app

```
sudo port install boost db48 openssl miniupnpc qrencode

cd operand/src
make -f makefile.osx
```

```
./operandd --help  # for a list of command-line options.

./operandd -daemon # to start the operand daemon.

./operandd help # When the daemon is running, to get a list of RPC commands
```
