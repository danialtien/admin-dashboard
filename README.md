# Step by step building build Admin Dashboard

#### Setup new project
- npx create-react-app ./
- npm i

#### Intall frameworks by addting to package.json [Link]()
- "dependencies": {
    "@syncfusion/ej2": "^19.4.48",
    "@syncfusion/ej2-react-calendars": "^19.4.48",
    "@syncfusion/ej2-react-charts": "^19.4.50",
    "@syncfusion/ej2-react-dropdowns": "^19.4.52",
    "@syncfusion/ej2-react-grids": "^19.4.50",
    "@syncfusion/ej2-react-inputs": "^19.4.52",
    "@syncfusion/ej2-react-kanban": "^19.4.48",
    "@syncfusion/ej2-react-popups": "^19.4.52",
    "@syncfusion/ej2-react-richtexteditor": "^19.4.50",
    "@syncfusion/ej2-react-schedule": "^19.4.50",
    "@testing-library/jest-dom": "^5.17.0",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-icons": "^4.12.0",
    "react-router-dom": "^6.20.1",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  },

- "devDependencies": {
    "autoprefixer": "^10.4.2",
    "postcss": "^8.4.6",
    "tailwindcss": "^3.0.19"
  }

#### Add config file
##### craco.config.js file [Link]()
##### tailwind.config.js [Link]()
##### Use tailwind by adding to [index.css]() and import it to index.js


#### Setup file structure
```
├───public
└───src
    ├───components
    │   └───Charts
    ├───contexts
    ├───data
    └───pages
        └───Charts
```
#### Create jsx file
- Create all jsx function components
- Create index.jsx file contain all exports of those components

#### Define route in App.js
#### Define ContextProvider in index.js
