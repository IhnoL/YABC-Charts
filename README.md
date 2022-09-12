# Usage

## Adding a new chart
* package chart via 'helm package >chartname<' and add artifact to this repository
* helm repo index .
* git commit && git push

## Install a chart from this repo
* helm repo add yabccharts https://ihnol.github.io/YABC-Charts/
* helm search repo
* helm install foobar yabccharts/foobar