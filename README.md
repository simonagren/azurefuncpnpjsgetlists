## Sample from blog post
https://simonagren.github.io/azurefunction-v2-pnpjs/

## Clone
- Clone this repository
- run `npm install` to restore dependencies

## GitHub Deployment
So in VS Code I made a few adjustments before I deployed the content of my Azure Functions.
- In `.gitignore` I removed `local.settings.json` and added `node_modules`.
This is because I didn't want you guys to have to create a `local.settings.json` manually.

## Debug
Debug if you want to by pressing F5, the try it out in the browser `http://localhost:7071/api/PnPHttpFunction?site=<SiteName>`. 

Now you should see a message in the browser with all the lists in the site you entered  

In part 2 we deploy this function:
https://simonagren.github.io/part2-azurefunction-v2-pnpjs/