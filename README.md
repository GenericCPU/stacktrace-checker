# stacktrace-checker
Simple command-line stacktrace checker to help debug faster

# usage
```
Usage: checkout [OPTION] PATH:LINENUMBER
Options: -l, --length number of lines printed above and below
```

# configuration
Edit the variables at the top of 'stacktrace-checker/checkout' to enable a default working directory or to change the default length

# requirements
linux: grep, ack, sed

# installation
Run the following commands ideally within your home directory
```
git clone https://github.com/GenericCPU/stacktrace-checker.git
sudo chmod +x stacktrace-checker/checkout
```
To access anywhere add the following line to the end of your .bashrc:
`export PATH=$PATH:~/stacktrace-checker`
