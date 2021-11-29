# Intel Edge Software Provisioner

see https://github.com/intel/Edge-Software-Provisioner

I'm not adding this to the app templates until i know more - the core container runs privileged and in the host namespace, which should scare anyone.

but - if you `docker-compose up`, you should be able to access the bootstrap payloads from https://intel_esp_web_1.loc.alho.st

I'm relying on caddy to revrese proxy containers, so IP address based access won't work, nor will unencrypted requests to port 80.