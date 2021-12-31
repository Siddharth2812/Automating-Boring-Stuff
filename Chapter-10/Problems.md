### Practice Questions
1. What is the difference between shutil.copy() and shutil.copytree()?
>shutil.copy() can only be used for a single file from a source to a destination. shutil.copytree() can be used to copy a directory along with all the files in it.

2. What function is used to rename files?
>shutil.move('oldname', 'newname')

3. What is the difference between the delete functions in the send2trash and shutil modules?
>in send2trash the files will be sent to trash/recycle bin but with shutil we can delete the file permanently

4. ZipFile objects have a close() method just like File objects’ close() method. What ZipFile method is equivalent to File objects’ open() method?
>zipfile.ZipFile('nameoffile.zip',read/write/append)

