
# Boutique Ecommerce API

Boutique Ecommerce, powered by Laravel, offers a comprehensive API system for seamless online shopping experiences. It encompasses vital features including user authentication, product management, order processing, and payment gateways. Designed for scalability, it caters to businesses of all sizes. With intuitive interfaces and a robust backend, it ensures smooth operations for both customers and administrators. Boutique Ecommerce mirrors real-life ecommerce scenarios, empowering businesses to thrive in the competitive online marketplace.




## 👉 TODO 
- [ ]  Replace ***Pusher*** with ***Reverb*** for real-time updates and notifications.
- [ ]  Integrate ***payment gateway*** for seamless transactions.
- [ ]  Refactor code for improved readability and efficiency.
- [ ]  Optimize queries for enhanced performance.


## 🔥 Features

- ***Authentication and Authorization*** using Sanctum for secure dashboard and client-side access.
- ***Implement social login functionality***, enabling users to authenticate via Google and Facebook accounts.
- ***Add categories and subcategories*** with images for organized product management.
- ***Products*** with attributes like name, price, discount, sizes, colors, multiple images and etc..
- Implement product ***rating system*** for user feedback.
- Enable users to write ***reviews*** for products, enhancing customer engagement and trust.
- ***Cart management***: Add, update, and delete items, with checkout functionality (payment gateway not yet implemented).
- ***Flexible shipping***: Adjust shipping prices based on city or country.
- ***Technical Support***: Assistance for clients encountering system issues.
- ***Comprehensive statistics***: Tools for easy system management and analysis.

## 🙏 3rd Parties

- ***Sanctum*** for authentication [https://laravel.com/docs/11.x/sanctum]  
- ***Spatie Laravel Permission*** [https://spatie.be/docs/laravel-permission/v6/introduction]
- ***Pusher*** (or Reverb) for real-time updates and notifications [https://pusher.com]
- ***Spatie Media Library*** [https://spatie.be/docs/laravel-medialibrary/v11/introduction]
- ***Socialite*** for social login functionality (Google - Facebook)  [https://laravel.com/docs/11.x/socialite]



## Installation

How to install Boutique

## 1- Clone the project and install required packages
```bash
  git clone https://github.com/KareemHussen/boutique-ecommerce-api.git
  cd boutique-ecommerce-api
  composer i
  npm i
```
## 2- Fill the missed data in .env which will be find in .env.example

```bash
  PUSHER_APP_ID=
  PUSHER_APP_KEY=
  PUSHER_APP_SECRET=

  GOOGLE_CLIENT_ID=
  GOOGLE_CLIENT_SECRET=

  FACEBOOK_CLIENT_ID=
  FACEBOOK_CLIENT_SECRET=
```
## 3- Now you are ready to go
```bash
  php artisan ser
  npm run dev (For Development)
  npm run build (For Production)
```

    
