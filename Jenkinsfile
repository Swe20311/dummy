node{
    stage("sdsd"){
    sh '''
    #mkdir swetha
    cd swetha
    tee test.sh << 'EOF'
cat $cur/test.sh
echo "variables ${cur}"
echo "test success"
EOF
    '''
    
    sh '''
    cur=swetha
    sh $cur/test.sh
    '''
    }

}
