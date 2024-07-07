# Generate framework compatibility matrix from fqnames

- Download these 2 files
- Compile AOSP without fcm from stock and wait for check_vintf to error out
- Delete Python prefix from all lines (e.g. `checkvintf E 06-24 00:30:22 49120 49120 check_vintf.cpp:554]`)
- Paste the result in fqnames.txt
- Launch the script
