1. Place package.xml in the folder 'deploymentFolder'
2. from CMD run 'ant retrieve'
3. The Folder named 'deployComponent' will be created with all the component listed into package.xml file.
4. To validate change edit build.xml and make 'checkonly = true'.
5. To deploy make checkonly = 'false' and from CMD run 'ant deploy'
5. Delete the 'deployComponent' folder