
TestPlus Folder
===============

The `TestPlus` folder is the parent folder of the test root directory.  The test root folder
is typically named for the root namespace of the org.  For example 'yourorg'.  The organization
root folder should containe a `__testroot__.py` file to indicate it is the root folder.

The `__testroot__.py` file should also contain a constant variable that declares the
type of test root that is represented.  For example:

```
    ROOT_TYPE = "testplus"
```
