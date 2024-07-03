# ARM-Templates

We can create AZURE Infrastructure using ARM templates.(IAC) <br>
Ways to create Azure Infra using ARM teamplates,
1) Azure DevOps CICD Pipelines
2) Azure Custom Templates Deployment
3) Azure CLI 
4) VS Code 

    ## 1) Azure DevOps CICD Pipelines
   
Initially resource group was empty. 
![image](https://github.com/samirwadkar31/ARM-Templates/assets/74359548/03996c10-bbee-45d4-859f-897b4a36ba6a)

Created Infra Creation Pipeline using ARM templates.
![image](https://github.com/samirwadkar31/ARM-Templates/assets/74359548/17df3cc0-d190-4f2f-a406-b3c1a3a488e7)

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/0e1604ea-19ba-4851-aced-f70fb198139f)


Pipeline completed and successfully provisioned the infrastructure on Azure.
![image](https://github.com/samirwadkar31/ARM-Templates/assets/74359548/8a6b80e6-6082-4f84-a534-2752ac1b2e48)

All resources got reflected on azure resource group
![image](https://github.com/samirwadkar31/ARM-Templates/assets/74359548/809a9cd8-258c-4593-a341-89c6f61a2f2e)


   ## 2) Azure Custom Templates Deployment

Go to Custom Deployment Templates service on Azure

 ![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/7879dc1a-134b-45a0-b13e-53f3434a97e2)

You can use quickstart templates or use your own templates. Here, I have used my own templeates.

 ![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/807f9231-ed9d-4307-bb5b-38f7ae0036da)

Load template.json & Parameter.json files from your local machine 

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/000bfe7d-1b84-4124-b92f-18642b2081e3)

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/eb03e491-511e-4abd-b6bb-ecf0af989bdf)

Click Review & create

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/41d85a0e-83bd-4268-85c1-244c790e18d1)

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/3baedbfb-b689-4cbf-80ea-e0c6d94b7e2c)

After successfuly deployment, you can use your azure resource!!

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/bef31ce1-1d1c-43f9-839f-3a1980ab1a4f)

   ## 3) Azure CLI

Go to your azure tenant. Log in with the subscription where you want to create the resources. Open the cloud shell terminal. Upload your template and parameter.json file

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/381602e4-2d08-4296-9f29-ba868d239f4a)

Aftre executing above azure cli command, your resource will be created in target resource group.

![image](https://github.com/samirwadkar31/AzureInfraCreation_ARM_Templates/assets/74359548/7369bdf1-ab44-4da3-8c78-f986a91c2162)

