# Move me

It is an application which provide the ability to manage the movement of people and companies to a different location
inside a town, to different towns or even countries.

## Getting Started

To start the application for development go to the Class `fh.burgenland.moveme.MovemeApplication` and run the `main` method with your IDE.

## Start Tests in Gradle

To start the Test in Gradle type "./gradlew test" into the Console.

## Create Build with Artifect in Gradle

To start a build with an artifect-output type "./gradlew build" into the Console.
You find the files under ./build/libs

##.editorconfig

You will find predefined editor settings in the ".editorconfig"-File in project root.
You can edit it to change and define the formatting conventions for your textual files in
the project.

##Spotless

to use Spotless the plugin was added in the "build.gradle"-File under the point "plugins"
--> id 'com.diffplug.spotless' version '6.1.2'

then the configuration-section "Spotless" was added by the end of the file (build.gradle)

If './gradlew build' is startet, the procedure will break because of miss-formatations

The command './gradlew spotlessCheck' checks for bad sections.

The command './gradlew spotlessApply' automatically reformats the bad sections.
