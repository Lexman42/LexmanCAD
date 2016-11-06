# About LexmanCAD
LexmanCAD was a weekend project that I started while in school to expand some AutoCAD2013 functionality that wasn't available to vanilla users. Somehow, these tools wound up actually being used on the AutoCAD app store. The basic theme is to solve some of the small annoyances that CAD drafters deal with day in and day out. I've long left the AutoCAD scene for web development, but, I'm hoping that by open sourcing this, the code can live on and be updated for more recent versions of Autodesk products.

## Repo Structure
Each project follows the autoloader template requested by Autodesk to expedite getting code and documentation onto the their app store. Detailed information can be found at [this page](http://usa.autodesk.com/adsk/servlet/item?siteID=123112&id=20143020). The installer can be used if you want to try the app out (this is the same installer that you currently get from the app store). If you are just interested in the code, there are really only two files that matter:
- xxx.lsp - the vlisp code
- xxx.cuix - ribbon bar (for menu entries, icons, and button layout)

## Projects
- **Flatten** - Convert 3D/2D plines into 2D/3D plines - [Github](https://github.com/Lexman42/LexmanCAD-Flatten) / [AppStore](https://apps.autodesk.com/ACD/en/Detail/Index?id=7290135081700538881&appLang=en&os=Win32_64)
- **FindMeXYZ** - Interactively create and position annotations of object properties - [Github](https://github.com/Lexman42/LexmanCAD-FindMeXYZ) / [AppStore](https://apps.autodesk.com/ACD/en/Detail/Index?id=4081568606009015228&appLang=en&os=Win32_64)
- **DWGLogger** - Automate logging of CAD files - [Github](https://github.com/Lexman42/LexmanCAD-DWGLogger) [AppStore](https://apps.autodesk.com/ACD/en/Detail/Index?id=6703266216843000184&appLang=en&os=Win32_64)
- **CADLog** - import/export drawings to csv, leverage excel to proceduraly generate objects - [Github](https://github.com/Lexman42/LexmanCAD-CADLog) / [AppStore](https://apps.autodesk.com/ACD/en/Detail/Index?id=8105152937977072981&appLang=en&os=Win32_64)

## Licensing/Contributing/Maintaining
This project is being open sourced under the MIT license. For the fine print, see the LICENSE file in each repo. You are more than welcome to fork, build off the code, expand it, launch new apps in the app store, etc. If you are interested in maintaining the current LexmanCAD apps that are in the app store (ie. making your updates available to current users) please get in touch, I'm currently not setup for any Autodesk development or QA.
