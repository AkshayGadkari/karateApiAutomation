### problem Statement : To merge Cucucmber reports of two runs  OR to get the merged Cucumber Report OR to get the Merged Karate Report  ###

Using CLI with help of Maven commands OR Jenkins

RUN 1
:  mvn clean test -Dkarate.options="--tags @Run1"
RUN 2
:   mvn clean test -Dkarate.options="--tags @Run2" 
Then 
some command /script to merge both reports in single one.

**Then Merged Cucumber Reprort**
**should have execution result of both the Runs.**

