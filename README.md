## Instructions



```shell
# Execute the publish task
./gradlew publish

# Check the generated ivy.xml file for app,
# nothing listed in the <dependencies> tag.  
cat build/ivy-artifacts/com.test.app/1.1/app/ivy.xml
```
