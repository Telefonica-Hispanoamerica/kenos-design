&nbsp;

| Otros repositorios de Kénos                                               | Descripción                                           |
| :--------------------------------------------------------------- | :---------------------------------------------------- |
| [kenos-web](https://github.com/Telefonica-Hispanoamerica/kenos-web)        | Repositorio con librerías de códigos para Kénos en web basado en React     |
| [kenos-native](https://github.com/Telefonica-Hispanoamerica/kenos-native)       | Repositorio con librerías de códigos para Kénos en nativo basado en React Native     |
| [kenos-icons](https://github.com/Telefonica-Hispanoamerica/kenos-icons) | Repositorio que contiene los iconos utilizados en Kénos|


---

<br/>


# Figma

## ¿Cómo sincronizar los tokens de diseño?

Si desea sincronizar tokens de diseño con archivos Figma, puede usar [Complemento Figma Tokens](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) con la siguiente información.

1. Abra el complemento Figma Tokens, vaya a `Settings` y seleccione `Github` en Token Storage
2. Agregar nuevas credenciales

- **Name:** El nombre de la marca.
- **Personal Access Token:** debes generar un token desde Github. [Lee como hacerlo](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-personal-access-token-classic)
- **Repository:** `Telefonica-Hispanoamerica/kenos-design`
- **Default Branch:** `master`
- **File Path:** `tokens/brandName.json` (ver archivos [here](./tokens/))

![image](https://user-images.githubusercontent.com/6722153/166447592-e3d1b545-199d-4155-9024-2fb88351b444.png) 3. inalmente, vaya a `Tokens`, seleccione  `Global` y `Apply to document` haga clic en `Update`
