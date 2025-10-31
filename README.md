Artifact HUB

helm install my-mongodb oci://registry-1.docker.io/cloudpirates/mongodb \
  --set replicaCount=2

  helm uninstall my-mongodb 