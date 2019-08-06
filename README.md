### evernym
---
https://github.com/evernym

https://www.evernym.com/

```rb
cron::d { 'puppet_agent':
  ensure => $ensure,
  minute => macaddress_rand(60),
  user => 'root',
  command => 'puppet agent -t > /dev/null 2>&1',
}

web_server_ips_array = gethostbyname2array("webs.yourdomain.com")
my_name = gethostbyaddr2array($::ipaddress) 
notify { "My reverse dns seems to be: ${my_name} ": }
```

```sh
```

```
```

