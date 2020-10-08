## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is sample of what I have learn at BeCode Brussels 
	
## Technologies
Project is created with:
* HTML5
* CSS3
* BOOTSTRAP
* SASS
	
## Setup
To run this project, install it locally using npm:

```
sass source/index.scss css/index.css

```

See sass --help for additional information on the command-line interface.

Dart Library
You can also use Dart Sass as a Dart library to get the speed of the Dart VM plus the ability to define your own functions and importers. To add it to an existing project:

1/ Install the Dart SDK. Make sure its bin directory is on your PATH.

2/ Create a pubspec.yaml file like this:


```
name: my_project
dev_dependencies:
  sass: ^1.27.0

```

1/ Run pub get.

2/ Create a compile-sass.dart file like this:

```
port 'dart:io';
import 'package:sass/sass.dart' as sass;

void main(List<String> arguments) {
  var result = sass.compile(arguments[0]);
  new File(arguments[1]).writeAsStringSync(result);
}
```
1/ You can now use this to compile files: dart compile-sass.dart styles.scss styles.css

```
dart compile-sass.dart styles.scss styles.css
```
Learn more about writing Dart code (it's easy!) and about Sass's Dart API


# css-integration-challenge
https://github.com/becodeorg/Startup-Brussels-Johnson-5.25/tree/master/1.The-Field/End-of-Fields-Consolidation-Challenges



https://nick-c0de.github.io/css-integration-challenge/.
