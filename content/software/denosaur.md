# Denosaur

Denosaur is a multi-language package-manager designed for offline-usage. The way it works, is that Denosaur stores and compresses packages within a folder in your home directory, and whenver you need said package, you can retrieve it from the folder.

The (somewhat) offical documentation can be read below here.

## Installation

Run the following installation script t install Denosaur on a system-wide basis.

``` console
powershell -ExecutionPolicy ByPass -c "irm https://github.com/Skrillx13/denosaur/tree/main/scripts/install.sh | iex"
```

## Usage

Create a folder anywhere you would like, and name it denosaur. The folder name is case-sensetive. Now, to save a package, simply run:

``` console
denosaur save npm install mathjax
```

Replace the `npm install package` with the command you would typically run to install a package. For example:

``` console
denosaur save npm install kaplay
denosaur save pip install requests
```

This saves said package to the denosaur folder, making it available for offline usage.

## Installing a package

Assuming you are in offline mode, navigate to the directory you wish to install the package onto, and run 

```
denosaur install npm install kaplay
```

Same thing as before, replace `npm install package` with the package you have saved and wish to use.

## Implementation

I'm not sure if this is useful, given there are a lot of issues with this project, such as:

- Worrying about package compatibility
- Having to manually download and waste storage space.
- No way to transfer out of offline-mode
- May break system operations? (unknown)

But regardless, it's still useful for me whenever I go on long-distance flights, and I want to do some very simple coding.