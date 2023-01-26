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
            def abc = "hello"
            def xyz = 10

            print abc
            print "abc is ${abc}"
            print "xyz is ${xyz}"

        }
      }
    }

  }
}


