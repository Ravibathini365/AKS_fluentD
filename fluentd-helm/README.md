

helm repo add vsc-fluentd-helm/fluentd-helm https://vscojfrog.vsazure.com/artifactory/vsc-fluentd-helm/ --username teamcity --password 6mKezA5nz6Rre1A4

helm install fluentd vsc-fluentd-helm/fluentd-helm -n kube-system --set dataType=prod