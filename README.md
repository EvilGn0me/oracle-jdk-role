Oracke-JDK-role
=========

Installs latest oracle-jdk

oracle naming sucks to set version with - or _ in the end of version tag. 

As of 06.10.17 oracle dont give you permanent link to download jdk. You need to adjust few params to make this role download jdk. Please refer to defaults/main.yml. version, version_hash and version_prefix is permanent values that should be adjusted for various java versions. authparam is the only parameter that has timeout. You should go to http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html , after you receive link to download java, you have like 10 minutes before authparam will be expired.
