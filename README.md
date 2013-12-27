# JAILCOPY HELPER

## About Jailcopy
// TODO write anything about that bash script

## Installation & Documentation

### Installation

On Linux and BSD OS:
```bash
sudo sh -c 'wget https://raw.github.com/gudron/jailcopy/master/jailcopy -P /usr/local/bin && chmod +x /usr/local/bin/jailcopy'
```

### Documentation
<pre>
USAGE: ./jailcopy -n <BINARY_NAME> -j <JAIL_ROOT>
Options:
	-n <BINARY_NAME>	Binary application name.	 Example: bash, sh, rsync
	-j <JAIL_ROOT>		Jailroot path.				 Example: /home/virtualhosts/example.dev	
</pre>