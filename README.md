# githooks
Simple repo to test some git hooks

## installation
Drop the hook file in the following directory and make sure it is executable:
{repo}/.git/hooks

It will be automatically called by git before the given operation.



## pre-push
Prevent pushes to master or development

Example Output of pre-push:
    Prevented push to protected branch "master" by using a pre-push hook.
    You should submit a pull request on Github instead.
     
    If you want to skip this check, invoke again with --no-verify 
     
    error: failed to push some refs to 'git@github.com:danieldbower/githooks.git'


