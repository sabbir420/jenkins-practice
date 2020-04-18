pipeline {
     agent any
         stage('Lint HTML') {
              steps {
                  sh 'tidy -q -e *.html'
              }
         }
     }
}
