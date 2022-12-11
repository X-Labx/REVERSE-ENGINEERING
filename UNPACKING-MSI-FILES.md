Open a command prompt in Admin mode.

Then:

msiexec /a drive:\filepath\to\MSI\file /qb TARGETDIR=drive:\filepath\to\target\folder

using the desired locations to fill the above mentioned filepaths. Example:

msiexec /a c:\testfile.msi /qb TARGETDIR=c:\temp\test

You may need to create any directories it uses, you can also monitor its activity before, after and during using various tools.

