# Ribari.me demonstration

This is a **Statamic** project built on **Laravel** for demonstration purposes. Follow the instructions below to set up and run the project locally.  

## Installation  

```sh
# 1. Clone the Repository  
git clone https://github.com/purgea/ribari.me
cd ribari.me 

# 2. Install PHP Dependencies  
composer install  

# 3. Configure Environment  
cp .env.example .env  
php artisan key:generate  

# 4. Run Migrations  
php artisan migrate  

# 5. Set Up Statamic  
php artisan statamic:install  #not entirely sure about the necessity of this command
php please make:user  

# 6. Install Frontend Dependencies  
npm install  

# 7. Compile Assets  
npm run dev
