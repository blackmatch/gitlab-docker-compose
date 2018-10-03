# gitlab-docker-compose

Deploy gitlab-ce with docker compose.

## usage

* copy `docker-compose.yml` to your server.
* setup `external_url` 、 `gitlab_rails['smtp_user_name']` 、 `gitlab_rails['smtp_password']` with your own setting.
* run container with `docker-compose up -d`.
* visit your server ip or `external_url`  to your gitlab platform.