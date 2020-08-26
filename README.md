
ODOT [Statewide Model](https://github.com/pbsag/tlumip) Synthetic Population (SPG) module

### Dependencies
The synpop dependencies are:

  - [CMF (common base)](https://github.com/pbsag/cmf) (this is a private repo)
  - [censusdata](https://github.com/pbsag/censusdata) (this is a private repo)
  - [utils](https://github.com/pbsag/utils) (this is a private repo)
  - log4j
    
synpop includes copies of the dependent jars since the souce code is private.

### Build Instructions
1. Download Eclipse Luna
2. Import synpop as an Eclipse project
3. Update .classpath references to the external required jars stored in the src folder
4. Build with Ant
  1. Right click on build.xml and select Run As and then Ant Build.  This should fail, but will setup a default Ant Build configuration
  2. Right click on build.xml and select Run As and then External tools configurations
  2. Go to the Targets tab and check "release"
  3. Click Run to build 
5. synpop.jar in the release folder is the release version



