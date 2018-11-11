# cert-manager
How to use cert-manager and setup ingress controller with LetsEncrypt

############################################################################
# Install Cert Manager for Ingress Controller
############################################################################
```
helm install \
    --name cert-manager \
    --namespace kube-system \
    stable/cert-manager
```
