# Test project for vetting out Groups behaviour

This sample project makes use of the tests that are added as part of the pull request https://github.com/cbeust/testng/pull/2666

Since the above mentioned pull request aims at restoring 
groups behaviour to what it was in TestNG 7.4.0 and before, 
it can be executed against different TestNG versions using the command 

By default this runs against TestNG `7.4.0`
```
mvn  clean test
```

To run the tests against a different version use the below command 

```
mvn clean test -Dtestng.version=7.3.0
```