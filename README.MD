# JSDoc DocSet Generator

**(4/20/2015) Fork Note from mvd7793:** The [original repo](https://github.com/theasta/jsdoc-docset-generator) was unfinished at the time this was forked. I hacked it together so it would actually work for my use case. The entity detection is as basic as it can go (e.g. it only detects classes in the top level directory of `documentation`), but it does generate something mildly useable. I will look into more work on this later. Feel free to bug me if this is something you would actually use. :)

Generates a DocSet from JSDoc documentation. This DocSet can be used with the Dasp App.

## Configuration

```
{
  "docSetRoot": "/path/to/dir",
  "docSetName": "MyDocSetJs",
  "docSetIdentifier": "MyDocSet",
  "docSetPlatformFamily": "MyDocSet",
  "icon": "/path/to/my/icon.png",
  "documentation": "/path/to/jsdoc/output"
}
```
