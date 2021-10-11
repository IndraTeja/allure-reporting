# Allure Reporting


## Installation

1. Download .tgz package manually.

https://repo.maven.apache.org/maven2/io/qameta/allure/allure-commandline/

https://docs.qameta.io/allure/

Download using curl

`
curl -o allure-2.6.0.tgz -Ls https://repo.maven.apache.org/maven2/io/qameta/allure/allure-commandline/2.15.0/allure-commandline-2.15.0.tgz
`

2. Extract & copy

`
sudo tar -zxvf allure-2.6.0.tgz -C /opt/   
`

3. set the bin path
 
`
sudo ln -s /opt/allure-2.6.0/bin/allure /usr/bin/allure  
`

4. Check the version


`
allure --version 
`
