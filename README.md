# MPT-BSUIR-Frontend
Demo project on the subject of modern programming technologies (front-end)
# Premium Auto Rental

## *authors: Konstantin Svirski(BE), Nikita Bogdanov(FE), Anton Shukanau(QA)*

## Description

The application is designed to automate car rental. An authorized user orders a car and pays for it.
The administrator confirms the reservation or refuses, indicating the reason for the refusal. At the end of the lease,
the user returns the car back and can leave a comment on the car. The administrator confirms the delivery of the car.
If there are problems with the car, then he writes out a fine that the user must pay.

## Actors

* Guest (not authorized user)
* User (authorized user)
* Admin (user with role of administrator)

### Guest functionality:

* Signing in
* Signing up
* View cars and make selection of them in different ways
* View detail description of car

### Users functionality:

* All guest's abilities
* Signing out
* View his/her page with personal information
* Edit personal information
* Rent car
* View orders and inforamtion of them
* Release rent with comment to car
* Pay a fine if with car was problems

### Admin functionality:

* All guest's abilities
* Signing out
* View his/her page with personal information
* Edit personal information
* View all users
* Block/unblock user
* Appoint administrator
* View information of specific user
* View all users orders
* View orders of specific user
* Apply rent of user
* Deny in rent with indicating the reason
* Approve release of rent car
* Issue a fine for a specific order
* Add car in list

## BE-side developing:

* Programming Language: *Java 11*
* Framework: *Spring boot 2.3.9(RELEASE)*
* ORM: *Hibernate, Spring Data*
* Database: *Amazon RDS*
* Web Server: *Apache Tomcat 9*
* Build tool: *Gradle 6.8*
* Security: *Spring Security, OAuth 2.0, OIDC*
* Testing utilities: *JUnit 5, Mockito*
* Metrics:
** Static analyzer of code: *SonarQube*
** Code coverage: *JaCoCo*

## FE-side developing:

* Programming Language: *TypeScript 4.4*
* Framework: *React 17.0.2*
* Data Flow: *Redux Toolkit*
* UI Framework: *Ant Design, Tailwind css, React-reveal*
* Athorization: *OAuth 2.0*
* Testing utilities: *Jest, Mocha*

## QA-side developing:

## Integreation flow:

* CI/CD: *Jenkins*
* Virtual cloud: *Amazon EC2*

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
