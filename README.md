# JDenticon Java API (JDJA)

Identicons are images that are generated for users of websites and programs that are unique for the given username or e-mail o whatever string you want. According to [Wikipedia](https://en.wikipedia.org/wiki/Identicon) an identicon is

>  a visual representation of a hash value, usually of an IP address, that serves to identify a user of a computer system as a form of avatar while protecting the users' privacy.

There are various generators for Identicons out there and when building a powerful program with **Java** you may want to add a bit of an extra for your users. So instead of having one basic image for every user after signup you could use an Identicon. According to [Jdenticon](http://jdenticon.com/) it is a

> free Javascript library for generating highly recognizable identicons.

And the Identicons are very nicely generated and can be generated as *.svg*-files. Unfortunately **JDenticon** is written in *javascript* and can't be used in **Java** without some other code.

___

### Contents

1. [Example Pictures](https://github.com/xXJetstreamXx/JDenticon-Java-API#example-pictures)
2. [JDJA explained](https://github.com/xXJetstreamXx/JDenticon-Java-API#jdja-explained)
3. [Installation](https://github.com/xXJetstreamXx/JDenticon-Java-API#installation)
4. [Usage](https://github.com/xXJetstreamXx/JDenticon-Java-API#usage)
5. [Downloads](https://github.com/xXJetstreamXx/JDenticon-Java-API#downloads)
6. [Changelog](https://github.com/xXJetstreamXx/JDenticon-Java-API#changelog)
7. [ToDo](https://github.com/xXJetstreamXx/JDenticon-Java-API#todo)

___

### Example Pictures

<img src="https://s31.postimg.org/co8invbpj/Test.png" width="200">
<img src="https://s31.postimg.org/ki9499jif/Test_Number_One.png" width="200">
<img src="https://s31.postimg.org/hpfwp8j5z/Test_Number_Three.png" width="200">

___

### JDJA explained

And that's exactly the point where **Jdenticon Java API** is useful. It let's you easily import the few classes and use the methods to

- **generate hashcodes** from a given String
- **generate a .svg** file from a hashcode
- **save the file** on a given location on your pc

___

### Installation

Simply download the latest file as **.jar** (e.g. "JDJA version 0.5.jar") and add it to your _Java Build Path_. 

#### Eclipse:

If you want to install JDJA in Eclipse follow these steps after downloading the **.jar**:

0. Create a new project: `File -> New -> Java project` (only if you want to start a new project)
1. go to your Java Build Path: `left-click on your project -> Properties -> Java Build Path`
2. add JDJA: `Libraries -> Add External Jars -> select your downloaded .jar`
3. After that download the **jdenticon.js** ([Link](https://cdn.jsdelivr.net/jdenticon/1.3.2/jdenticon.min.js)) and put it into your src folder.
4. you can now use JDJA

___

### Usage

Work in progress (version 0.6 changes)

___

### Downloads

Version 0.5: [MEGA](https://mega.nz/#!xcgWkJYa!KumUEkA5qXQ77byiQ9Hy2u9LI9XCYlXsY1093pQcfMk)

Version 0.7: [MEGA](https://mega.nz/#!tRQFXI4A!5gQMvo2HT5ukdf9sGtyLqCZqWVob6YP4AhYWuOzYPfs)
___

### Changelog

#### Version 0.5 (first public release)

- added support for .svg files
- added export of .svg
- implemented the generation of hash-codes from given strings

#### Version 0.6 [not released]

- minor changes (first implementation of JPG / PNG export)

#### Version 0.7

- made the code look better
- added support for generating JPG
- added support for generating PNG
- added own "Hash" data type (for better handling, to minimize failure)
- added HashGen class to generate hashcodes
- changed data format (now type "File" is getting returned)

___

### ToDo

- [x] add svg support
- [ ] add canvas support
- [x] add image export for **.png** and **.jpg**
- [x] rework code for better understanding
- [ ] add support for **.pdf**
