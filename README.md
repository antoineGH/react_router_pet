# React Quizz

# Table of contents

1. [Project Goals](#description)
2. [Technologies](#tech)
3. [System Features](#sys-features)
4. [Installation instructions](#installation)
5. [Screenshots](#screenshots)

## 1. Project description<a name="description"></a>

In this project, you will have the opportunity to practice using React Router to add client-side routing to a React Application. Specifically, you will be building a pet adoption website that allows users to view all the adoptable pets of a particular species and view the profiles of specific adoptable pets.

## 2. Technologies<a name="tech"></a>

This system is provisioned to be built in JavaScript using React library which is highly flexible.

The browser will be in charge of rendering this application in its final form, HTML. Some of the logic involved in creating the web page, especially the one in charge of dealing with presentation logic is handled on the client-side.

List of frontend dependencies and version used:

- react: v17.0.2,
- react-dom: v17.0.2,
- react-router-dom: v5.3.0,
- react-scripts: v4.0.3,
- web-vitals: v1.0.1

## 3. System Features<a name="sys-features"></a>

- The HomePage component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.
- The PetDetailsPage page displays when the browser’s current URL includes a specific pet’s id.
- The PetDetailsPage displays data for the correct pet based on the id in the URL parameters’ values.
- When the user searches for a pet in the search bar, they are redirected to the SearchPage, which uses the query parameter called query to filter pets by name.
- When a user clicks a pet whose details are not available, they are redirected to a PetNotFoundPage.
- From the PetNotFound page, users can click “Go Back” button that will take them to page they were previously on.

## 4. Installation instructions<a name="installation"></a>

Versions:

- Node: 14.15.1
- Npm: 6.14.8
- React: 17.0.1

Download code from Github:

```shell
git clone https://github.com/antoineratat/react_router_pet.git
```

Navigate to project directory.

```shell
cd /react-router_pet
```

Install node modules.

```shell
npm install
```

Run the app in development mode. Open http://localhost:3000 to view it in the browser.

```shell
npm start
```

## 5. Screenshots<a name="screenshots"></a>

App ![Components Screenshot](https://github.com/antoineratat/github_docs/blob/main/react_quizz/quizz_1.PNG?raw=true)
