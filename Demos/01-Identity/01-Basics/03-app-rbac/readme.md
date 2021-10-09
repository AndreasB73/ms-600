# App Registration Process and Manifest

    -   Explain appRoles User | Application
    -   Mention Claims (context.User.HasClaim(ClaimTypes.Role, "Admin") and Azure SecGroups

    ```json
    "appRoles": [
    {
    "allowedMemberTypes": [ "User" ],
    "description": "Administrator role for Product Catalog web application.",
    "displayName": "ProductAdministrators",
    "id": "98ce9517-557f-4ac5-b827-f18d948ee552",
    "isEnabled": true,
    "lang": null,
    "origin": "Application",
    "value": "ProductAdministrators"
    },
    ```
