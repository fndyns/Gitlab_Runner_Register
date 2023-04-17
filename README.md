# Gitlab_Runner_Register

[ec2-user@ip-172-31-5-206 ~]$ sudo gitlab-runner register
Runtime platform                                    arch=amd64 os=linux pid=15365 revision=bbcb5aba version=15.3.0
Running in system-mode.                            
                                                   
Enter the GitLab instance URL (for example, https://gitlab.com/):
https://internal.git.banct-app.com/
Enter the registration token:
GR1348941UaoWh_wmTcpmR3pa7M9P
Enter a description for the runner:
[ip-172-31-5-206.eu-west-2.compute.internal]: banct-account-svc-runner
Enter tags for the runner (comma-separated):
aws, banct
Enter optional maintenance note for the runner:

Registering runner... succeeded                     runner=GR1348941UaoWh_wm
Enter an executor: custom, parallels, virtualbox, kubernetes, docker-ssh+machine, docker, docker-ssh, shell, ssh, docker+machine:
docker
Enter the default Docker image (for example, ruby:2.7):
amazon/aws-cli
Runner registered successfully. Feel free to start it, but if it's running already the config should be automatically reloaded!
 
Configuration (with the authentication token) was saved in "/etc/gitlab-runner/config.toml" 
(reverse-i-search)`veri': sudo gitlab-runner verify
