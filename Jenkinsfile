// pipeline {
//     agent{
//        label 'ansible'
//     }
//
//
//     stages {
//         stage('Hello') {
//             steps {
//                 echo 'Hello World'
//             }
//         }
//         stage('Hello1') {
//                 steps {
//                     echo 'Hello World'
//                 }
//             }
//         stage('Hello2') {
//                 steps {
//                     echo 'Hello World'
//                 }
//             }
//     }
//     post {
//      always {
//       echo "sending email"
//      }
//     }
//
// }

//@Library('roboshop') _
//
// test()
pipeline {
  agent any
  stages {
    stage('vars') {
      steps {
        script {
             abc = "hello"
             xyz = 10
             env.pqr = "welcome"
            print abc
            print "abc is ${abc}"
            print "xyz is ${xyz}"
            print "pqr is ${pqr}"

        }
        script {

            print "pqr is in second script as a global variable ${pqr}"

        }
      }
    }

  }
}


