# **Basics**

## **Java** was the most widely used programming language for the last couple decades or so and it still is today. Don't look at Javascript or Python or Go. Not even close. You gotta _**give credit where it's due**_.  Java is still everywhere. To give you a big picture view of Java's current usage, take Amazon and Google, most of the Amazon and Google products still use Java technology. 

## _**Nonetheless**_, Java has its cons though the pros outweigh the cons. Java is verbose. That's probably the major _**dealbreaker**_ with Java. It takes probably ten lines of Java code to do the same thing you could do with three lines of Javascript code. 


# **Experiment**

### **1.** We are not going to worry about whether Java is an interpreted language or a compiled language here. It's unnecessary at this stage to _**ponder over**_ such high level concepts. When Java was designed decades ago, it was developed to combat a lot of problems found in earlier programming languages but tackling one nagging problem made Java the most used programming language for decades. That problem is the portability of computer programs. Back then, you mostly wrote code in C or C++. When you write code in C or C++, you need to write platform-specific code for each environment whether you want the code to run in a Mac, Windows or Linux. When Java came around, it changed everything. You would write the code once and it would work everywhere. Java is platform-independent. Java wasn't the first ever platform-independent language. But it was definitely the best one _**in terms of**_ of speed and usability. 

### **2.** When people say Java, they most likely mean the Java programming language. But in reality, Java is much more than that. Java architecture consists of several components, just one of which is the programming language. The four components of Java architecture is laid down below: 

- ### Java programming language
- ### Java class file or Java Bytecode 
- ### Java core APIs 
- ### Java virtual machine (JVM)

### **3.** We will take a look at each components in the appropriate pilots. For now, just let the idea of each Java components _**sink in**_. Enter the following tasks into "master.md":

- ### Look at the source code of Java programming language version 7: http://hg.openjdk.java.net/jdk7/jdk7/jdk/file/9b8c96f96a0f/src/share/classes/java/lang. Look for a file named "Character.java" and enter the number of lines. 

- ### Look at the Java Bytecode of a Java program that prints out "Fluents Inc" created by `Achilles Troy` here: https://github.com/achilleshelenatroy/adventurist/blob/master/java/pilot-01/fluents-bytecode.txt. Look for a line "0: aload_0", enter the line below it. 

- ### Look at the source code of Java Core APIs 8 _**aka**_ Java **Standard Edition** 8: http://hg.openjdk.java.net/jdk/jdk/file/ac6e9a2ebc04/src. 
- ### As you can see, Java Core APIs contains _**tremendous**_ amounts of code so for now look at the source code of HTTP module in NET package of Core APIs: http://hg.openjdk.java.net/jdk/jdk/file/ac6e9a2ebc04/src/java.net.http/share/classes/java/net/http. Look for a file named "HttpResponse.java", enter the number of lines. 

- ### Look at the github repo of **openj9** Java virtual machine: https://github.com/eclipse/openj9. Look for the colored programming language bar, click on it and enter the percentages of C, C++ and Java used in the repository. 

