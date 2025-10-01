# Microwavin Manoa
Many college students have limited kitchen resources, limited cooking skills, limited time, limited access to grocery stores, and no access to creative recipes that respect these constraints. As a result, college students spend money to eat out, or eat non-healthy foods at fast food places or through vending machines.

Microwavin Manoa creates a way for students (on-campus or off) to learn and share recipes that:
- Can be made using minimal kitchen facilities (at a minimum, a toaster oven, or a microwave!).
- Can be made out of ingredients that are available within walking distance of UH.
- Can be filtered via dietary restrictions (gluten-free, vegan, etc).
- Have an estimated cost per serving.
- Has an estimated number of servings per recipe.
- Has an estimate of how long it takes to make.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
You'll need the following installed:
- npm 
- [Node.js](https://nodejs.org/en)
- [Meteor](https://v2-docs.meteor.com/install.html) 

### Installation
Fork the Microwavin Manoa repo:

```
git clone https://github.com/YOUR-USERNAME/microwavin-manoa.git
cd microwavin-manoa/app
```

Then, cd into the app directory and install the required libraries with:

```
$ meteor npm install
```

Once the libraries are installed, you can run the application by invoking:

```
$ meteor npm run start
```

### Viewing the running app
The template application will appear at http://localhost:3000. You can login using the credentials in settings.development.json, or else register a new account.

## Running Tests 

### End to End Tests
Microwavin Manoa includes end-to-end tests to ensure seamless user experiences. Run these tests using:

```
npx playwright test
```

### Coding Style Tests
To maintain coding consistency, we enforce ESLint rules. Run the linter with:

```
meteor npm run lint
```

## Deployment
Deploy with [Meteor Cloud](https://cloud-old.meteor.com/). 

Install Meteor Cloud:

```
meteor add-platform
```

Log in:

```
meteor login
```

Deploy the app:

```
meteor deploy your-app.meteorapp.com --settings settings.production.json
```

Configure custom domain and SSL in the Meteor Cloud dashboard.

### Built With
- [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
- [React](https://react.dev/) for component-based UI implementation and routing.
- [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
- [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Get in Touch
Join our [Discord](https://discord.com/) to stay updated and contact the main contributors!

## License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/carolwong492/MicrowavinManoa/blob/main/LICENSE) file for details
