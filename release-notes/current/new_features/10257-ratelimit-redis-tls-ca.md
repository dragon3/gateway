Added `caCertificateRef` to the global rate limit Redis TLS settings, so the rate limit service can verify a Redis server certificate signed by a private CA stored in a ConfigMap or Secret.
