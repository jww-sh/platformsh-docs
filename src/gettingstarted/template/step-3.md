# Start with a template

## Build, Deploy, Done!

Once you have configured the template application in the previous step, Platform.sh will build your project for you.

1. **The management console**

   When the build screen has cleared, Platform.sh will return you to the management console. This time, however, you will be on the main page for your new project, `My First Project`.
   
   ![New Project verify](/videos/new-project.gif)
   
   From here, you can control the settings of this project, as well as monitor its status.
   
   In the `Environments` box, click on `Master`.
   
2. **Check the build status**

   As Platform.sh completes its build, take a minute to notice the information available on this page.
   
   * **Overview**
   
      In this box, the `Master` environment, which is a live environment build from the `master` branch of our project, will have a status of `Building`. 
      
      Once that status has updated to `Active`, the site is live.
      
      ![Build status](/images/getting-started/template/build-status.png)
      
   * **Environment Activity**
   
      In this box, you can see what we have done so far has two initial entries: `My First Project` was created, and a template profile was initialized based on the template you chose in the previous step.
      
      ![Environment activity](/images/getting-started/template/env-activity.png)
   
3. **Done!**

   That's it! Once the build status has changed to `Active`, you're application has been deployed on Platform.sh.
   
   You can view the template now by clicking on the link that is now visible for the `Master` environment under the Overview box. 
   
   It will open another tab in your browser to your new live site!
      
   
> In these few steps you have created a free trial account, configured a maintained template for your project and deployed it using the management console in your browser. 
>
> Platform.sh provides far more features and control than we have covered here, so we will next explore what some of those features are and how to work with them.

<html>
<head>
<link rel="stylesheet" href="/styles/styles.css">
</head>
<body>

<br/><br/>

<center>

<a href="/gettingstarted/template/step-2.html" class="buttongen small">Back</a>
<a href="/gettingstarted/template/step-4.html" class="buttongen small">I have built and deployed a template project</a>

</center>

<br/><br/>

</body>
</html>