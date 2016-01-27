# windows-installer-file-search
Python script for finding the Windows Installer (.msi) that installed a specific file.

## Usage
`windows-installer-file-search.py <file path substring>`

## Example
````
> python windows-installer-file-search.py opus.dll
File: C:\Program Files (x86)\Mumble\opus.dll
Product: Mumble 1.2.13
Install user: S-1-5-18
Cached installer: C:\Windows\Installer\2f6b072.msi
````
