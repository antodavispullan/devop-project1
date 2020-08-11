node{
    def applicationTitle = 'Learning Project';
    stage('CheckoutCode'){
        git branch:'master',url:'https://github.com/antodavispullan/devop-project1.git'        
    }
    stage('Copy HTML'){
        sh 'sudo cp index.html /var/www/html/'
    }
    stage('Copy Images'){
        sh 'sudo cp -r images/ /var/www/html/'
    }
    stage('Notify Email'){
        sh 'sending email'
    }    
}