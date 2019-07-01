# helm-charts
The official Panda Clouds helm chart repository.

### Add a new Chart

```console
$ cd /path/to/proj
$ helm create mychart
$ helm package mychart
$ mv mychart-0.1.0.tgz docs
$ helm repo index docs --url https://technosophos.github.com/tscharts
$ git add -i
$ git commit -av
$ git push origin master
```

From there, I can do a `helm repo add tscharts
https://technosophos.github.com/tscharts`