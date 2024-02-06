# PixInvent Assets

Use this repo for PixInvent products assets (Global CDN)

> 💡 Use this repo as single source of truth for the template assets. 
> 
> As a result, if the design team changes the image, it will be updated automatically in all the places where it is used, such as the readme file, landing page image, etc..

## Folder Structure

```
template-name(vuexy)
├── landing-page
├── admin-template
│   ├── banner
│   ├── item-page
│   ├── logo
│   ├── preview-image
├── figma-ui-kit
```
Table of contents:
| Folder        | Purpose                                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------------------- |
| landing-page  | Folder contains images for **landing page** purpose. ex: demos, apps, pages etc..                       |
| banner        | Folder contains images for **item-page banner**, can be used in repo readme file                        |
| logo          | Folder contains template logo, can be used in repo readme file                                          |
| preview-image | Folder contains template Folder contains template **preview-image** for the marketplace preview purpose |
|               |                                                                                                         |
## Usage

To use assets over cdn:
```
https://cdn.pixinvent.com/pi-assets/path/to/file.extension
```

Usage examples:

**Logo**

```
https://cdn.pixinvent.com/pi-assets/vuexy/admin-template/logo/logo.png
```

**Banner**

```
https://cdn.pixinvent.com/pi-assets/vuexy/admin-template/banner/banner.png
```

**Landing-page**

```
https://cdn.pixinvent.com/pi-assets/vuexy/landing-page/app-academy.png
```

<details>
  <summary>jsdelivr (Deprecated)</summary>
To use assets over cdn:

```
https://cdn.jsdelivr.net/gh/<owner>/<repo>/path/to/file.extension
```

Usage examples:

**Logo**

```
https://cdn.jsdelivr.net/gh/pixinvent/pi-assets/vuexy/admin-template/logo/logo.png
```

**Banner**

```
https://cdn.jsdelivr.net/gh/pixinvent/pi-assets/vuexy/admin-template/banner/banner.png
```

**Landing-page**

```
https://cdn.jsdelivr.net/gh/pixinvent/pi-assets/vuexy/landing-page/app-academy.png
```
</details>
