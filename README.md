# libitext-rtf-java-maven Debian package

Official libitext-rtf-java Debian package installs .jar only into `/usr/share/java`, but not into local Maven repo (`/usr/share/maven-repo`).

The current package simply depends on `libitext-rtf-java` and creates necessary symlink and .pom file in Debian local Maven repo, so that `com.lowagie:itext-rtf:debian` is available from that repo.
