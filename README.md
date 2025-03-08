# obscuretosh

This is a personal repository of mine that has Hackintosh EFIs for various
obscure devices that _I may or may not gather_.

> Please keep in mind I, and the entirety of the Hackintosh community, do
> **not** endorse the usage of prebuilt EFIs as there is always a likelyhood
> of unexpected behaviours or bricks occuring.

> **The contents of this repository excluding the files yielding information
> about this repository (e.g. this readme, .gitignore, etc) are **solely**
> for personal archival purposes only and you are hereby responsible for
> any further damage it could cause your device.**

## Structure of files

### Devices:

Each device's EFI folder will have this naming format:
```
XXXXXXXXXX~YYYYYY:ZZ.ZZ.Z
```
Where:
- __X__ takes place of the name of the device's model
- `~` is a delimiter
- __Y__ takes place of the macOS version it's contents were gathered for
- __Z__ takes place for the **exact** macOS version.

### Current devices on this list

**along with comment,**

| Model Name    | CPU Name | macOS Version | Comments                                      |
| ------------- | -------- | ------------- | ----------------------------------------------|
| NT370R5E-A44S | i3-3120M | 11, Big Sur   | Brightness, Camera and Ethernet does not work |

## Contributing

### Problem fixes:

Open an issue addresssing your potential fix to one of the problems
any given device may have (in Comments section of the table above),
test it and take note of every event for legitibility (not a native speaker so that might not be a real word).

The format for a **problem fix** issue:
```
[<model name> | problem fix]: <minimal description of problem that's fixed>
```

### Additions:

If you somehow found your way to this very dead repository and you,
for some reason, want your EFI to be here, it MUST meet these
requirements:

1. Youtube/Google search results for your device must not be mostly in English.
2. Search engine results much show only results from online e-commerce websites and manufacturer documentation.
3. Device must be older than 5 years.

The format for a **device addition** issue:
```
[<model name> | device addition]; <whatever mininal description you want>
```
