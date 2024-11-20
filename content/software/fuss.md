# Fuss: Fluctuating Stylesheet Syntax

Fuss is a powerful, simple, and extensive CSS extension. Part of it was directly inspired by Sass, but another reason I made Fuss is because I wanted directed CSS support for one of the Fabric Projects, WoodWork.

Fuss now directly supports WoodWork, and vice-versa. However, Fuss can still be used for other projects, that are not necessarily tied to WoodWork.

## Quickstart

Install the Fuss extension for the language you are using:

``` console
npm install fuss
pip install fuss
...
```

Or, if you are simply building a website with HTML, link your Fuss file, and download the Visual Studio Code extension.

``` html
<link rel="stylesheet" href="/stylesheets/styles.fuss">
```

## Basic Syntax

Some basic Fuss styles can look something like this:

``` css
$variable1: 10%

body {
    background-color: #fffff8
    font-family: "Palatino Linotype", "Palatino LT STD"
    padding-left: $variable1
}
```

As you can see, the need for a ";" at the end of a style is removed, and the only time a comma will be used is if there are multiple styles within a line. Variables can also be used, if you are planning on using a style multiple times.

For more information, check out the offical [Fuss Documentation](https://www.youtube.com/watch?v=xvFZjo5PgG0).