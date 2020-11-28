#  Build WordPress with SSL
*  create wpress and mysql docker image in the build directoy
*  run the renew-cert.sh to copy letsencrypt cert files to wpress-files folder
*  run the deploy.sh to copy files to volume folders
*  run the crNetwork.sh to create proxyNET network
*  run startup and shutdown scripts to start or shutdown wordpress 
