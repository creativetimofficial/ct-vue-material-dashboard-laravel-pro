# [Vue Material Dashboard 2 PRO](http://demos.creative-tim.com/vue-material-dashboard-2-pro/#/?ref=readme-vmd2p) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https://www.creative-tim.com/product/vue-material-dashboard-2-pro&text=Check%20Vue%20Material%20Dashboard%202%20Pro%20made%20by%20@CreativeTim%20#webdesign%20#dashboard%20#materialdesign%20#vue%20https://www.creative-tim.com/product/vue-material-dashboard-pro)

![version](https://img.shields.io/badge/version-3.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-vue-material-dashboard-2-pro.svg)](https://github.com/creativetimofficial/ct-vue-material-dashboard-2-pro/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-vue-material-dashboard-2-pro.svg)](https://github.com/creativetimofficial/ct-vue-material-dashboard-2-pro/issues?q=is%3Aissue+is%3Aclosed)

![Image](https://s3.amazonaws.com/creativetim_bucket/products/595/original/vue-material-dashboard-pro.jpg)

Vue Material Dashboard 2 PRO is our newest premium Admin Template based on Vue3 & Bootstrap5. If you’re a developer looking to create an admin dashboard that is developer-friendly, rich with features, and highly customisable, here is your match. Our innovative Vue3 & Bootstrap5 dashboard comes with a beautiful design inspired by Google's Material Design and it will help you create stunning websites & web apps to delight your clients

# Download

For the PRO version of the project you will download the .zip file from the Creative Tim site and extract it.
You will get two project folders: one for the Laravel API project and one for the Vue frontend.

# Table of Contents

- [Versions](#versions)
- [Demo](#demo)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Documentation](#documentation)
- [File Structure](#file-structure)
- [Browser Support](#browser-support)
- [Resources](#resources)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions)
- [Licensing](#licensing)
- [Useful Links](#useful-links)

# Versions

[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/vue-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-dashboard-2-pro?ref=readme-vmd2p)

| VueJS |
| ----- |

| [![Vue Material Dashboard 2 PRO](https://s3.amazonaws.com/creativetim_bucket/products/595/thumb/vue-material-dashboard-pro.jpg)](http://demos.creative-tim.com/vue-material-dashboard-2-pro/?ref=readme-vmd2p)

# Demo

If you want to get inspiration or just show something directly to your clients, you can jump-start your development with our pre-built example pages. You will be able to quickly set up the basic structure for your web project.

- [Dashboard](http://demos.creative-tim.com/vue-material-dashboard-2-pro/#/dashboards/dashboard-default?ref=readme-vmd2p)
- [Sales](http://demos.creative-tim.com/vue-material-dashboard-2-pro/#/dashboards/sales?ref=readme-vmd2p)
- [Profile](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/pages/profile/overview?ref=readme-vmd2p)
- [Account](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/pages/account/settings?ref=readme-vmd2p)
- [RTL](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/pages/rtl-page?ref=readme-vmd2p)
- [Applications](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/applications/kanban?ref=readme-vmd2p)
- [Ecommerce](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/ecommerce/products/product-page?ref=readme-vmd2p)
- [Sign In](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/authentication/signin/basic?ref=readme-vmd2p)
- [Sign Up](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/authentication/signup/cover?ref=readme-vmd2p)

[View More](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/dashboards/dashboard-default?ref=readme-vmd2p).

# Quick start

Quick start options:
- Buy from [Creative Tim](https://www.creative-tim.com/product/vue-material-dashboard-2-pro?ref=readme-vmd2p).

## Introduction

JSON:API is a specification for how a client should request that resources be fetched or modified, and how a server should respond to those requests. It is designed to minimize both the number of requests and the amount of data transmitted between clients and servers. This efficiency is achieved without compromising readability, flexibility, or discoverability.

## Prerequisites

### JSON:API backend
The Laravel JSON:API backend project requires a proper multi-threaded web server such as Apache/Nginx environment with PHP, Composer and MySQL.

[Click here to go to the JSON:API docs]()

**Do not use `php artisan serve` as it will result in stalled requests due to the single-threaded nature of the built-in PHP web server.**

We strongly recommend using [Laradock](https://laradock.io/) for Linux and Mac or [Laragon](https://laragon.org/download/) for Windows if possible.

Other options for your local environment:

Windows: [How to install WAMP on Windows](https://updivision.com/blog/post/beginner-s-guide-to-setting-up-your-local-development-environment-on-windows)
Linux: [How to install LAMP on Linux](https://howtoubuntu.org/how-to-install-lamp-on-ubuntu)
Mac: [How to install MAMP on MAC](https://wpshout.com/quick-guides/how-to-install-mamp-on-your-mac/)
You will also need to install Composer 2: https://getcomposer.org/doc/00-intro.md


### Vue Material frontend

The Vue Material frontend project requires a working local environment with NodeJS version 8.9 or above (8.11.0+ recommended), npm, VueCLI.

Install Node: https://nodejs.org/ (version 8.11.0+ recommended)

Install NPM: https://www.npmjs.com/get-npm

Install VueCLI: https://cli.vuejs.org/guide/installation.html

## Laravel JSON:API Project Installation

1. Navigate in your Laravel API project folder: cd `your-laravel-json-api-project`
2. Install project dependencies: `composer install`
3. Create a new .env file: `cp .env.example .env`
4. Add your own database credentials in the .env file in DB_DATABASE, DB_USERNAME, DB_PASSWORD
5. Create users table: `php artisan migrate --seed`
6. Generate application key: `php artisan key:generate`
7. Install Laravel Passport: `php artisan passport:install` and set in the .env file the CLIENT_ID and CLIENT_SECRET that you receive
8. Add your own mailtrap.io credentials in MAIL_USERNAME and MAIL_PASSWORD in the .env file


## Vue Material Dashboard Project Installation

1. Navigate to your Vue Dashboard project folder: `cd your-vue-material-dashbord-project`
2. Install project dependencies: `npm install`
3. Create a new .env file: `cp .env.example .env`
4. `VUE_APP_BASE_URL` should contain the URL of your Vue Material Dashboard Project (eg. http://localhost:8080/)
5. `VUE_APP_API_BASE_URL` should contain the URL of your Laravel JSON:API Project. (eg. http://localhost:3000/api/v1)
6. Run `npm run dev` to start the application in a local development environment or npm run build to build release distributables.


## Fully Coded Elements

Vue Material Dashboard 2 PRO is built with over 100 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining. All components can take variations in color, which you can easily modify using sass files. You will save a lot of time going from prototyping to full-functional code because all elements are implemented.

This Premium Vue3 & Bootstrap5 Dashboard is coming with prebuilt design blocks, so the development process is seamless,
switching from our pages to the real website is very easy to be done.

View [all components here](https://www.creative-tim.com/learning-lab/vue/alerts/material-dashboard/).

# Usage
To start testing the Pro theme, register as a user or log in using one of the default users:

- admin type - admin@jsonapi.com with the password **secret**
- creator type - creator@jsonapi.com with the password **secret**
- member type - member@jsonapi.com with the password **secret**

In addition to the features included in the free theme, the Pro theme also has a role management example with an updated user management, as well as tag management, category management and item management examples. All the necessary files are installed out of the box and all the needed routes are added to src\router\index.js. Keep in mind that all the features can be viewed once you log in using the credentials provided above or by registering your own user.

Each role has a different privilege level and can perform a certain number of actions according to this level.

A **member type** user can log in and update his profile.

A **creator type** user can log in, update his profile and perform actions on categories, tags and items.

An **admin type** user can log in, update his profile and perform actions on categories, tags, items, roles and users.

### Dashboard
You can access the dashboard either by using the "**Dashboards/Analytics**" link in the left sidebar or by adding **/dashboards/dashboard-default** in the URL.

### Login
The login functionality is fully implemented in our theme helping you to start your project in no time. To login into dashboard you just have to add **/login** in the URL and fill the login form with one of the credentials (user: admin@jsonapi.com, creator@jsonapi.com, member@jsonapi.com and password: **secret**).

The `src\views\Login.vue` is the Vue component which handles the login functinality. You can easily adapt it to your needs.

It uses the auth store located in `src\store\auth.module.js.`

#### Login example
```
<div class="card z-index-0 fadeIn3 fadeInBottom">
    <div class="card-header p-0 position-relative mt-n4 mx-3 z-index-2">
        <div class="bg-gradient-success shadow-success border-radius-lg py-3 pe-1">
            <h4 class="text-white font-weight-bolder text-center mt-2 mb-0">
                Sign in
            </h4>
            <div class="row mt-3">
                <div class="col-2 text-center ms-auto">
                    <a class="btn btn-link px-3" href="javascript:;">
                        <i class="fab fa-facebook text-white text-lg"></i>
                    </a>
                </div>
                <div class="col-2 text-center px-1">
                    <a class="btn btn-link px-3" href="javascript:;">
                        <i class="fab fa-github text-white text-lg"></i>
                    </a>
                </div>
                <div class="col-2 text-center me-auto">
                    <a class="btn btn-link px-3" href="javascript:;">
                        <i class="fab fa-google text-white text-lg"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="card-body">
        <Form role="form" class="text-start mt-3" :validation-schema="schema" @submit="handleLogin"
            @invalid-submit="badSubmit">
            <div class="mb-3">
                <material-input-field id="email" v-model:value="user.email" type="email"
                    label="Email" name="email" />
            </div>
            <div class="mb-3">
                <material-input-field id="password" v-model:value="user.password" type="password"
                    label="Password" name="password" />
            </div>
            <material-switch id="rememberMe" name="Remember Me">Remember me</material-switch>
            <div class="text-center">
                <material-button class="my-4 mb-2" variant="gradient" color="success" full-width>
                    <span>Sign in</span>
                </material-button>
            </div>
            <p class="mt-4 text-sm text-center">
                Don't have an account?
                <router-link :to="{ name: 'Signup' }"
                    class="text-success text-gradient font-weight-bold">Sign
                    up</router-link>
            </p>
            <p class="text-sm text-center">
                <router-link :to="{ name: 'PasswordForgot' }"
                    class="text-success text-gradient font-weight-bold">Recover
                    Password</router-link>
            </p>
        </Form>
    </div>
</div>
```

### Register
The register functionality is fully implemented in our theme helping you to start your project in no time. To register a new user you just have to add **/signup** in the URL or click on register link from login page and fill the register form with user details.

The `src\views\Signup.vue` is the Vue component which handles the register functinality. You can easily extend it to your needs.

It uses the auth store located in src\store\auth.module.js.

#### Register example

```
<div class="card mt-8">
    <div class="card-header p-0 position-relative mt-n4 mx-3 z-index-2">
        <div class="bg-gradient-success shadow-success border-radius-lg py-3 pe-1 text-center py-4">
            <h4 class="font-weight-bolder text-white mt-1">
                Join us today
            </h4>
            <p class="mb-1 text-white text-sm">
                Enter your email and password to register
            </p>
        </div>
    </div>
    <div class="card-body pb-3">
        <Form role="form" :validation-schema="schema" @submit="handleSignup">
            <div class="mb-3">
                <material-input-field id="name" v-model:value="user.name" label="Name"
                    name="name" />
            </div>
            <div class="mb-3">
                <material-input-field id="email" v-model:value="user.email" type="email"
                    label="Email" name="email" />
            </div>
            <div class="mb-3">
                <material-input-field id="password" v-model:value="user.password" type="password"
                    label="Password" name="password" />
            </div>
            <div class="mb-3">
                <material-input-field id="confirmPassword" v-model:value="user.confirmPassword"
                    type="password" label="Confirm Password" name="confirmPassword" />
            </div>
            <material-checkbox-field id="flexCheckDefault" v-model:checked="termsChecked"
                name="checkbox">
                I agree the
                <a href="../../../pages/privacy.html" class="text-dark font-weight-bolder">Terms and
                    Conditions</a>
            </material-checkbox-field>
            <div class="text-center">
                <material-button color="success" variant="gradient" full-width
                    class="mt-4 mb-0">Sign up</material-button>
            </div>
        </Form>
    </div>
    <div class="card-footer text-center pt-0 px-sm-4 px-1">
        <p class="mb-4 mx-auto">
            Already have an account?
            <router-link :to="{ name: 'Login' }"
                class="text-success text-gradient font-weight-bold">Sign in</router-link>
        </p>
    </div>
</div>
```

### Profile edit

You have the option to edit the current logged in user's profile information (name, email, profile picture) and password. To access this page, just click the "**Examples(API)/User Profile**" link in the left sidebar or add **/user-profile** in the URL.

The `src\views\examples-api\profile` is the folder with Vue components that handle the update of the user information and password.

#### Profile edit example

```
<div class="multisteps-form__panel border-radius-xl bg-white" data-animation="FadeIn">
    <h5 class="font-weight-bolder mb-0">About me</h5>
    <div class="multisteps-form__content">

      <div class="row mt-4 overflow-hidden">
        <div>
          <material-avatar :img="imgSource" shadow="regular" class="img-fluid w-20 mt-7">
          </material-avatar>
        </div>
        <div class="mt-1  mb-2">
          <material-button size="sm" type="button">
            <label for="imageInput" class="mb-0 text-white small">Select Image</label>
            <input id="imageInput" @change.prevent="onFileChange" type="file" style="display: none;" accept="image/*">
          </material-button>
        </div>
      </div>


      <div class="row mt-5">

        <material-input id="name" label="Name" variant="static" v-model:value="user.name" name="name" />
        <validation-error :errors="apiValidationErrors.name" />

      </div>

      <div class="row mt-5">
        <material-input id="email" type="email" label="Email Address" variant="static" v-model:value="user.email"
          name="email" />

        <validation-error :errors="apiValidationErrors.email" />
      </div>

      <div class="button-row d-flex mt-4">
        <material-button type="button" color="dark" variant="gradient" class="ms-auto mb-0 js-btn-next"
          @click="handleSubmit">Submit Changes</material-button>
      </div>
    </div>
  </div>
```

#### Password edit example

```
<div class="multisteps-form__panel border-radius-xl bg-white" data-animation="FadeIn">
    <h5 class="font-weight-bolder mb-0">Change Password</h5>
    <div class="multisteps-form__content mt-4">
      <div class="row">
        <div class="col-12">
          <div class="mt-2">
            <material-input id="password" v-model:value="user.password" type="password" label="Password"
              name="password" />

            <validation-error :errors="apiValidationErrors.password" />
          </div>
          <div class="mt-5">
            <material-input id="confirmPassword" v-model:value="user.password_confirmation" type="password"
              label="Confirm Password" name="confirmPassword" />
          </div>
        </div>
      </div>
      <div class="button-row d-flex mt-4">
        <material-button type="button" color="dark" variant="gradient" class="ms-auto mb-0 js-btn-next"
          @click="handleChange">Change Password</material-button>
      </div>
    </div>
  </div>
```

### Roles Management

The Pro theme allows you to add user roles. By default, the theme comes with **Admin**, **Creator** and **Member** roles. To access the role management example click the "**Examples(API)/Roles**" link in the left sidebar or add **/roles-list** to the URL. Here you can add/edit new roles. To add a new role, click the "**Add role**" button. To edit an existing role, click the "**Edit**" button. In both cases, you will be directed to a form which allows you to modify the name and description of a role.

You can find the compoments for role functionality in `src\views\examples-api\roles` folder.

The store used for role functionality is found in `src\store\roles.module.js`

#### Roles list example
```
<table id="user-list" ref="table" class="table table-flush">
  <thead class="thead-light">
    <tr>
      <th title="name" class="w-45">Name</th>
      <th title="created_at" class="w-45">Created at</th>
      <th data-sortable="false" class="text-end">Actions</th>
    </tr>
  </thead>
  <tbody class="text-sm">
  </tbody>
</table>
```

#### Add/Edit role example
```
<div class="col-10">
  <material-input id="name" v-model:value="role.name" label="Name"
      name="name"></material-input>
  <validation-error :errors="apiValidationErrors.name"></validation-error>
</div>
```

### Users Management

The theme comes with an out of the box user management option. To access this option, click the "**Examples(API)/Users**" link in the left sidebar or add **/users-list** to the URL. The first thing you will see is a list of existing users. You can add new ones by clicking the "**Add user**" button (above the table on the right). On the Add user page, you will find a form which allows you to fill out the user`s name, email, role and password. To edit an existing user, click the  button.

You can find the compoments for user functionality in `src\views\examples-api\users` folder.

The store used for user functionality is found in `src\store\users.module.js`

#### Users list example
```
<table id="user-list" ref="table" class="table table-flush">
  <thead class="thead-light">
    <tr>
      <th data-sortable="false">Avatar</th>
      <th title="name">Name</th>
      <th title="email">Email</th>
      <th title="roles.name">Role</th>
      <th title="created_at">Created at</th>
      <th data-sortable="false">Action</th>
    </tr>
  </thead>
  <tbody class="text-sm">
  </tbody>
</table>
```

#### Add/Edit user example
```
<div class="row mt-4 overflow-hidden">
  <div>
    <material-avatar :img="user.profile_image" shadow="regular" class="image-fluid w-20 mt-7" :fixedSize="true">
    </material-avatar>
  </div>
  <div class="mt-1  mb-2">
    <material-button size="sm" type="button">
      <label for="imageInput" class="mb-0 text-white small">Select Image</label>
      <input id="imageInput" @change.prevent="onFileChange" type="file" style="display: none;" accept="image/*">
    </material-button>
  </div>
</div>

<div class="row mt-5">

  <material-input id="name" label="Name" variant="static" v-model:value="user.name" name="name" />
  <validation-error :errors="apiValidationErrors.name" />

</div>

<div class="row mt-5">
  <material-input id="email" type="email" label="Email Address" variant="static" v-model:value="user.email"
    name="email" />
  <validation-error :errors="apiValidationErrors.email" />
</div>

<!--selectedRole-->
<div class="mt-5">
  <label class="ms-0"> Role </label>
  <select id="choices-state" class="multisteps-form__select form-control" name="choices-state">
  </select>
</div>

<div class="row mt-5">
  <material-input id="password" v-model:value="user.password" variant="static" type="password" label="Password"
    name="password" />
  <validation-error :errors="apiValidationErrors.password" />
</div>
<div class="row mt-5">
  <material-input id="confirmPassword" variant="static" v-model:value="user.password_confirmation" type="password"
    label="Confirm Password" name="confirmPassword" />
</div>
```

### Tags Management

Out of the box you will have an example of tag management (for the cases in which you are developing a blog or a shop). To access this example, click the "**Examples(API)/Tags**" link in the left sidebar or add **/tags-list** to the URL. You can add and edit tags here, but you can only delete them if they are not attached to any items.

You can find the compoments for tag functionality in `src\views\examples-api\tags` folder.

The store used for tag functionality is found in `src\store\tags.module.js`

#### Tags list example
```
<table id="tag-list" ref="table" class="table table-flush">
  <thead class="thead-light">
    <tr>
      <th data-sortable="false" class="w-20">Name</th>
      <th title="name" class="w-20">Color</th>
      <th title="created_at" class="w-20">Created at</th>
      <th data-sortable="false" class="text-end">Action</th>
    </tr>
  </thead>
  <tbody class="text-sm">
  </tbody>
</table>
```

#### Add/Edit tag example
```
<div class="card-body">
  <form>
      <div class="row">
          <div class="col-10">

              <material-input id="name" v-model:value="tag.name" label="Name"
                  name="name" variant="static"></material-input>
              <validation-error :errors="apiValidationErrors.name"></validation-error>

          </div>

      </div>

      <div class="row mt-5 mb-5 d-flex align-items-center">

          <div class="col-10">
              <label class="ms-0"> Color </label>
              <slider v-model="color" class="w-100"></slider>
              <validation-error :errors="apiValidationErrors.color"></validation-error>
          </div>

          <div class="col-2 text-end mt-5">
              <material-button class="float-right btn btm-sm" @click.prevent="handleAdd">Add
                  Tag</material-button>
          </div>
      </div>
  </form>
</div>
```

### Categories Management
Out of the box you will have an example of category management (for the cases in which you are developing a blog or a shop). To access this example, click the "**Examples(API)/Categories**" link in the left sidebar or add **/categoies-list** to the URL. You can add and edit categories here, but you can only delete them if they are not attached to any items.

You can find the compoments for category functionality in `src\views\examples-api\categories` folder.

The store used for category functionality is found in `src\store\categories.module.js`

#### Categories list example
```
<table id="category-list" ref="table" class="table table-flush">
    <thead class="thead-light">
      <tr>
        <th data-sortable="false" class="w-20">Name</th>
        <th title="description" class="w-40">Description</th>
        <th title="created_at" class="w-20">Created at</th>
        <th data-sortable="false" class="text-end">Action</th>
      </tr>
    </thead>
    <tbody class="text-sm">
    </tbody>
  </table>
```

#### Add/Edit category example
```
<div class="card-body">
    <form>

        <div class="row mt-5">
            <div class="col-10">

                <material-input id="name" v-model:value="category.name" label="Name" variant="static"
                    name="name"></material-input>
                <validation-error :errors="apiValidationErrors.name"></validation-error>

            </div>
        </div>

        <div class="row mt-4 mb-5 d-flex align-items-end">

            <div class="col-10">
            <material-input id="description" v-model:value="category.description" label="Description" variant="static"
                    name="description"></material-input>
                <validation-error :errors="apiValidationErrors.description"></validation-error>
            </div>
            <div class="col-2 text-end">
                <material-button class="float-right btn btm-sm" @click.prevent="handleAdd">Add
                    Category</material-button>
            </div>
        </div>
    </form>
</div>
```

### Items Management

Item management is the most advanced example included in the Pro theme, because every item has a picture, belongs to a category and has multiple tags. To access this example click the "**Examples(API)/Items**" link in the left sidebar or add **/items-list** to the URL. Here you can manage the items. A list of items will appear once you start adding them (to access the add page click "**Add item**"). On the add page, besides the Name and Description fields (which are present in most of the CRUD examples) you can see a category dropdown, which contains the categories you added, a file input and a tag multi select. If you did not add any categories or tags, please go to the corresponding sections (categories, tags) and add some.

You can find the compoments for item functionality in `src\views\examples-api\items` folder.

The store used for item functionality is found in `src\store\items.module.js`

#### Items list example
```
<table id="item-list" ref="table" class="table table-flush">
    <thead class="thead-light">
      <tr>
        <th title="name" class="w-20">Name</th>
        <th title="category" class="w-20">Category</th>
        <th title="picture" class="w-20">Picture</th>
        <th title="tags" class="w-20">Tags</th>
        <th title="created_at" class="w-20">Created at</th>
        <th data-sortable="false" class="text-end">Action</th>
      </tr>
    </thead>
    <tbody class="text-sm">
    </tbody>
  </table>
```

#### Add/Edit item example
```
<div class="card-body">
    <form>
        <div class="mt-4 overflow-hidden">
            <div>
                <material-avatar :img="item.image" shadow="regular" class="img-fluid w-20 mt-7"
                    :fixedSize="true">
                </material-avatar>
            </div>
            <div class="mt-1 mb-2">
                <material-button size="sm" type="button">
                    <label for="imageInput" class="mb-0 text-white small">Select Image</label>
                    <input id="imageInput" @change.prevent="onFileChange" type="file"
                        style="display: none;">
                </material-button>
            </div>
        </div>

        <div class="mt-5">
            <material-input id="name" label="Name" v-model:value="item.name" name="name"
                variant="static" />
            <validation-error :errors="apiValidationErrors.name" />
        </div>

        <div class="mt-5">
            <label class="ms-0"> Description </label>
            <material-textarea id="description" v-model:value="item.description"
                name="description" />
            <validation-error :errors="apiValidationErrors.description" />
        </div>

        <!--selectedCategory-->
        <div class="mt-5">
            <label class="ms-0"> Category </label>
            <select id="choices-categories" class="multisteps-form__select form-control"
                name="choices-categories">
            </select>
            <validation-error :errors="apiValidationErrors.category" />
        </div>

        <!--selectedTag-->
        <div class="mt-5">
            <label class="ms-0"> Tags </label>
            <select multiple id="choices-tags" class="multisteps-form__select form-control"
                name="choices-tags">
            </select>
            <validation-error :errors="apiValidationErrors.tags" />
        </div>

        <!--selectedStatus-->
        <div class="mt-5">
            <label class="ms-0"> Status </label>

            <div class="form-check ps-0">
                <input class="form-check-input" type="radio" name="radio" id="published"
                    value="published" v-model="item.status">
                <label class="form-check-label" for="published">Published</label>
            </div>
            <div class="form-check ps-0">
                <input class="form-check-input" type="radio" name="radio" id="draft" value="draft"
                    v-model="item.status">
                <label class="form-check-label" for="draft">Draft</label>
            </div>
            <div class="form-check ps-0">
                <input class="form-check-input" type="radio" name="radio" id="archive"
                    value="archive" v-model="item.status">
                <label class="form-check-label" for="archive">Archive</label>
            </div>
            <validation-error :errors="apiValidationErrors.status" />
        </div>

        <!--showOnHomepage-->
        <div class="mt-5">
            <label class="ms-0"> Show on homepage? </label>
            <div class="form-check form-switch mb-4">
                <input class="form-check-input" type="checkbox" id="isOnHomepage"
                    v-model="item.is_on_homepage">
            </div>
            <validation-error :errors="apiValidationErrors.is_on_homepage" />
        </div>


        <!--date-->
        <div class="mt-5">
            <label class="ms-0"> Date </label>
            <flatPickr v-model="item.date_at" class="form-control" placeholder=" Select date">
            </flatPickr>
            <validation-error :errors="apiValidationErrors.date_at" />
        </div>

        <div class="button-row d-flex mt-4">
            <material-button type="button" color="dark" variant="gradient"
                class="ms-auto mb-0 js-btn-next" @click="handleAdd">Add Item</material-button>
        </div>
    </form>
</div>
```








# Documentation

Each element is well presented in very complex documentation.
You can read more about the [documentation here](https://www.creative-tim.com/learning-lab/vue/overview/material-dashboard/).

### File Structure

Within the download you'll find the following directories and files:

```
vue-material-dashboard-2-pro
    ├── public
    │   ├── favicon.png
    │   └── index.html
    ├── src
    │   ├── assets
    │   │   ├── css
    │   │   ├── fonts
    │   │   ├── img
    │   │   ├── js
    │   │   └── scss
    │   ├── components
    │   │   ├── BasePagination.vue
    │   │   ├── MaterialAlert.vue
    │   │   ├── MaterialAvatar.vue
    │   │   ├── MaterialBadge.vue
    │   │   ├── MaterialButton.vue
    │   │   ├── MaterialCheckbox.vue
    │   │   ├── MaterialCheckboxField.vue
    │   │   ├── MaterialInput.vue
    │   │   ├── MaterialInputField.vue
    │   │   ├── MaterialPagination.vue
    │   │   ├── MaterialPaginationItem.vue
    │   │   ├── MaterialProgress.vue
    │   │   ├── MaterialRadio.vue
    │   │   ├── MaterialSnackbar.vue
    │   │   ├── MaterialSocialButton.vue
    │   │   ├── MaterialSwitch.vue
    │   │   ├── MaterialTextarea.vue
    │   │   └── ValidationError.vue
    │   ├── examples
    │   │   ├── Cards
    │   │   ├── Charts
    │   │   ├── Navbars
    │   │   ├── PageLayout
    │   │   ├── Sidenav
    │   │   ├── Breadcrumbs.vue
    │   │   ├── Calendar.vue
    │   │   ├── Configurator.vue
    │   │   └── Footer.vue
    │   ├── mixins
    |   |   ├── eventTable.js
    │   │   ├── formMixin.js
    │   │   └── showSwal.js
    │   ├── router
    |   |    └── index.js
    │   ├── services
    │   │   ├── auth-header.js
    │   │   ├── auth.service.js
    │   │   ├── categories.service.js
    │   │   ├── items.service.js
    │   │   ├── profile.service.js
    │   │   ├── roles.service.js
    │   │   ├── tags.service.js
    │   │   └── users.service.js
    │   ├── store
    │   │   ├── auth.module.js
    │   │   ├── categories.module.js
    │   │   ├── index.js
    │   │   ├── items.module.js
    │   │   ├── profile.module.js
    │   │   ├── roles.module.js
    │   │   ├── tags.module.js
    │   │   └── users.module.js
    │   ├── views
    │   │   ├── applications
    │   │   ├── auth
    │   │   ├── dashboards
    │   │   ├── ecommerce
    │   │   ├── pages
    │   │   ├── Home.vue
    │   │   ├── Login.vue
    │   │   ├── PasswordForgot.vue
    │   │   ├── PasswordReset.vue
    │   │   └── Signup.vue
    │   ├── App.vue
    │   ├── main.js
    │   └── material-dashboard.js
    ├── .browserslistrc
    ├── .eslintrc.js
    ├── .gitignore
    ├── babel.config.json
    ├── CHANGELOG.md
    ├── ISSUE_TEMPLATE.md
    ├── package.json
    └── README.md
```

### Special thanks
During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:

- [noUISlider](https://refreshless.com/nouislider/) - JavaScript Range Slider
- [Popper.js](https://popper.js.org/) - Kickass library used to manage poppers
- [Flatpickr](https://flatpickr.js.org/) - Useful library used to select date
- [Choices JS](https://joshuajohnson.co.uk/Choices/) - A nice plugin that select elements with intuitive multiselection and searching but also for managing tags.
- [CountUp JS](https://inorganik.github.io/countUp.js/) - A dependency-free, lightweight JavaScript class that can be used to quickly create animations that display numerical data in a more interesting way.
- [Charts Js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting for designers & developers
- [FullCalendar](https://fullcalendar.io/) - Full-sized drag & drop event calendar
- [Dropzone](https://www.dropzonejs.com/) - An open source library that provides drag’n’drop file uploads with image previews.
- [Datatables](https://github.com/fiduswriter/Simple-DataTables) - DataTables but in Vanilla ES2018 JS
- [jKanban](http://www.riccardotartaglia.it/jkanban/) - Pure agnostic Javascript plugin for Kanban boards
- [PhotoSwipe](https://photoswipe.com/) - JavaScript image gallery for mobile and desktop, modular, framework independent
- [Quill](https://quilljs.com/) - A free, open source WYSIWYG editor built for the modern web
- [Wizard](https://www.cssscript.com/multi-step-form-bootstrap/) - Animated Multi-step form for Bootstrap

Let us know your thoughts below. And good luck with development!

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources

- [Live Preview](https://demos.creative-tim.com/vue-material-dashboard-2-pro/#/?ref=readme-vmd2p)
- [Buy Page](https://www.creative-tim.com/product/vue-material-dashboard-2-pro?ref=readme-vmd2p)
- Documentation is [here](https://www.creative-tim.com/learning-lab/vue/overview/material-dashboard/?ref=readme-vmd2p)
- [License Agreement](https://www.creative-tim.com/license?ref=readme-vmd2p)
- [Support](https://www.creative-tim.com/contact-us?ref=readme-vmd2p)
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-vue-material-dashboard-2-pro/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Vue Material Dashboard 2 PRO. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Vue Material Dashboard 2 PRO. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/product/vue-material-dashboard-2-pro?ref=readme-vmd2p).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us?ref=readme-vmd2p) instead of opening an issue.

## Licensing

- Copyright 2022 [Creative Tim](https://www.creative-tim.com?ref=readme-vmd2p)
- Creative Tim [license](https://www.creative-tim.com/license?ref=readme-vmd2p)

## Useful Links

- [More products](https://www.creative-tim.com/templates?ref=readme-vmd2p) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free?ref=readme-vmd2p) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new?ref=readme-vmd2p) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
