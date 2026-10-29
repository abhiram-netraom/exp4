For experiment 3, configure jenkins, then go to command prompt:
install cloudflared: winget install --id Cloudflare.cloudflared --source winget

then enter: cloudflared tunnel --url http://locahost:8080

Go to this github repo: webhooks: add webhooks.
type the provided url: https://agent-investments-popular-vid.trycloudflare.com/github-webhook/

select application/json send

save.

Update something in repo and check the build status in jenkins. 
