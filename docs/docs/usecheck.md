# Use Check
Check is a tool that checks if a domain exists in a BobNet JSON.
There are two versions: a module version and a standalone tool.
For developers, use module. For users, use standalone.
This guide is designed for developers. For users, follow the instruction told in standalone.

In order to use checkmod, aka Check Module, you must pass a variable named domain into the checkmod.checkForURL() function. Here's an example:

```python
import checkmod
domain = "hi.bob"
checkmod.checkForURL(domain)
if checkmod.isExist == True:
    print("hi.bob does exist!")
else:
    print("hi.bob doesnt exist!")
```
It passed the domain named hi.bob, and sees if it exists. If it exist, it prints that it exists.

An implementation you could potentially do is something like this:
- See what URL the user inputs
- Check if URL is real with checkmod
- Go to URL