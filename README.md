## AEM 6.2 Project - Reactor

## How to deploy packages to local instance.
   
   - Use profile 'deploy-author-package' : To build package to author instance
   - Use profile 'deploy-publish-package' : To build package to publish instance
   - Use profile 'auto-deploy-core' : To build only the core package
   
## Project skeleton created with below Maven Archetype 10 by Timmy Mathew
   
   mvn archetype:generate -DarchetypeGroupId=com.adobe.granite.archetypes 
   -DarchetypeArtifactId=aem-project-archetype -DarchetypeVersion=10 
   -DarchetypeRepository=https://repo.adobe.com/nexus/content/groups/public/