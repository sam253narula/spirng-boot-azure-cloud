# spirng-boot-azure-cloud

https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest&tabs=azure-cli

https://docs.microsoft.com/en-us/azure/developer/java/spring-framework/deploy-spring-boot-java-app-with-maven-plugin#:~:text=Deploy%20the%20app%20to%20Azure,-Once%20you%20have&text=Maven%20will%20deploy%20your%20web,URL%20in%20a%20Web%20browser.

https://github.com/spring-guides/gs-spring-boot/blob/master/complete/pom.xml

https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest

https://portal.azure.com/#home

https://github.com/Microsoft/azure-maven-plugins/blob/master/docs/common-configuration.md

Run the login command.

Azure CLI

Copy

Try It
az login
If the CLI can open your default browser, it will do so and load an Azure sign-in page.

Otherwise, open a browser page at https://aka.ms/devicelogin and enter the authorization code displayed in your terminal.

Sign in with your account credentials in the browser.


From the command prompt or terminal window that you were using earlier, rebuild the JAR file using Maven if you made any changes to the pom.xml file; for example:

shell

Copy
mvn clean package
Deploy your web app to Azure by using Maven; for example:

shell

Copy
mvn azure-webapp:deploy





------------------------------------------------------------------


