# So, you have a library module that is common to more than 1 project

if you use composite build you can achieve 3 goals

1. make your project resolve the library dependency like you resolve binary dependency (with implementation ("group:artifact:version") ) without the need to create a repository (using the project name and group id of the library)
2. update the library without the versioning-deploy-consume process
3. see the library in the same idea window as your project (even though its existence in another folder)