Download Link: https://assignmentchef.com/product/solved-assignment-7-java-program
<br>
<span class="desktop">From the below Java code, extend it and create a few</span> derivative classes, i.e. a Router, a Switch, a Server, a PSU (Power Supply Unit) etc. Each of those new classes has to be declared as extending the base Asset class and introduce new attributes and methods. For example, you may consider the following skeletons or add something that matches your expectations: Router

• String application; // one from the following list “Home”, “Core”, “Infrastructure”, etc

• int numOfNICs; // number of network interfaces

• String OS; // operating system. including vendor, version, and other details

• boolean hasConsole; // flag that indicates presence of management <a href="https://www.justanswer.com/topics-console/">console</a> Switch

• int numOf_100M; // number of 100Mb ethernet interfaces

• int numOf_1G; // number of 1Gb ethernet interfaces

• int numOf_10G; // number of 10Gb ethernet interfaces

• int numOf_SFP; // number of SFP modules

• String OS; // operating system. including vendor, version, and other details

• String level; one from the following list “L2”, “L3”, “L4” Server

• String OS; // same as with the Router

• int NumOfNICs; // same as with the Router

• boolean isVirtualized; // flag that shows whether or not this server is a Virtual Machine running on some virtualization platform You may add more types of assets, and more attributes into each asset to make it looking more realistic, but the grading decision will be based on whether or not inheritance is defined correctly.

Inheritance should not be considered as only including keyword “extends” in the declaration of a class, but mainly as a proper set of methods that have to be either added or overridden. One of such methods would be the constructor, such that constructor of the Router class will be different than constructor of the Switch class, but both should call constructor of the Asset class by using super(); notation. You may also consider adding up getters/setters for the extended set of attributes.

Please also have in mind that a customized version of toString() method is needed for each derivative class in order to be able to “print” corresponding objects. Such method is about to return presentation of all valuable class attributes in form of a formatted String object. Finally, your Driver program also needs to be revised to update the way how different assets are instantiated Starting Code: