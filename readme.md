#Laravel-Quiz-App-Project: Laravel based quiz system

It is a demo project for demonstrating what can be:


- __Email__: admin@admin.com
- __Pass__: password

![LaraQuiz screenshot](https://quickadminpanel.com/assets/pages/demos/demo-laraquiz-01.png)

![LaraQuiz screenshot 2](https://quickadminpanel.com/assets/pages/demos/demo-laraquiz-02.png)

## How to use

#### Using Docker
- Clone the repository with __git clone__
- Run __make setup__
- Access via __http://localhost:8888__

#### Without Docker
- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- Now you can login as admin: launch the main URL and login with default credentials __admin@admin.com__ - __password__
- Fill in the database with topics, questions and options
- For social login - fill in the credentials of your social apps in .env file
- That's it - allow people to register and take quizzes!

## License

Basically, feel free to use and re-use any way you want.

---

https://samsonnegash.cf/

## More from our LaravelDaily Team

- Check out our adminpanel generator [QuickAdminPanel](https://quickadminpanel.com) 
- Read our [Blog with Laravel Tutorials](https://laraveldaily.com)
- FREE E-book: [50 Laravel Quick Tips (and counting)](https://laraveldaily.com/free-e-book-40-laravel-quick-tips-and-counting/)
- Subscribe to our [YouTube channel Laravel Business](https://www.youtube.com/channel/UCTuplgOBi6tJIlesIboymGA)
- Enroll in our [Laravel Online Courses](https://laraveldaily.teachable.com/)
