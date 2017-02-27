# Mockito Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[Mockito](http://site.mockito.org/) version 1.10.19.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `mockito-annotations-1.10.19-r.2.jar`. Attach this file to the
Mockito library entry in your build path to have Eclipse use the annotations.