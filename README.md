# L300-Durable

Deploy the Azure Resource

## Scenario
- Durable Function App using Dotnet Isolated .NET 6.0
  - Open the Storage Account

- Notice all of the Execution IDs in the Storage Browser (_Azure Portal_) are the same meaning this is the same **ExecutionId**
  - The **PartitionId** changes
    - Please explain why the **ExecutionId** is the same and why the **PartitionId** changes?
   
- What is the resolution to this problem and how would we apply the fix to this problem?


Deploy the Scenario here: [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmacavall%2FL300-Durable%2Fmaster%2Fazuredeploy.json)


   
First PartitionId <br/>
![image](https://github.com/macavall/L300-Durable/assets/43223084/1c9a471a-5424-4bd6-b53d-2e5c577791ae)

Second PartitionId <br/>
![image](https://github.com/macavall/L300-Durable/assets/43223084/86e6e0ae-50cc-47fc-9c6b-13edc728b02d)

---

If there are issues with accessing the Storage Account Browser due to permissions, ensure that we have the IAM Access set for the following **Role Permissions** to your user email

![image](https://github.com/macavall/L300-Durable/assets/43223084/2401727c-e01f-4dde-98a5-924ecec17933)

![image](https://github.com/macavall/L300-Durable/assets/43223084/8b563c43-142e-43da-b2f8-2737c92501ff)

![image](https://github.com/macavall/L300-Durable/assets/43223084/3e0d4c6c-884c-4557-9144-390b112c83c3)

## Storage Configurations
- Ensure the Storage Configurations blade has the following configurations

![image](https://github.com/macavall/L300-Durable/assets/43223084/50fe915a-aef2-4dec-bcca-43fd4cb747ce)







