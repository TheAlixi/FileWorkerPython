# FileWorker
## Install

Install library in pip

Requires __pip__ installed

```
pip install fileworkerpy
```
---
## Work with library
### Import library

```python
from FileWorkerPy import *
```
or
```python
import FileWorkerPy
```

## Create File

Create File object
```python
file = File("file_path", "permissions")
```
> If script can't find file, he will send error message to console

## Work with file
### Get file
Method returning a file variable

```python
file.getFile()
```

### Get file path
Method returning a full file path

```python
file.getFilePath()
```

### Get file path name
Method returning a full name of file

```python
file.getFilePathName()
```

### Get file name
Method returning a name of file

```python
file.getFileName()
```
> This method returning only file name without file extension

### Get file extension
Method returning a file extension

```python
file.getFileExtension()
```
