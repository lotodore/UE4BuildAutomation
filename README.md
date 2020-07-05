# UE4BuildAutomation
Example Jenkinsfile for cross-platform build automation for UE4

Usage:
- Deploy at least one Jenkins node for each platform, use labels "windows" and "mac"
- Install Powershell Core on nodes.
- Adjust BUILD_PROJECT_NAME (the name of the UE4 project, default is the job name).
- Adjust getBuildArchivePath and getUnrealEngineRoot using the corresponding locations on your Jenkins nodes.
- Adjust the scm "checkout" command according to your needs (this may also require credentials to be set in Jenkins).
