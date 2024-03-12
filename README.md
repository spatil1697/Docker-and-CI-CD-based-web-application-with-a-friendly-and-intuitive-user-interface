This is a web-based Coffee Shop application designed to streamline the coffee ordering process in offices. The idea stemmed from the widespread popularity of coffee in workplace settings. Imagine having a centralized store within large offices where employees can order coffee online through a user-friendly application. This not only saves time for employees but also helps companies save on expenses associated with coffee machines.

📦 ## Technologies

React Js
Tailwind CSS
Redux
Context API
Django
JWT
SQLite
Docker
GitHub Actions
NGINX load balancer
Selenium Testing.

✨ ## Features
Here's what you can do with the Coffee Shop Web Application:

Sign Up:
Users can register on the application using their email, name, and password. Password verification is required by retyping it for accuracy. Upon clicking the sign-up button, the backend generates a password hash and stores it in the database.

Login:
Users can log in using their credentials, with backend verification using JWT authentication. Upon successful verification, an authentication token is assigned to the user and stored in the browser's local storage for 90 days. Token renewal occurs automatically after 90 days if the user remains logged in.

Products:
Users can browse and select different products to add to their cart.

Profile:
Users can access their profile by clicking on their name in the navigation bar, allowing them to view and update their information.

Cart:
Within the cart, users can adjust the quantity of selected items or remove them entirely. The cart dynamically updates to display the total price and quantity of items added.

DevOps:
For version control, GitHub is utilized, and a CI/CD pipeline is established using GitHub Actions. Upon code push, the pipeline triggers, initiating Selenium tests to ensure the correct loading of the Login page. Subsequently, a new code image is generated and deployed to the local server. Two servers are deployed, managed by an NGINX load balancer for optimal load distribution. Watchtower continually monitors for new images, utilizing round-robin technique for load balancing across servers.

💭 ## How can it be improved?

Add additional authorization features.
Implement payment functionality.

🖼️ ## Screenshots

![Home_page](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/1ea63ba3-c24c-4b70-82ef-4d0589f859f4)

![coffee_Menu](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/621c5037-fa9c-4e58-85c9-6228aa1990b1)

![Snacks_Menu](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/2490e189-23dc-4e9a-806a-093f44a2f56d)

![Single_Item](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/77581c14-800a-4535-be08-1fc1c0472dd4)

![Cart](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/3fcb00a4-8dd7-478b-a88f-9cf5b06ace4f)

![login](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/b719a963-79d6-43d6-ae31-3b8ca7fcdb10)
