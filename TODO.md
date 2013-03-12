**tasks**

  - release must be done with maven 3 (see https://github.com/redfish4ktc/redfish4ktc-maven-parent/wiki#wiki-release)
     - configuration of enforcer must be different when performing release (use the release profile to check this)
     - doc (build will failed if maven 3.0.4+ is not used)

**upgrade plugins**

- maven-compiler-plugin to 3.0: check if it is ok with maven 2.2.1
- maven-release-plugin 2.4

**add plugins**
