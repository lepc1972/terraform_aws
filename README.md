# # Terraform AWS Infrastructure

Este repositorio contiene configuraciones de Terraform para desplegar infraestructura en AWS, incluyendo la creación de una VPC y una instancia EC2.

## Estructura del repositorio

- **`main.tf`**: Define los recursos principales de AWS, como la instancia EC2 y la VPC.
- **`providers.tf`**: Configura los proveedores necesarios, en este caso, AWS.
- **`datasources.tf`**: Contiene definiciones de fuentes de datos utilizadas en la configuración.
- **`mac-ssh-config.tpl`** y **`userdata.tpl`**: Plantillas utilizadas para la configuración de la instancia EC2.
- **`.gitignore`**: Especifica los archivos y directorios que deben ser ignorados por Git, como los archivos de estado de Terraform y directorios temporales.

## Requisitos previos

- **Terraform**: Asegúrate de tener instalada la versión 0.14 o superior. Puedes descargarla desde el [sitio oficial de Terraform](https://www.terraform.io/downloads).
- **Credenciales de AWS**: Configura tus credenciales de AWS en tu entorno local. Puedes hacerlo mediante variables de entorno o utilizando el archivo `~/.aws/credentials`.

## Uso

1. **Inicializa el entorno de Terraform**:

   ```bash
   terraform init

   ```

   ```bash
   terraform plan

   ```

   ```bash
   terraform apply

   ```

2. **Para limpiar o eliminar todos los recursos**

    ```bash
   terraform destroy

   ```



