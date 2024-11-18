# devsecops

```bash
docker run -d -p 9300:80 --name php-apache-container -e TAG="your_tag" -e GIT_COMMIT="your_commit_hash" -e GIT_URL="your_git_url" -v ./volume/database:/var/www/html/database devsecops:1.0.0
```

image from /docs/assets/cicd.png

## CI/CD Pipeline schema

![CI/CD Pipeline](/docs/assets/cicdv2.png)