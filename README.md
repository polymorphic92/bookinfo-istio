*Start cluster : `oc cluster up --skip-registry-check`  
*go to console : https://127.0.0.1:8443
*install istio : ./install-istio `istio version` - ex : 1.0.5
*wait for pods to come up 
*deploy bookinfo ./deploy-bookinfo `istio version` - ex : 1.0.5
*wait for pods to come up 
*hit endpoint : ./curl-loop
*install kiali ./install-kiali
*go to kiali : https://kiali-istio-system.127.0.0.1.nip.io