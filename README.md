# phpdatabase
Create from console openshift Mysql database persistent (default value generated if empty)
Create from console openshift Php https://github.com/cuccurese2010/phpdatabase.git(Application Name:test)
From CLI: oc env dc test -e databaseuser=user8HG -e databasepassword=r1HcnG6i5SOc6ad5 -e databasename=sampledb
The secret value from db Mysql you can find it in the console path:Resources/Secrets/mysql
The variables databaseuser databasepassword databasename they are variables project file dbtest.php
