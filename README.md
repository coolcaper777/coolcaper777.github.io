# coolcaper777.github.io

This site exists to serve one file: a Tesla Fleet API partner public key, at the
fixed well-known path Tesla's developer platform requires:

```
/.well-known/appspecific/com.tesla.3p.public-key.pem
```

It's part of a personal home-automation project (an Indigo plugin for commanding
Tesla vehicle charging from excess solar). The key published here is the *public*
half of an EC (P-256) keypair used to sign Tesla Fleet API vehicle commands - the
matching private key is never published and never leaves the host machine.

No other content is served from this site.
