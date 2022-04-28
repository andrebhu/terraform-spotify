# Terraform Spotify

Create a playlist on Spotify by writing it as a Terraform configuration.

Follow along with the [tutorial](https://learn.hashicorp.com/tutorials/terraform/spotify-playlist)


```
docker run --rm -it -p 27228:27228 --env-file ./.env ghcr.io/conradludgate/spotify-auth-proxy
```

```
terraform init
terraform apply
```

