# This is the AES encyption line from my .travis.yml file that was working
- openssl aes-256-cbc -K $encrypted_b13aa665fbec_key -iv $encrypted_b13aa665fbec_iv
  -in assets/server.key.enc -out assets/server.key -d
