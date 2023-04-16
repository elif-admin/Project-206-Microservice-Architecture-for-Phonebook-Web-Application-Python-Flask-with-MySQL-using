```bash
helm repo add phonebook-repo1 https://raw.githubusercontent.com/elif-admin/phonebook-repo1/main
helm install phonebook-app phonebook-repo1/phonebook-chart
```

- To use own images execute as below:

```bash
helm install phonebook-app phonebook-repo1 --set webserver_image=<image-name> --set resultserver_image=<image-name>
```