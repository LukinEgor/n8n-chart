# Helm chart for n8n

## Install chart
helm upgrade --install --wait --create-namespace --namespace=n8n -f values.yaml n8n .
