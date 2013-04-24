It is just a sample application that shows hot to execute jersey in eap 6.


To build it make sure you have Maven installed  and then go to root directory and type:

$ mvn clean package

The deployment jersey-eap6-hello-world-0.0.1.war will be generated in target directory:

- Copy it to EAP 6 standalone/deployments directory
- Start EAP using: $ bin/standalone.sh
- With a browser, access URL localhost:8080/jersey-eap6-hello-world-0.0.1.war/hello
- The browser should show the String "Hello World"
