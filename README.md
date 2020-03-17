### Pull the community Wordpress image:

```
docker pull tutum/wordpress
```

## Create container based off above image:

docker run --name my_wordpress_container -d -p 80:80 tutum/wordpress
