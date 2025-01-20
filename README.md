<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> A smart pharmaceutical vending machine that aims to address the unavailability of basic pharmaceuticals and ensure their accessibility in situations where pharmacies are closed or unavailable. By integrating microcontrollers, actuators, and advanced technologies, we automate the dispensing and payment processes to provide convenience and reliability.
>
> Our solution features an interactive robotic system and an AI-trained model for pattern recognition across various areas. Additionally, we offer a user-friendly interface that helps users locate nearby vending machines and enables real-time communication with the system. This approach streamlines access to essential pharmaceuticals and enhances the overall user experience.

### User Stories

#### Customer
- As a Customer, I want to locate nearby vending machines, so I can quickly access essential pharmaceuticals when pharmacies are closed.
- As a Customer, I want to browse available medicines and their details, so I can find and select the medication I need.
- As a Customer, I want the system to guide me to the machine and allow me to shop and dispense medicantions of my choice.

#### Admin 
- As an admin, I want to manage and monitor the stock levels in vending machines, so I can restock them promptly to avoid shortages.
- As an admin, I want to review and analyze sales data, so I can identify trends and improve vending machine performance.
- As an admin, I want the vending machine inventory to be updated in real time and reflected accurately to users, ensuring credibility and trust in the system.
<br><br>
<!-- Tech stack -->
<img src="./readme/title3.svg"/>

###  PharmaVend is -built using the following technologies:

- This project uses the [Flutter app development framework](https://flutter.dev/). Flutter is a cross-platform hybrid app development platform which allows us to use a single codebase for apps on mobile, desktop, and the web.
- For backend development, the app uses [Laravel](https://laravel.com/), a PHP-based framework known for its scalability and robust API handling capabilities.
- The user and admin panel websites are built using [React](https://react.dev/), a front-end library that delivers a dynamic and interactive interface.
-The application enhances its functionality with several Google APIs, each serving a unique purpose:
- **Maps JavaScript API**: Provides interactive maps and location features on the application and admin panels. [Learn more](https://developers.google.com/maps/documentation/javascript/overview).
- **Geolocation API**: Allows the app to retrieve the current location of the user by accepting an HTTPS request with the cell tower and WiFi access points that a mobile client can detect. [Learn more](https://developers.google.com/maps/documentation/geolocation/overview).
- **Distance Matrix API**: Calculates travel distance and time for a matrix of origins and destinations, useful for managing delivery times and logistics. [Learn more](https://developers.google.com/maps/documentation/distance-matrix/overview).
- **Directions API**: Supplies route directions between multiple locations which are used to plot navigational routes on the map. [Learn more](https://developers.google.com/maps/documentation/directions/overview).
- **Reverse Geocoding API**: Converts geographic coordinates into a human-readable address. [Learn more](https://developers.google.com/maps/documentation/geocoding/overview).
- The IoT integration is powered by the [Arduino Platform](https://www.arduino.cc/), utilizing the [ESP32 microcontroller](https://www.espressif.com/en/products/socs/esp32) to control actuators for precise and reliable dispensing of products.

<br><br>
<!-- UI UX -->
<img src="./readme/title4.svg"/>


> We designed PharmaVend using wireframes and mockups, iterating on the design until we reached the ideal layout for easy navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/7ouYeUwMOHD4Q3yAhSmUx7/Final-project?node-id=0-1&p=f&t=3UV9S1T6sdou9NPQ-0)

### Mockups

| Home Screen                | Map Screen               | Checkout Screen              |
|-------------------------------|--------------------------|--------------------------|
| ![Home  Screen](./readme/demo/home.png) | ![Map](./readme/demo/map.png) | ![Home](./readme/demo/checkout.png) |
<!-- 
| Details Screen                | Cart Screen             | Checkout Screen           |
|-------------------------------|--------------------------|--------------------------|
| ![Details](./readme/demo/details.png) | ![Cart](./readme/demo/cart.png) | ![Checkout](./readme/demo/checkout.png) |

| History Screen                | Dispense Screen          | Landing #2               |
|-------------------------------|--------------------------|--------------------------|
| ![History](./readme/demo/history.png) | ![Dispense](./readme/demo/dispense.png) | ![Landing2](./readme/demo/landing2.png) | -->

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

###  Architecting Data Excellence: Innovative Database Design Strategies:

- Insert ER Diagram here


<p align="center">
  <img src="./readme/demo/DB-schema.png" alt="ER Diagram">
</p>

<br><br>


<!-- Implementation -->
<img src="./readme/title6.svg"/>


### User Screens (Mobile)
#### Visual Overview
| Login Screen                | Register Screen               | Landing Screen              |
|-------------------------------|--------------------------|--------------------------|
| ![Login](./readme/demo/login.png) | ![Register](./readme/demo/signup.png) | ![Landing](./readme/demo/landing.png) |

| Other Landing Screen                | Home Screen             | Map Screen           |
|-------------------------------|--------------------------|--------------------------|
| ![Other Landing](./readme/demo/landing2.png) | ![Home](./readme/demo/home.png) | ![Map](./readme/demo/map.png) |

| Product Detail Screen                | Cart Display Screen          | Checkout Screen               |
|-------------------------------|--------------------------|--------------------------|
| ![Product Detail](./readme/demo/details.png) | ![Cart](./readme/demo/cart.png) | ![Checkout](./readme/demo/checkout.png) |

| User History Screen                | Product Dispense Screen          | Notification Screen               |
|-------------------------------|--------------------------|--------------------------|
| ![History](./readme/demo/history.png) | ![Dispense](./readme/demo/dispense.png) | ![Notification](./readme/demo/notification.png) |

#### Interactive Walkthrough
| Sign Up Demo                | Google Signin Demo               | Find Closest Machine               | 
|-------------------------------|--------------------------|--------------------------|
| ![Sign up](./readme/demo/signup.gif) | ![Google](./readme/demo/googlesignin.gif) | ![Closest](./readme/demo/closest.gif) | 

| Checkout Demo                | Search medicine Demo               | Notification Update               | 
|-------------------------------|--------------------------|--------------------------|
| ![Checkout](./readme/demo/paymedicine.gif) | ![Search](./readme/demo/search.gif) | ![Notification](./readme/demo/notification.gif) | 

| Map Navigation Demo                | 
|-------------------------------|
| ![Checkout](./readme/demo/maps.gif) | 

### Admin Screens (Web)
#### Visual Overview
| Dashboard Screen #1  | Dashboard Screen #2 |
| ---| ---|
| ![Dashboard Screen #1](./readme/demo/dashboard1.png) | ![Dashboard Screen #2](./readme/demo/dashboard2.png) |

| Orders Screen #1  | Orders Screen #2 |
| ---| ---|
| ![Orders Screen #1](./readme/demo/orders1.png) | ![Orders Screen #2](./readme/demo/orders2.png) |

| Inventory Screen #1  | Inventory Screen #2 |
| ---| ---|
| ![Inventory Screen #1](./readme/demo/inventory1.png) | ![Inventory Screen #2](./readme/demo/inventory2.png) |

| Machines Screen  | Products Screen  |
| ---| ---|
| ![Machines Screen](./readme/demo/machines.png) | ![Products Screen](./readme/demo/products.png) |

| Customers Screen #1  | Customers Screen #2 |
| ---| ---|
| ![Customers Screen #1](./readme/demo/customers1.png) | ![Customers Screen #2](./readme/demo/customers2.png) |

#### Interactive Walkthrough

Machine Navigation 

| ![Admin #1](./readme/demo/admin1.gif) |

Machine Deployment

| ![Admin #2](./readme/demo/admin2.gif) |
<br><br>


<!-- Prompt Engineering -->
<img src="./readme/title7.svg"/>

###  Mastering AI Interaction: Unveiling the Power of Prompt Engineering:

- This project uses advanced prompt engineering techniques to optimize the interaction with natural language processing models. By skillfully crafting input instructions, we tailor the behavior of the models to achieve precise and efficient language understanding and generation for various tasks and preferences.

<br><br>

<!-- AWS Deployment -->
<img src="./readme/title8.svg"/>

###  Efficient AI Deployment: Unleashing the Potential with AWS Integration:

- This project leverages AWS deployment strategies to seamlessly integrate and deploy natural language processing models. With a focus on scalability, reliability, and performance, we ensure that AI applications powered by these models deliver robust and responsive solutions for diverse use cases.

<br><br>

<!-- Unit Testing -->
<img src="./readme/title9.svg"/>

###  Precision in Development: Harnessing the Power of Unit Testing:

- This project employs rigorous unit testing methodologies to ensure the reliability and accuracy of code components. By systematically evaluating individual units of the software, we guarantee a robust foundation, identifying and addressing potential issues early in the development process.

<br><br>


<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up Coffee Express locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [example](https://example.com)
2. Clone the repo
   git clone [github](https://github.com/your_username_/Project-Name.git)
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

Now, you should be able to run Coffee Express locally and explore its features.