# Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-
This is a web-based Coffee Shop application. The idea for this application arose from the popularity of coffee in offices. Imagine having a centralized store in large offices from which coffee can be delivered online through a centralized application. Employees would save a lot of time, and companies could save money on coffee machines.

📦 Technologies
React Js
Tailwind CSS
Redux
context API
Django
JWT
SQL lite
Docker
GitHub actions
nginx load balancer
Selenium Testing.

✨Features
Here's what you can do with Coffee Shop Web Application:

Sign Up: Users can register on the application using their email, name, and password. To ensure accuracy, users are required to retype their password for verification. Once the user clicks on the sign-up button, the backend generates a hash of the password and stores it in the database.

Login: Users can log in using their credentials, and the verification is checked in the backend using JWT authentication. If the user exists in the database, an authentication token is assigned to the user and stored in the browser's local storage for 90 days. After 90 days, if the user is still logged in, the authentication token is renewed.

products: User can select diffrent products and add to cart.

Profile: Users can access their profile from the frontend by clicking on their name in the navigation bar.

Cart: Within the cart users can increase the quantity of a product or remove it entirely. The cart displays the total price and quantity of items added.

Devops: For version control GitHub is used, and CI/CD pipeline is established using GitHub Actions. Whenever code is pushed to GitHub, the pipeline triggers. Initially, Selenium tests ensure that the Login page loads correctly. Subsequently, an image of the new code is generated and pushed to the local server. Two servers are provisioned, and an NGINX load balancer is employed for efficient management. Watchtower continuously monitors for new images, checking every 3 seconds. The round-robin technique is employed, meaning the first image is directed to the first server, the second to the second server and so on, ensuring load distribution across servers.


💭 How can it be improved?
Add more autherization feature.
Add Payment fuctionality.

🖼️🖼 Screen Shots
![Home_page](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/1ea63ba3-c24c-4b70-82ef-4d0589f859f4)

![coffee_Menu](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/621c5037-fa9c-4e58-85c9-6228aa1990b1)

![Snacks_Menu](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/2490e189-23dc-4e9a-806a-093f44a2f56d)

![Single_Item](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/77581c14-800a-4535-be08-1fc1c0472dd4)

![Cart](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/3fcb00a4-8dd7-478b-a88f-9cf5b06ace4f)

![login](https://github.com/spatil1697/Docker-and-CI-CD-based-web-application-with-a-friendly-and-intuitive-user-interface-/assets/110406683/b719a963-79d6-43d6-ae31-3b8ca7fcdb10)
