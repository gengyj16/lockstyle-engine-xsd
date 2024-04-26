# lockstyle-engine-xsd
Unofficial lockstyle engine xml syntax
[![Netlify Status](https://api.netlify.com/api/v1/badges/99c3ac8d-9b9b-4ef1-87b6-bf1f75b4dfb0/deploy-status)](https://app.netlify.com/sites/lockstyle-xsd/deploys)

## Usage in Visual Studio Code

Install [XML Language Support by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) first, then search for "File Associations" in settings and edit `settings.json`.
```json
{
    "xml.fileAssociations": [
        {
            "pattern": "manifest.xml",
            "systemId": "(URL or local path to manifest.xsd)"
        }
    ],
}
```
