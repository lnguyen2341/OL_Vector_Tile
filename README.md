# OL_Vector_Tile

For a simple demonstration to deploy this app to Cloud Foundry:
1. Download this project zip file to your local workstation.  Be sure to keep in its own folder in your local file system, and cd to that directory.
<code> cd ../OL_Vector_Tile</code>
2. Use the PCF Apps Manager: Go to TOOLS and look for the API endpoint, e.g.
<code>cf login -a api.run.pivotal.io</code>
3. Use the PCF Command Line Interface (CLI) from your shell tool: Log into the specified Cloud Foundry endpoint;
4. Select an Org (if needed) and a Space;
5. From your project's directory, type: <code>cf push</code>
6. Retrieve your app's URI from AppsManager, et voila!
