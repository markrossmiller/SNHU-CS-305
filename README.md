# SNHU-CS-305

Artemis Financial needed an HTTPS server to serve hashed checksums of files over the network. They also needed static testing done on the software, as well as functional debugging.

I added code to the application to address the checksum as well as server code to handle SSL-enabled server with a self-signed certificate.

The most challenging aspect of the project was to get the server to actually run. Eclipse makes it very difficult to run a Spring application, in my humble opinion.

To be honest, I felt the project itself was an easy undertaking. My main issue was not with coding per-se, but rather with the mechanics of getting the software to run. Static testing, whenEclipse cooperated, was as easy as adding in a plugin to the pom.xml file.

I could not get the OWASP plugin code to run during the execution of the project two code, because it refused to download a needed file from a government website. If I had been able to procure this challenge, it would have been easy enough to tell if any new vulerabilities had been added. If there were new vulnerabilities from dependencies, it would have occurred from the Java security libraries which handled the SHA-256 hashing algorithm.

We used keytool, which comes with the Java binary utilities in order to create the certificate file for serving web pages.

I wouldn't showcase this work to a future employer, because in my opinion it doesn't do a good job at showing skills I have in software programming. I would rather create a more functional program from scratch, especially if it were to be refined for actual production environment. I think such a program would do a better job at showing the skills I have at building a program.
