node {
   
                   echo "STAGE: Checkout Source >>> STARTS";
                   stage('Git Checkout'){
                        checkout scm
                    }
                    echo "STAGE: Checkout Source >>> ENDS";
                     
                    echo "STAGE: Run Jmeter test >>> STARTS";
                    stage ('Run JMeter Test'){
                    bat 'D:/apache-jmeter-5.2.1/bin/jmeter.bat -n -t D:/apache-jmeter-5.2.1/extras/Test.jmx -l test.jtl'
                    }
                     echo "STAGE: Run Jmeter test >>> ENDS";
     }
