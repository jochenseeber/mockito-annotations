# ${annotatedProject.name} Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[${annotatedProject.name}](${annotatedProject.url}) version ${annotatedProject.version}.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `${project.name}-${project.version}.jar`. Attach this file to the
${annotatedProject.name} library entry in your build path to have Eclipse use the annotations.