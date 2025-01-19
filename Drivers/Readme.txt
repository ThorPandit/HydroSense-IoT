Java SDK should be higher than 7. 
for 64bit window PC jdk can found from below G-drive link:
https://drive.google.com/file/d/1e9nst-mftWEz1IIZ9cJxPrVg-cQ2E34W/view?usp=sharing


and for Linux and higher version can download from below official link:-
https://www.oracle.com/in/java/technologies/downloads/#java8-windows


Device driver also attached below:-
https://drive.google.com/file/d/1IF_lomgl295Nftpz0qplEg8HVwKakFpS/view?usp=sharing


Process:
After Jdk8 or higher installation, 
1. go to the program File -> java -> jre1.8.0_latest and then "copy the path"
2. open Settings -> environment settings
3. click on Environment variable (present on bottom right)
4. Add new System variables: 
     Variable name: JAVA_HOME
     Variable value: "Copied path of the jre1.8.0_latest
    press ok
5. Now click on Path available in System variable and add a new path
   past the "Copied path of the jre1.8.0_latest" and add "\bin" at last
   example: if path is : C:\Program Files\Java\jre1.8.0_121
   past as: C:\Program Files\Java\jre1.8.0_121\bin
   press ok
6. verify before further proceeding. open command prompt
   write: java -version 
	check the result , result should show the latest installed java jdk version
	such as:
	C:\Users\Shubh>java -version
	java version "1.8.0_121"
	Java(TM) SE Runtime Environment (build 1.8.0_121-b10)
	Java HotSpot(TM) 64-Bit Server VM (build 25.121-b10, mixed mode)


For ubuntu:  install OpenJDK 8 
JDK:
sudo apt-get install openjdk-8-jdk

JRE:
sudo spt-get install openjdk-8-jre

