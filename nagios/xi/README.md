## Nagios XI Container v5.5.6
```
docker pull lerndevops/nagios:xi5.5.6
```
```
docker run -d -p 80:80 --name nagiosxi lerndevops/nagios:xi5.5.6
```

## Nagios XI Container v5.4

```
docker pull lerndevops/nagios:xi5.4
```
```
docker run -d -p 80:80 -p 5666:5666 -p 5667:5667 --name nagiosxi lerndevops/nagios:xi5.4
```
```
80 : apache
5666 : NRPE
5667 : NSCA
```
