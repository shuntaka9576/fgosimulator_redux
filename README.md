# fgosimulator_redux
## Installation
```
npm install
npm run prebundle
npm run build
npm start
```
## Demo Play
![fgogif1](https://user-images.githubusercontent.com/12817245/33017538-0a7ea07a-ce36-11e7-8ccc-f3ca21758ba0.gif)

## Folder Structure
```
fgosimulator_redux
    │  .babelrc
    │  .eslintrc.js
    │  index.html
    │  nedb.db
    │  package.json
    │  README.md
    │  webpack.config.js
    │
    ├─icon
    │  └─i
    │      ├─icon
    │      │      item_100.jpg
    │      │      ...
    │      │      item_900.jpg
    │      │
    │      ├─icon_class
    │      │      class_1.png
    │      │      ...
    │      │      class_13.png
    │      │
    │      ├─icon_servants
    │      │      1.jpg
    │      │      ...
    │      │      99.jpg
    │      │
    │      └─icon_skills
    │              101.jpg
    │              ...
    │              906.jpg
    │
    └─src
        ├─main
        │      createWindow.js
        │      index.js
        │      setAppMenu.js
        │
        └─renderer
            │  app.jsx
            │
            ├─actions
            │      index.js
            │
            ├─components
            │  ├─MaterialPageComponents
            │  │      MaterialComponent.jsx
            │  │
            │  ├─ServantPageComponents
            │  │      ServantClassComponents.jsx
            │  │
            │  └─SkilPageComponents
            │          SkillPageComponentsTable.jsx
            │          SkillPageComponentsTableRow.jsx
            │
            ├─containers
            │      AnalyticsPage.jsx
            │      MainPage.jsx
            │      MaterialPage.jsx
            │      ServantPage.jsx
            │      SkillPage.jsx
            │      SkillPage2.jsx
            │
            ├─lib
            │  ├─fgo
            │  │      materialdata.min.js
            │  │      materialdatautills.js
            │  │
            │  ├─highcharts
            │  │      analyticschart.js
            │  │
            │  └─nedb
            │          nedb.operation.js
            │
            └─reducers
                    index.js

```

## Other


