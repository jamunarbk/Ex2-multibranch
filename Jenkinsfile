pipeline { 
agent any 
stages { 
stage('Build') { 
steps { 
echo "Building application from MAIN branch" 
} 
} 
stage('Test') { 
steps {
echo "Running tests on MAIN branch" 
} 
} 
stage('Deploy') { 
steps { 
echo "Deploying to production" 
} 
} 
} 
}
