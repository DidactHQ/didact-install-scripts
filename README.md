# Didact Install Scripts

This repository contains installation scripts that conveniently setup applications of the Didact Platform onto your target system.

For the moment, I intend to use these scripts for easily installing **Didact CLI only**. After installing Didact CLI, you can use its commands to install the other applications such as Didact Engine and Didact UI. If demand arises for dedicated installation scripts for the other Didact Platform applications, then I will be happy to add them.

These scripts are excellent to use for both local development and CI/CD pipelines/production deployments.

Windows, Mac OS, and Linux platforms are all supported by their respective scripts:

| Platform | Script Type | Script |
| --- | --- | --- |
| Windows | Powershell | diadct-cli-install.ps1 |
| Mac OS | Shell | didact-cli-install.sh |
| Linux | Shell | didact-cli-install.sh |