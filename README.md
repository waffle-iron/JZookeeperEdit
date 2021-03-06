[![Stories in Ready](https://badge.waffle.io/feldoh/JZookeeperEdit.png?label=ready&title=Ready)](https://waffle.io/feldoh/JZookeeperEdit)
JZookeeperEdit
==============

A simple tool for browsing and modifying zookeeper trees.


Config
=======
On first run it will create a config file in your home directory .JZookeeperEdit
where it will save details of servers you connect to if you click "Save Cluster Details"


Requirements
==============
This tool was written using Java 1.8 with JavaFX and Maven as its build tool.
This means you will need the environment variable JAVA_HOME to point to a valid Java 8 Home.

**Note that due to a limitation of controlsfx this tool requires at least Java 1.8.0_20**<br>
The reason for this is discussed in [this](http://fxexperience.com/2014/09/announcing-controlsfx-8-20-7/) blog post

Running using Maven
====================
mvn jfx:run


Creating a Jar
===============
mvn jfx:jar


Creating a native binary
=========================
mvn jfx:native
<br>**Note that this will build a native package for whatever environment you are on**
<br>**For example, a dmg on a mac**


Libraries & Tools
=================
Apache Curator 2.7.1 - Simple ZooKeeper Wrapper<br>
JavaFX Maven Plugin  - Simple JavaFX + Maven
ControlsFX 8.20.8    - Dialogues<br>
Java 1.8.0_20        - Language<br>
Maven 3.2.1          - Lifecycle<br>
JavaFX 8             - GUI

