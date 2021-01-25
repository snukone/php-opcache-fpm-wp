Für Cert-Manager ist unbedingt eine dnsPolicy notwendig!

Für Lets-Encrypt muss unbedingt letsencrypt-prod verwendet werden um kein Fake Zertifikat zu erhalten!

Prüfungen:
`kubectl describe issuer letsencrypt-prod`
`kubectl get secret lesetraum-blog-tls -o yaml`