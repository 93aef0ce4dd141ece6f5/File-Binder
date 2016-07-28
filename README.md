# File-Binder
Binds two files together and updates the stub accordingly. The stub will then drop and execute both files.

The binder works for any (AFAIK) two files, so that can be like `.exe` and `.jpg`, or `.jpg` and `.txt` but you might have to run the file binder/stub generator a second time some times if the output happens to fail on the first build.

## How-to
1. Compile FileBinderStub.c to FileBinderStub.exe
2. Compile and run FileBinder and make sure the FileBinderStub.exe is in the same directory as stated in the `.rc` file.

Usage: `FileBinder.exe [PAYLOAD] [SECONDARY] [OUTPUT]`
