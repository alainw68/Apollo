+++
title = "rm"
chapter = false
weight = 103
hidden = false
+++

## Summary
Delete a specified file.

### Arguments (positional)
#### path
Path to a the file to be deleted. If this is not a full path, the agent's current working directory will be used. 

## Usage
```
rm [path]
```
Example
```
rm C:\config.txt
```

## Detailed Summary
The `rm` command uses the `System.IO.File.Delete` method to attempt to delete a specified file.
