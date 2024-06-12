FSCK: File System Consistency Check is a linux by default utility to check file system for errors or outstanding issues.

The fsck tool can be used in various situations:
Use fsck to run a filesystem check as preventive maintenance or when there is an issue with your system.
One common problem fsck can diagnose is when the system fails to boot.
Another one is when you get an input/output error when the files on your system become corrupt.
You can also use the fsck utility to check the health of external drives, such as SD cards or USB flash drives

FSCK SYNTAX:
fsck <options> <filesystem>


To view partitions for your first disk, for example, use the following command:
sudo parted /dev/sda 'print'

