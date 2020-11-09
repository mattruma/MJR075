# Introduction

## BlazorApp1

```text
Domain          : DIRECTORY_NAME.onmicrosoft.com
Tenant Id       : TENANT_ID
Client Id       : CLIENT_ID
Instance        : https://DIRECTORY_NAME.b2clogin.com/
Framework       : net5.0
```

```bash
dotnet new blazorwasm -au IndividualB2C --aad-b2c-instance "https://DIRECTORY_NAME.b2clogin.com/" --client-id "CLIENT_ID" --domain "DIRECTORY_NAME.onmicrosoft.com" -o BlazorApp1 -ssp "B2C_1_SignIn" -f net5.0
```

## BlazorApp2

```text
Domain          : DIRECTORY_NAME.onmicrosoft.com
Tenant Id       : TENANT_ID
Client Id       : CLIENT_ID
Instance        : https://DIRECTORY_NAME.b2clogin.com/
Framework       : netcoreapp3.1
```

```bash

dotnet new blazorwasm -au IndividualB2C --aad-b2c-instance "https://DIRECTORY_NAME.b2clogin.com/" --client-id "CLIENT_ID" --domain "DIRECTORY_NAME.onmicrosoft.com" -o BlazorApp2 -ssp "B2C_1_SignIn" -f netcoreapp3.1
```

## Links

* <https://docs.microsoft.com/en-us/aspnet/core/blazor/security/webassembly/standalone-with-azure-active-directory-b2c?view=aspnetcore-5.0>
* <https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications?tabs=app-reg-ga>
* <https://docs.microsoft.com/en-us/aspnet/core/migration/31-to-50?view=aspnetcore-3.1&tabs=visual-studio>
