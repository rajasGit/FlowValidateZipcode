FlowValidateZipcode
===================

Flow Apex Plugins for Validation ZIpcode

This is a sample Salesforce ANT package which can be used to deploy the code necessary for performing Zipcode validation from a Flow.
The package includes 2 separate Apex plug-ins using separate web services to validate the zipcode.


Instructions( When using Salesforce Ant)
-----------------------------------------
1. Get the package
2. Modify the build.properties file to point to your salesforce instance
3. run 'ant deployUnpackaged'
4. Before using the Apex Plug-in in a flow, make sure you set up the security controls to enable callouts to 'http://www.webservicex.net'


Instructions( When NOT using Salesforce Ant)
-----------------------------------------
1. Get the package
2. Create the Apex Classes listed in the package manually. 
4. Before using the Apex Plug-in in a flow, make sure you set up the security controls to enable callouts to 'http://www.webservicex.net'
