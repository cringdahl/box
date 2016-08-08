node {
   stage '\u2776 Collect Stage 1'
   println "p BUILD_NUMBER = ${BUILD_NUMBER}"
   echo 'e BUILD_NUMBER = ${BUILD_NUMBER}'


   tokens = "${env.JOB_NAME}".tokenize('/')
   org = tokens[0]
   repo = tokens[1]
   branch = tokens[2]
   // echo 'org/repo/branch=${env.JOB_NAME}'

   echo '\u2776 Comitted \u2713.'

   stage '\u27A1 Build Stage 2'
   echo '\u27A1 Built.'

   stage '\u2756 Test Stage 3'
   echo '\u2756 Terrified \u274C.'
   echo '\u2756 Verified \u2705.'

   stage '\u273F Stage Stage 4'
   echo '\u273F Staged \u2705.'

   stage '\u2601 Deploy 5'
   echo '\u2601 Not deployed \u2639.'
   echo '\u2601 Deployed \u263A.'
}
