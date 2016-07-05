# JDenticon Java API (JDJA)

Identicons are images that are generated for users of websites and programs that are unique for the given username or e-mail o whatever string you want. According to [Wikipedia](https://en.wikipedia.org/wiki/Identicon) an identicon is

>  a visual representation of a hash value, usually of an IP address, that serves to identify a user of a computer system as a form of avatar while protecting the users' privacy.

There are various generators for Identicons out there and when building a powerful program with **Java** you may want to add a bit of an extra for your users. So instead of having one basic image for every user after signup you could use an Identicon. According to [Jdenticon](http://jdenticon.com/) it is a

> free Javascript library for generating highly recognizable identicons.

And the Identicons are very nicely generated and can be generated as *.svg*-files. Unfortunately **JDenticon** is written in *javascript* and can't be used in **Java** without some other code.

___

### Example Pictures

<img src="https://s31.postimg.org/co8invbpj/Test.png" width="200">
<img src="https://s31.postimg.org/ki9499jif/Test_Number_One.png" width="200">
<img src="https://s31.postimg.org/hpfwp8j5z/Test_Number_Three.png" width="200">


___

### JDJA

And that's exactly the point where **Jdenticon Java API** is useful. It let's you easily import the few classes and use the methods to

- **generate hashcodes** from a given String
- **generate a .svg** file from a hashcode
- **save the file** on a given location on your pc

___

### Installation

Simply download the latest file as **.jar** (e.g. "JDJA version 0.5.jar") and add it to your _Java Build Path_

#### Eclipse:

If you want to install JDJA in Eclipse follow these steps after downloading the **.jar**:

0. Create a new project: `File -> New -> Java project` (only if you want to start a new project)
1. go to your Java Build Path: `left-click on your project -> Properties -> Java Build Path`
2. add JDJA: `Libraries -> Add External Jars -> select your downloaded .jar`
3. done, you can now use JDJA

___

### Usage

--- w.i.p.

___

### Downloads

... w.i.p.

___

### ToDo

- [x] add svg support
- [ ] add canvas support
- [ ] add image export for **.png** and **.jpg**
- [ ] rework code for better understanding
