# ms-spring-service-configuration

### Create JSON File
{
"spring.datasource.username": "",
"spring.datasource.password": ""
}

### Load JSON file into Vault
vault kv put secret/booking-ms @booking-ms.json
