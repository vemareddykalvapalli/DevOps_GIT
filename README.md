# DevOps_GIT
Learning Git
There are not too many requirements for using this plugin:
Jenkins 1.400 or newer
Jenkins Git Plugin version 1.1.12 or newer
At least one GitHub hosted project to build ;-)
Step-by-Step Instructions on How to Use it
Installation
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left-hand side of the screen.
Select the Manage Plugins link.
On the Available tab, select the Github Plugin and click the Download and Install button at the bottom of the page (if you do not got the Git Plugin installed, do not worry, Jenkins is smart enough to install/upgrade the Git plugin, where required).
Restart Jenkins once the plugins are downloaded (Note: users of Jenkins 1.442 or newer should be aware that the plugin currently requires a restart to function correctly).
Configuration
If all you want to do is enable the hyperlinks in the Recent Changes for the build, it is just a case of providing the GitHub project URL in the Jenkins job configuration, e.g.
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
In the GitHub project field, enter the URL of the GitHub project. If your GitHub project's git URL looks like: git@github.com:username/project.git,

then the GitHub project should be: http://github.com/username/project/or if the project is private, you can get faster navigation with: https://github.com/username/project/
If you want to enable build triggering, you need to configure your Jenkins instance for receiving the push notifications from GitHub. There are two ways you can achieve this. The first way is to let Jenkins manage the Post-Receive URLs for you:
Configure System Jenkins
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Let Jenkins auto-manage hook URLs option.
Ensure you have provided at least one username and password for connecting to GitHub (the password is required as GitHub does not expose an API for managing the Post-Receive URLs).
The second way is to manage the Post-Receive URLs yourself:
github repository administration
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Manually manage hook URLs option.
For each project that you want to have triggering builds, you need to open the Repository Administration screen on that GitHub project's page.
Select the Service Hooks tab.
Select the Post-Receive URLs hook.
Add the URL, which will be the root URL of your Jenkins instance with /github-webhook appended.
Jenkins instanceOnce you have configured your Jenkins instance for receiving the push notifications, you can enable jobs being triggered via the push notifications:
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
Select the Build when a change is pushed to GitHub checkbox and save the configuration.There are not too many requirements for using this plugin:
Jenkins 1.400 or newer
Jenkins Git Plugin version 1.1.12 or newer
At least one GitHub hosted project to build ;-)
Step-by-Step Instructions on How to Use it
Installation
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left-hand side of the screen.
Select the Manage Plugins link.
On the Available tab, select the Github Plugin and click the Download and Install button at the bottom of the page (if you do not got the Git Plugin installed, do not worry, Jenkins is smart enough to install/upgrade the Git plugin, where required).
Restart Jenkins once the plugins are downloaded (Note: users of Jenkins 1.442 or newer should be aware that the plugin currently requires a restart to function correctly).
Configuration
If all you want to do is enable the hyperlinks in the Recent Changes for the build, it is just a case of providing the GitHub project URL in the Jenkins job configuration, e.g.
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
In the GitHub project field, enter the URL of the GitHub project. If your GitHub project's git URL looks like: git@github.com:username/project.git,

then the GitHub project should be: http://github.com/username/project/or if the project is private, you can get faster navigation with: https://github.com/username/project/
If you want to enable build triggering, you need to configure your Jenkins instance for receiving the push notifications from GitHub. There are two ways you can achieve this. The first way is to let Jenkins manage the Post-Receive URLs for you:
Configure System Jenkins
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Let Jenkins auto-manage hook URLs option.
Ensure you have provided at least one username and password for connecting to GitHub (the password is required as GitHub does not expose an API for managing the Post-Receive URLs).
The second way is to manage the Post-Receive URLs yourself:
github repository administration
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Manually manage hook URLs option.
For each project that you want to have triggering builds, you need to open the Repository Administration screen on that GitHub project's page.
Select the Service Hooks tab.
Select the Post-Receive URLs hook.
Add the URL, which will be the root URL of your Jenkins instance with /github-webhook appended.
Jenkins instanceOnce you have configured your Jenkins instance for receiving the push notifications, you can enable jobs being triggered via the push notifications:
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
Select the Build when a change is pushed to GitHub checkbox and save the configuration.There are not too many requirements for using this plugin:
Jenkins 1.400 or newer
Jenkins Git Plugin version 1.1.12 or newer
At least one GitHub hosted project to build ;-)
Step-by-Step Instructions on How to Use it
Installation
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left-hand side of the screen.
Select the Manage Plugins link.
On the Available tab, select the Github Plugin and click the Download and Install button at the bottom of the page (if you do not got the Git Plugin installed, do not worry, Jenkins is smart enough to install/upgrade the Git plugin, where required).
Restart Jenkins once the plugins are downloaded (Note: users of Jenkins 1.442 or newer should be aware that the plugin currently requires a restart to function correctly).
Configuration
If all you want to do is enable the hyperlinks in the Recent Changes for the build, it is just a case of providing the GitHub project URL in the Jenkins job configuration, e.g.
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
In the GitHub project field, enter the URL of the GitHub project. If your GitHub project's git URL looks like: git@github.com:username/project.git,

then the GitHub project should be: http://github.com/username/project/or if the project is private, you can get faster navigation with: https://github.com/username/project/
If you want to enable build triggering, you need to configure your Jenkins instance for receiving the push notifications from GitHub. There are two ways you can achieve this. The first way is to let Jenkins manage the Post-Receive URLs for you:
Configure System Jenkins
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Let Jenkins auto-manage hook URLs option.
Ensure you have provided at least one username and password for connecting to GitHub (the password is required as GitHub does not expose an API for managing the Post-Receive URLs).
The second way is to manage the Post-Receive URLs yourself:
github repository administration
Go to your Jenkins instances root page.
If your Jenkins instance has security enabled, login as a user who has the Overall | Administer permission.
Select the Manage Jenkins link on the left hand side of the screen.
Select the Configure System link.
In the GitHub Web Hook section select the Manually manage hook URLs option.
For each project that you want to have triggering builds, you need to open the Repository Administration screen on that GitHub project's page.
Select the Service Hooks tab.
Select the Post-Receive URLs hook.
Add the URL, which will be the root URL of your Jenkins instance with /github-webhook appended.
Jenkins instanceOnce you have configured your Jenkins instance for receiving the push notifications, you can enable jobs being triggered via the push notifications:
Goto your Jenkins instance job.
Select the Configure link on the left hand side of the screen.
Select the Build when a change is pushed to GitHub checkbox and save the configuration.
