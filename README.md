# A CI/CD pipline setup

Consisting of:
* git server
* build server
* artifact store

## usage

To use gitea via `gitea.sommer.local` on a Windows machine, append the following lines to `C:\Windows\System32\drivers\etc\hosts` before the `# End of section` line:

```
# cicd-pipeline
127.0.0.1 gitea.sommer.local
127.0.0.1 www.gitea.sommer.local
127.0.0.1 jenkins.sommer.local
127.0.0.1 www.jenkins.sommer.local
```
