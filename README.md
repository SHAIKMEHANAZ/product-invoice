# product-invoice
FREE STYLE PROJECT
Get-ChildItem $env:USERPROFILE\Downloads -Filter jenkins.war
Navigate to Downloads
cd $env:USERPROFILE\Downloads
Start Jenkins on port 8081

If jenkins.war is directly inside Downloads:
java -jar jenkins.war --httpPort=8081
http://localhost:8081
Get-Content "$env:USERPROFILE\.jenkins\secrets\initialAdminPassword"
