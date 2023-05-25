# mladenium.github.io

## Documentation

## Resource Naming Convention

When naming resources in the project, we follow the following naming convention to ensure consistency and manageability.

1. **Resource Group:**
   - Naming Format: `<ProjectName>-<Environment>-<ResourceType>-rg`
   - Example: `myapp-dev-rg`

2. **Virtual Network:**
   - Naming Format: `<ProjectName>-<Environment>-vnet`
   - Example: `myapp-dev-vnet`

3. **Subnet:**
   - Naming Format: `<ProjectName>-<Environment>-<SubnetName>-subnet`
   - Example: `myapp-dev-web-subnet`

4. **Virtual Machine:**
   - Naming Format: `<ProjectName>-<Environment>-<Role>-vm`
   - Example: `myapp-dev-web-vm`

5. **Database:**
   - Naming Format: `<ProjectName>-<Environment>-<DatabaseType>-db`
   - Example: `myapp-dev-mysql-db`

6. **Storage Account:**
   - Naming Format: `<ProjectName><Environment><AccountType>sa`
   - Example: `myappdevstorageaccount`

7. **Key Vault:**
   - Naming Format: `<ProjectName>-<Environment>-kv`
   - Example: `myapp-dev-kv`

8. **Application Insights:**
   - Naming Format: `<ProjectName>-<Environment>-ai`
   - Example: `myapp-dev-ai`

Please ensure to adhere to this naming convention when creating and managing resources in the project. Consistent naming helps with easy identification, maintenance, and troubleshooting of resources.

> Note: Replace `<ProjectName>`, `<Environment>`, `<ResourceType>`, `<SubnetName>`, `<Role>`, `<DatabaseType>`, and `<AccountType>` with the appropriate values relevant to your project.

