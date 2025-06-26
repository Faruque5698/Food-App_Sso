 # 🍔 Food App (SSO Client)

This is a Laravel 12 application that acts as an SSO client, using the central SSO Server for user authentication via OAuth 2.0 and Laravel Passport.  
It provides a seamless login experience by integrating with the shared authentication system used across multiple applications.

This project using:
-Laravel 12 (PHP 8.2+)

### Step 1: Clone the repository

```bash
git clone git@github.com:Faruque5698/Food-App_Sso.git
cd Food-App_Sso
```
### Step 2: Copy the example environment file

```bash
cp .env.example .env
```
### Step 3: Install dependencies

```bash
composer install
```
### Step 4: Generate application key

```bash
php artisan key:generate
```

### Step 5: Configure your database
Edit the `.env` file to set your database connection details:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Your_DB_Name
DB_USERNAME=Your_DB_Username
DB_PASSWORD=Your_DB_Password

SESSION_DRIVER=file

SSO_CLIENT_ID=
SSO_CLIENT_SECRET=
SSO_BASE_URI=
SESSION_DOMAIN=
```

### Step 6: Run migrations

```bash
php artisan migrate
```

### Step 7: Seed the database (optional)
If you want to seed the database with sample data, you can run:

```bash
php artisan db:seed
```

## Contribution

Contributions, feedback, and improvements are highly appreciated. Feel free to fork the repository and submit pull requests.

## Issues & Support

For any issues, bugs, or feature requests, please open an issue in the repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have questions or want to discuss, reach me at:  
**Email:** ashaduzzaman5698@gmail.com  
**GitHub:** [github.com/Faruque5698](https://github.com/Faruque5698)

---

Thank you for reviewing this project. I look forward to your feedback!
