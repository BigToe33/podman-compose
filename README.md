# How To Run:

```
sudo systemctl daemon-reload
sudo systemctl enable --now ngofs.service ngofs-reload.timer
```

# Gives Error:
Using ```sudo systemctl status ngofs.service``` to check the status of the service I get the error:  
  <Error: error adding pod to state: name "NGOFS2" is in use: pod already exists  
  Error: error creating container storage: the container name "ngofs-cron" is already in use by "some ID number". You have to remove that container to be able to reuse that name.: that name is already in use.
