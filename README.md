# Ant-WebProject

Once you run the ant command, it will generate the jar file.

Run the jar file as follows.
# java -jar <<Path to Jar file>>/HelloWorld-20170629.jar

Note: In MAC or Linuc before running java, give the execute permissions as follows.
#chmod -R 777 <<Path to Jar file>>/HelloWorld-20170629.jar
  
  
  ---------------------------------------------------------------------------------------------
  
  Build.xml:
   
   Contains all the instructions:
   
   1. Copy all the files except java files to "build/classes"
   
   2. Compile .java files in "src" directory and copy .class files in "build/classes"
   
   3. Package all the content in "build/classes" and "WebContent" as a war/jar/ear files.
   
   4. Deploy the war/jar/ear file in to "webapp" directory of Tomcat
   
   5. Cleanup "build/classes"

