node{
    def applicationTitle = 'Learning Project';
    stage('CheckoutCode'){
        git branch:'master',url:'https://github.com/antodavispullan/devop-project1.git'        
    }
    stage('Copy HTML'){
        sh 'cp index.html /var/www/html/'
    }
    stage('Copy Images'){
        sh 'cp -r images/ /var/www/html/'
    }
    stage('Notify Email'){
        sh 'echo "sending email"'
    }    
}