## Getting Started:


###### Description
 
 Kubernetes is an open-source system for managing containerized applications. It groups containers that make up an application into logical units for easy management and discovery.

 With the Kubernetes Action Pack you will be able to orchestrate the deployment of your containerized business applications.

###### Actions
 
 1. Create Resource
 2. Get Resource
 3. Delete Resource
 4. Rolling Update
 
 ###### Compatibility:
 
 1. Open JDK Java 11 
 2. Oracle Java 1.7 
 3. open source Kubernetes 1.9.0


###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. ITPA Shared Action Pack should be installed. 

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**

###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_KUBERNETES.PUB.DOC.xml)


###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)
