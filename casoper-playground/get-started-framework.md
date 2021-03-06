

# Get started with Visual Studio and .NET Framework for Azure developers

This tutorial will walk you through building and deploying an ASP.NET application to Microsoft Azure using Visual Studio.  When finished, you'll have deployed the application to Azure Web Apps with an Azure SQL Database back end.

## Prerequisites

* [Visual Studio 2017](https://www.visualstudio.com/downloads/) with the **ASP.NET and web development** [workload](/visualstudio/install/modify-visual-studio).   
* A [Microsoft Azure subscription](https://azure.microsoft.com/free/)


## Downloading and running the application

First, get the sample code for this walkthrough and run it locally.

1. Download the sample code from GitHub.
    
    [Sample - Contoso University](https://github.com/CamSoper/contoso-university)
    
    Alternatively, clone it to your local machine with the following [git command-line client](https://git-scm.com/) command:

    ```cmd
    git clone https://github.com/CamSoper/contoso-university
    ```

2. Open **ContosoUniversity.sln** in Visual Studio.

3. Press **CTRL+F5** to restore the project's NuGet packages, build the project, and run it locally.

## Deploying the application to Azure

You've successfully built the application and you've run it locally using IISExpress as its web server and SQL Server Express LocalDB as its database.  Next, you'll deploy your web application to the cloud.

> [!IMPORTANT]
> If this is the first time you've used the Azure tools in Visual Studio, you may be prompted to log in.  Be sure you're signed into Visual Studio with the same account your Azure subscription is associated with.

1. In **Visual Studio Solution Explorer**, right-click on the project name and select **Publish...**

2. Using the **Publish** dialog, select **Microsoft Azure App Service**, select **Create New**, and then click **Publish**

3. In the **Create App Service** dialog, click the **Services** heading on the left side.  Click the plus sign next to **SQL Database**

    ![Adding the SQL Database](media/getting-started-framework/add-sql.png)

4. In the **Configure SQL Database** dialog, next to **SQL Server**, click **New...**.

5. Complete the **Configure SQL Server** dialog as follows:

    * Leave the default **Server Name**.  This will be part of the address for your Azure SQL Database service.
    * Enter an **Administrator Username**.  Common names like *admin*, *sa*, *root*, etc., are not allowed.
    * Enter an **Administrator Password**.
    * Confirm the **Administrator Password**.
    * Click **OK** to return to the **Configure SQL Database** dialog.

6. Using the **Configure SQL Database** dialog, in **Connection String Name**, enter *SchoolContext*.
    
    > [!IMPORTANT]
    > *SchoolContext* should match the name of the connection string in the *web.config* file. Be sure you enter it exactly as written.

7. Click **OK** to return to the **Create App Service** dialog.    

8. Click **Create** to deploy the application.  When deployment is complete, a browser will open with your deployed application.

> [!TIP]
> If you'd like to seed the database with sample data, find the **Settings...** link on the **Publish** dialog.  For the *SchoolContext* database, tick the checkbox that says *Execute Code First Migrations*.

## Next steps

* [Use Azure Active Directory for authentication in an ASP.NET web application](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [Build an Azure Web App using Azure SQL Database](/azure/app-service-web/web-sites-dotnet-get-started)
* [Try a .NET sample application with Azure Storage](/azure/storage/storage-samples-dotnet)


