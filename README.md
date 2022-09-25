# selfhost-template
module for selfhost project.

## Quick Start
### Dependencies
#### Mandatory
- [Nginx](https://github.com/AustralEpitech/selfhost-nginx) (Web server)

### Installation
- Stop your [`web server`](https://github.com/AustralEpitech/selfhost-nginx)
- Add appropriate values to `.env`
- Launch the image
```console
docker-compose up -d --build
```
- Wait for the [`install_site`](https://github.com/AustralEpitech/selfhost-install_site) container to be done
- Restart your `web server`
- Open `$DOMAIN` in a `web browser`
