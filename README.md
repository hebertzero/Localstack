# Localstack

### Primeiros passos
Para executarmos a aplicação, primeiro precisamos executar o `docker compose`.

Para executar, utilize o comando abaixo:
```bash
docker compose up
```

### Terraform
Para executar a criação do `sns` precisamos executar o arquivo do terraform chamado `main.tf`.
Para executar a criação da fila:
```bash
terraform apply 'main.tfplan'
```

Para destruir o objeto provisionado:
```bash
terraform destroy
```
