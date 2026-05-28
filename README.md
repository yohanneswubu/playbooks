# CIS-460

## Working with this code repository

1. Set up [SSH authentication to GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
2. Clone your fork to your local environment
3. In your local clone, set the upstream repo: 
`git remote add upstream git@github.com:highlinecollege/CIS-460.git`

## Automating deployment
The Cloudformation template in this repo will deploy an EC2 instance and the
resources it needs for networking. The deployment script is in 
[.github/workflows/deploy.yaml](.github/workflows/deploy.yaml). Running this
script requires [adding secrets to GitHub Actions](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions)

