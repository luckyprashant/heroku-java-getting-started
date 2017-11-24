Technical Documentation LogonApu
=====================================
git: https://stash.eden.klm.com/scm/c3s/logonapi.git
main branch: develop


LOCAL DEVELOPMENT
-----------------

    mvn clean install -DskipTest

###startup:
 
	cd logon\logon-api
	mvn clean install -DskipTests -Pcargo cargo:run -o (uses local.filter)
	
###Local testing:
- Import soap project cd soap
- Start local server
- Hit request to http://localhost:9080/logon-api/logon/v2