#### Done by tutorial: http://www.baeldung.com/spring-cloud-bootstrapping

##### Before running instruction:
1. see the property `spring.cloud.config.server.git.uri=file:///${user.home}/application-config` in the `application.properties` of the config server, see the next
2. add `application-config` folder to the (for windows) c:\Users\<your_user_name>\(see also additional info in the `APPENDIX 1`)

##### APPENDIX
The most significant setting for the config server is the git.uri parameter. </b>
 This is currently set to a relative file path that generally resolves to c:\Users\{username}\ on Windows or /Users/{username}/ on *nix. </b>
 This property points to a Git repository where the property files for all the other applications are stored. </b>
 It can be set to an absolute file path if necessary. </b>
 </b>
Tip: On a windows machine preface the value with ‘file:///’, on *nix then use ‘file://’. </b>
