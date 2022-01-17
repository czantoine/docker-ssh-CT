  docker build -t eg_sshd .
  docker run -d -P --name test_sshd eg_sshd
  docker port test_sshd 22

``` Cmd prompt
0.0.0.0:49154
```

  ssh root@ip_adress -p 49154
  
  ``` Cmd prompt
# The password is ``azerty``.
root@f38c87f2a42d:/#
  ```
