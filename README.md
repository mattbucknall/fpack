# fpack
Tool for packaging, signing and encrypting firmware images

## Usage
```
fpack <spec-file> <fpk-file> [root-dir]

  <spec-file>      Path to input JSON file specifying images
                   to include in FPK file, encryption keys
                   etc.
                   
  <fpk-file>       Path for FPK output file.
  
  [root-dir]       Optional argument, specifies path prefix
                   for any files referenced in <spec-file>.
```
