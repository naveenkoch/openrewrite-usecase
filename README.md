# openrewrite-usecase
  
  Openrewrite Upgrade recipe example

  In this project the dependencies are declared in root project's build.gradle file by varialbe and refer them in sub projects.

# How to Run Rewrite Upgrade Recipe
 
  To run recipes place the init.gradle file in the parent folder of this project and in the command line of this project run the below gradle command
  
```
gradle --init-script ../init.gradle rewriteRun
```
# Problem
  After running the recipe the dependencies are not upgrading eventhough the recipe ran without any error.
  Even if we run change the init.gradle script to allprojects rather than rootProject still it's not working.
 
 
