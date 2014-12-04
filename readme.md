# Deployment plan for my site.
##### Written by Daniel Carroll

### All production and basic testing will be done on the local machine.
### Servers will be configured IOW the standard server spinup SOP.

##### 1) Once local development is complete merge to github.
Once you have completed development on your new feature, create a "NewFeatureBranch" on github and allow other developers to test and troubleshoot. 
Once that testing is complete, pull the new code back to your machine and merge with any changes youve made. Test and fix any problems youve created.   
When all features are working as expected, push the info back to the master branch of github.

#### 2) Now your ready to put the site on the web.
Push new code to "Staging" server.  
Troubleshoot with all major browsers and check for any live problems. Include other developers in this process.
If problems are found, Repeat step 1 until problem is resolved and then continue.
When no problems exist, push the updated code to the live server.

#### 3) Now your site is live to the world!
Now that your code is on the live server, you should expect visitors to hit your site.  
Continue to monitor for abnormal functionality and check your "WebMaster" email often.  
If you find a problem, go back to step 1 and repeat in order.
