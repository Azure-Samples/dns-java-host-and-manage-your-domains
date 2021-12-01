---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Dns
  platforms: java
---

# Getting Started with Dns - Manage Dns - in Java #


  Azure DNS sample for managing DNS zones.
   - Create a root DNS zone (contoso.com)
   - Create a web application
   - Add a CNAME record (www) to root DNS zone and bind it to web application host name
   - Creates a virtual machine with public IP
   - Add a A record (employees) to root DNS zone that points to virtual machine public IPV4 address
   - Creates a child DNS zone (partners.contoso.com)
   - Creates a virtual machine with public IP
   - Add a A record (partners) to child DNS zone that points to virtual machine public IPV4 address
   - Delegate from root domain to child domain by adding NS records
   - Remove A record from the root DNS zone
   - Delete the child DNS zone
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/dns-java-host-and-manage-your-domains.git

    cd dns-java-host-and-manage-your-domains

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.