# Tech610-ttt-App-CICD-Jenkins

This repo is for automating the testing and deployment of the Tic-Tac-Toe application using Jenkins CI/CD pipelines

Line addded to test webhook after webhook troubleshooting which added `github-webhook/` to the end of the Paycode URL. Done on main branch.

Line to test webhook works on dev branch- 2nd attempt after troubleshooting

Line added to test the CI/CD pipeline by triggering Job 1 on the dev branch and verifying the merge from dev to main branch

Line added to test whether the merge from dev to main working with only the git plugin configuration at the bottom of the `maria-ttt-job2-ci-merge` item

Line added to test whetehr job 3, deploying the app using jenkins will work now that I have allowed for ssh from jenkins ip and updated the public ip from my fresh EC2 instance (started up using terraform) into my execute shell on jenkins.

Line added to see if my ip may be an issue and execute shell needs this to fetch it: 
```bash
echo "Current Jenkins build-agent IP:"
curl -4 https://ipv4.icanhazip.com
echo
```

Line added to test whether now that I have my jenkins build agent source IP, and have allowed ssh from it in my sg configuration (port 22), it will finally work