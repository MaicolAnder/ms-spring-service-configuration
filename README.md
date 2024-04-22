# ms-spring-service-configuration

### Create JSON File
{
"spring.datasource.username": "",
"spring.datasource.password": ""
}

### Load JSON file into Vault
vault kv put secret/booking-ms @booking-ms.json

### Start  dev serice
vault server --dev --dev-root-token-id="00000000-0000-0000-0000-000000000000"
