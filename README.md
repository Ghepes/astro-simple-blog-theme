
[![Netlify Status](https://api.netlify.com/api/v1/badges/6a2826b4-fed2-4d02-8749-75046510c48f/deploy-status)](https://app.netlify.com/sites/start-blog-theme/deploys)  [![Run Build](https://github.com/Ghepes/astro-simple-blog-theme/actions/workflows/build-test.yml/badge.svg)](https://github.com/Ghepes/astro-simple-blog-theme/actions/workflows/build-test.yml)

# Starter simple wromo theme with Netlify end Astro


![Video](https://github.com/user-attachments/assets/50e794be-007a-47fa-b7bf-5e7c16875232)
![screenshot starter-wromo-theme](https://github.com/user-attachments/assets/8b829f8e-29ad-4d37-80da-7e8eab106e0f)


## Demo

[View Creek Theme on Netlify](https://main--start-blog-theme.netlify.app/)


## Features

- based on [bootstrap](https://getbootstrap.com/)
- pagination
- tags
- categories

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
|:----------------  |:-------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 👀 Want to learn more?

Feel free to check [our documentation](https://github.com/Ghepes/astro-simple-blog-theme) or jump into our [Discord server](https://astro.build/chat).

## Site Configuration

```cjs
  // src/config.cjs
  // Web site base url
  siteBaseUrl: '/',
  // Web site language
  siteLanguage: "en",
  //Web site title. It is visible in sidebar and browser
  siteTitle: "Wromo Themes with Astro end Netlify",
  //Web site desciption. It is visible in sidebar. Also added head meta data.
  siteDescription: "<your site description>",
  //Override footer text.
  siteCopyright: "© 2020 copyright text.",
  //Site global date format. [dayjs](https://day.js.org/docs/en/display/format)
  dateFormat: "MMMM D, YYYY",
  // Pagination number of posts per page
  paginate: 6,
  //Customize the menu
  memus:[
    {
      identifier: "about",
      name: "About",
      url: "/about/",
    }
  ],
```
https://buymeacoffee.com/infowromon
## Support

If this template helped you, buy me a coffee.

<a href="https://www.buymeacoffee.com/infowromon" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## License

This template is [MIT](LICENSE) licensed.


