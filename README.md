# installer
Installers for any software across different platforms

* [sysbench](https://github.com/akopytov/sysbench)
* [dbdeployer](https://github.com/akopytov/sysbench)
* [readyset](https://readyset.io/docs/get-started/install-rs)
* [pmm](https://github.com/percona/pmm) Percona Monitoring and Management
* [pgloader](https://pgloader.readthedocs.io/)


# Run default recommendation installation
```
cd <product>
./run
```

# Get help on all steps available
```
./run help


  Usage: ./run action [action action ...]

  Actions include:

	- install
	- version
	- configure
	- start
	- cleanup

	- stop
	- remove
	- purge
	- help

```

# Perform script debugging
```
TRACE=y ./run
```
