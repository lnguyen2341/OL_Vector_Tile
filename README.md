# OL_Vector_Tile

A example web application to deploy to Pivotal Cloud Foundry:
1. Download this project zip file and uncompress on your local workstation.  Be sure to keep in its own folder in your local file system, and cd to that directory.
<code> cd ../OL_Vector_Tile</code>
2. Log into your PCF Apps Manager UI: Go to TOOLS and look for the API endpoint
3. Using PCF Command Line Interface (CLI) from your shell tool: Log into the specified PCF endpoint, E.g.,
<code>cf login -a api.run.pivotal.io</code>
4. Select an Org and a Space in which to deploy your app;
5. Using the PCF CLI, push your app
<code>cf push</code>
6. Watch the log feedback on the CLI to see progress of the app being deployed;
7. Reference the app route (URI) from AppsManager and access it via your browser.
