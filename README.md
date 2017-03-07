# 137-jars
A Maven repository of jars that I need to grab but haven't been hosted anywhere else.

**To future self** add a new jar:

Place jar in jars subfolder

Add jar to maven repo:

mvn install:install-file -DgroupId=codemining.deps -DartifactId=$depname -Dversion=$version -Dfile=$path -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=./repository -DcreateChecksum=true

The repository url to use in gradle or maven is:

https://github.com/lukehb/137-jars/raw/master/repository

## More info
http://riaconnection.wordpress.com/2012/08/01/create-your-own-github-maven-repository/
