# HElM
1. helm  repo add helm <url> --username <user name> --password <token/password>
2. genrate templet using command eg : `helm template <chart> -f <values file > 
3. to genrate new version use update Chart.yaml : `helm\Chart.yaml`
4. after verify changes command to create package : `helm package . --destination ../packages`
5. update helm index using command  `helm repo index --merge index.yaml ./`
