# kube-flipstarter
Kuberntes configurations for flipstarter.cash on GCE. Note that this requires `cert-manager` if you use the ingress features.

## Deployment
1. Add a new blank disk on GCE called `flipstarter-data` that is as small as you can make it. You can always expand it later.
2. Edit `kube/flipstarter-ingress.yml` with your preferred domain name.
3. Run `kubectl apply -f kube`.
4. Profit!
