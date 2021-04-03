<h1>This is my template for Lightning Web Components which is a Salesforce framework.</h1><br> Heres how to set up and deploy a new application:<br>
<ul>
<li>npx create-lwc-app name-of-app (yes to basic app w/express server)</li>
<li>cd name-of-app</li>
<li>npm run watch (to start server)</li></ul><br>
To deploy in GitHub pages:<br>
<ul>
<li>npm install gh-pages --save-dev</li>
<li>in package.json file, update: "homepage":"{username}.github.io/{name-of-app}"</li>
<li>in package.json file, update: "scripts":"predeploy":"npm run build",<br> "deploy":"gh-pages -d dist",</li><br>
<li>make sure project has a GH origin (ex: git remote add origin https://git@github.com:name-of-app/my-app.git)</li>
<li>npm run deploy (to launch on GH pages)</li></ul><br>
-[Live Link to Test App](https://benjaminpitts.github.io/lwc-test-app/)<br><br>

Find more information on the main repo on [GitHub](https://github.com/muenzpraeger/create-lwc-app).

