# unshorten
Url unshortener written in Python

## Usage
- the usage requires the package "requests" to be installed 

### Basic usage requires the short URL you wish to unshorten
```commandline
unshorten https://short.url/
```
output:
```
Provided url -> https://short.url/
Unshortened url -> https://unshortened.url/
```

### Add the "-c" or "--concise" option to obtain a more concise output
```commandline
unshorten -c https://short.url/
```
output:
```
https://unshortened.url/
```

If nor "https://" nor "http://" is found in the url, "https://" is assumed
