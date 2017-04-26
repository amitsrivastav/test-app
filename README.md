#POLL SCM "H/5 * * * *"
Merge your feature branch back into your main or master branch once the committed code passed the unit test.
Execute static code analysis, such as code coverage, code complexity, checks for common bugs, etc.
Publish your build artifacts to a repository, such as Artifactory or Sonatype Nexus
Deploy your application to an integration test environment
Execute integration tests
Deploy your application to a performance test environment
Execute a load test against your application
Deploy your application to a User Acceptance Testing Environment (UAT)
Deploy your application to production

Refereances 
http://www.javaworld.com/article/3123117/development-tools/open-source-java-projects-jenkins-with-docker-part-1.html


Jenkins project types:
Freestyle project: This most common type of project allows you to monitor a source code repository and use any build system, such as Maven and Ant.
Pipeline: Choose this project type for complicated projects with moving parts that you need to coordinate across multiple build slaves. We'll explore pipelines more in Part 2.
External job: Use this to configure an automated external job that you want to track in Jenkins as part of your build.
Multi-configuration project: This is the job type for projects that require different configurations for different environments, such as production, staging, and test.
Folder: When you have a complicated build then you might want to organize things into folders, each with their own distinct namespace.
Multi-branch pipeline: automatically create a set of pipeline projects, based on the code branches that are defined in your source code repository

for correct referance 
https://oliverveits.wordpress.com/2016/12/22/getting-started-with-jenkins-part-3-periodic-vs-triggered-builds/