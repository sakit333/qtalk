# github_nexus
---
- If it needs in windows(local machine) create settings.xml file in .m2 folder and add nexus url and credentials
```bash
.m2/settings.xml
```
```xml
<settings>
  <servers>
    <server>
      <id>nexus-releases</id>
      <username>admin</username>
      <password>admin</password>
    </server>
    <server>
      <id>nexus-snapshots</id>
      <username>admin</username>
      <password>admin</password>
    </server>
  </servers>
</settings>
```
- If it needs in jenkins(CI/CD) 
- create global maven settings.xml file in jenkins