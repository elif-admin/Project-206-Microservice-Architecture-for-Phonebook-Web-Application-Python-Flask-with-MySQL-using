```bash
helm repo add phonebook-repo https://raw.githubusercontent.com/james-clarusway/phonebook-repo/main
helm install phonebook-app phonebook-repo/phonebook-chart
```

- To use own images execute as below:

```bash
helm install phonebook-app phonebook-repo --set webserver_image=<image-name> --set resultserver_image=<image-name>
```