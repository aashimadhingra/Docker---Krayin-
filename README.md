# Docker-Krayin


https://github.com/user-attachments/assets/e68d7a4b-9393-44bb-b6c1-989f0ef84447



# Krayin CRM  

**Krayin** is an open-source Laravel-based CRM platform designed to help businesses manage interactions with customers and potential customers efficiently.  

## Features  
- Customer management  
- Lead management  
- Opportunity tracking  
- Easy-to-use interface  
- Open-source and customizable  

## Requirements  

To install and run Krayin, ensure your server meets the following requirements:  

- **Server:** Apache 2 or NGINX  
- **RAM:** 4GB or higher  
- **Node:** 8.11.3 LTS or higher  
- **PHP:** 7.3.0 or higher  
- **Composer:** 1.6.5 or higher  

## Installation  

Follow these steps to install Krayin CRM:  

1. **Clone the Repository**  
   Clone this repository to your local environment or server.  

   ```bash  
   git clone <repository_url>  
   cd <repository_directory>

   
2.**Install Dependencies**
Install Krayin using Composer:

composer create-project krayin/laravel-crm  
3.**Run the Installation Script**

Execute the following command to complete the installation:
php artisan krayin-crm:install  

4.**Configure Your Environment**
Update the .env file with your database and application settings.

5.**Start the Application**
Start the local development server:
php artisan serve  

