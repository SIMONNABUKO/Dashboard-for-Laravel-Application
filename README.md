# How to install the dashboard in your Laravel project

#### Copy ./frontend/admin folder into your Laravel's public folder

#### Copy ./admin folder into your Laravel's resources/views folder

#### Copy dashboard.php file into your Laravel's resources/views/layouts folder

#### Create a controller e.g DashboardController then a function called home(you can call it anything you want)eg.

`public function home(){ return view('admin.pages.home'); }`

#### Create a new route in web.php e.g

`route::get('dashboard/home', 'App\Http\Controllers\DahboardController@home')`

##### If you did that correctly, visit http://127.0.0.1/dashboard/home and there you have your dashboard! Customise the way you want.
