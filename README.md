# OL_Vector_Tile

A example web application to deploy to Pivotal Cloud Foundry:
1. Download this project zip file and uncompress on your local workstation.  Be sure to keep in its own folder in your local file system, and cd to that directory.
<code> cd ../OL_Vector_Tile</code>
2. In the manifest.yml file, modify the name of the application to your choice.  Note: the application name must be unique across your PCF foundation.
3. Log into your PCF Apps Manager UI: Go to TOOLS and look for the API endpoint
4. Using PCF Command Line Interface (CLI) from your shell tool: Log into the specified PCF endpoint, E.g.,
<code>cf login -a api.run.pivotal.io</code>
5. Select an Org and a Space in which to deploy your app;
6. Using the PCF CLI, push your app
<code>cf push</code>
7. Watch the log feedback on the CLI to see progress of the app being deployed;
8. Reference the app route (URI) from AppsManager and access it via your browser.
