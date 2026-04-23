# Command to managing files, directories and text
# Principal commands to Linux+

## The **ls** command's commonly used options
### Display all file and subdirectory names, inlcluding hidden files' names
> ls -a or --all 

### Show a directory's own metadata instead of its contents
> ls -d or --directory

### Classify each file's type using an indicator code (*,/,=,>,@, or |)
> ls -F or --classify

### Dsplay al file and subdirectory names along with their associated index number
> ls -i or --inode

### Display file and subdirectory metadata, which includes file type, file access permissions, hard link count, file owner, file's group, modification date and time, and filename
> ls -l

### Show a directory's contents, and for any subdirectory within the original directory tree, consecutively show their contents as well (recursively)
> ls -R

## The **touch** command's commonly used to create files
> touch chahad.txt

> touch chahad.txt chahad1.txt chahad2.txt

## The **mkdir** command's commonly used to create directories
> mkdir chahad

> mkdir /home/chahad/linux

> mkdir -p chahad/linux/ubuntu

## The **cp** command's commonly used options
### Perform a recursive copy and keep all the files' original attributes, such as permissions, ownership, and time stamps 
> cp -a or --archive

### Overwrite any preexisting destination files with same name as destination.
> cp -f or --force

### Ask before overwrite any preexisting destination files with same name as destination.
> cp -i or --interactive

### Do not overwrite any preexisting destination files with same name as destination
> cp -n or --no-clobber

### Copy a directory's contents, and for any subdirectory within the original directory tree, consecutively copy its contents as well (recursive)
> cp -R,-r or --recursive

### Only overwrite preexting destination files with the same name as destination, if the source file is newer
> cp -u or --update

### Provide detailed command action information as command executes
> cp -v or --verbose

## The **mv** command's commonly used options
### Overwrite any preexisting destination files with same name as destination
> mv -f or --force

### Ask before overwriting any preexisting destination files with the same name as destination
> mv -i or --interactive

### Do not overwrite any preexisting destination files with the same name as destination
> mv -f or --no-clobber

### Only overwrite preexisting destination files with the same name as destination if the source file is newer
> mv -u or --update

### Provide detailed command action information as command executes
> mv -v or --verbose

## The **rsync** command's commonly used options
### Use archive mode
> rsync -a or --archive

### Retain device and special files
> rsync -D

### Retain file's group
> rsync -g or --group

### Display any numeric output in a human-readable format
> rsync -u or --human-readable

### Copy symbolic links as symbolics links
> rsync -l or --links

### Retain file's owner
> rsync -o or --owner

### Retain file's permission
> rsync -p or --perms

### Display progression of file copy process
> rsync --progress

### Copy a directory's contents, and for any subdirectory within the original directory tree, consecutively copy its contents as well (recursive)
> rsync -r or --recursive

### Display detailed file transfer statistics
> rsync --stats

### Retain's files modification time
> rsync -t or --times

### Provide detailed command action information as command executes
> rsync -v or --verbose

## The **rm** command's commonly used options
### Delete any empty directories
> rm -d or --dir

### Continue on with the deletion process, even if some files designated by the command for removal do not exist, and do not ask prior to deleting any existing files
> rm -f or --force

### Ask before deleting any existing files
> rm -i or --interactive

### Ask before deleting more than three files, or when using the -r option
> rm -I

### Delete a directory's contents, and for any subdirectory within the original directory tree, consecutively delete its contents and the subdirecoty as well (recursive)
> rm -R, -r or --recursive

### Provide detailed command action information as command executes
> rm -v or --verbose