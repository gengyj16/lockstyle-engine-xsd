# lockstyle-engine-xsd
Unofficial lockstyle engine xml syntax
[![Netlify Status](https://api.netlify.com/api/v1/badges/99c3ac8d-9b9b-4ef1-87b6-bf1f75b4dfb0/deploy-status)](https://app.netlify.com/sites/lockstyle-xsd/deploys)

## Usage in Visual Studio Code

[中文教程](https://blog.0to1.fun/posts/tools/#%E9%94%81%E5%B1%8F-xsd-%E8%AF%AD%E6%B3%95%E6%A0%A1%E9%AA%8C)

Install [XML Language Support by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) first, then search for "File Associations" in settings and edit `settings.json`.
```json
{
    "xml.fileAssociations": [
        {
            "pattern": "**/*manifest*.xml",
            "systemId": "(URL or local path to manifest.xsd)"
        }
    ],
}
```
