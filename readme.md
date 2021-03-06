reSlim UI Boilerplate
=======
[![Coverage](https://img.shields.io/badge/coverage-100%25-brightgreen.svg)](https://github.com/aalfiann/reSlim-ui-boilerplate)
[![Version](https://img.shields.io/badge/stable-1.23.2-brightgreen.svg)](https://github.com/aalfiann/reSlim-ui-boilerplate)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/aalfiann/reSlim-ui-boilerplate/blob/master/license.md)

Basic UI template for production use with [reSlim](https://github.com/aalfiann/reSlim).<br>

System Requirements
---------------

1. Web server with URL rewriting
2. PHP 5.5 or newer
3. You already have reSlim rest api version >= 1.14.1 running


Getting Started
---------------
1. Edit the config.php inside folder "reSlim-ui-boilerplate/src/app"<br>
    $config['title'] = 'reSlim UI';<br>
    $config['keyword'] = 'Backend, Rest, API, UI';<br>
    $config['description'] = 'Make your project reSlim with use restful api. reSlim is based on Slim3';<br>
    $config['email'] = 'your default email address';<br>
    $config['basepath'] = 'url location of base path of this app'; //it should be http://localhost:1337/reSlim-ui-boilerplate/src/app<br>
    $config['homepath'] = 'url location of home path of this app'; //it should be http://localhost:1337/reSlim-ui-boilerplate/src/app<br>
    $config['assetspath'] = 'url location of assets path of this app'; //it should be http://localhost:1337/reSlim-ui-boilerplate/src/assets<br>
    $config['homepath'] = 'url location of front path';<br>
    $config['api'] = 'url location of base path of reslim rest api';<br>
    $config['apikey'] = 'your api key, you can leave this blank and fill this later';<br><br>
    That is enough, you can set it later from admin panel
3. Visit yourserver/reSlim-ui-boilerplate/src/app<br>
    For my case is http://localhost:1337/reSlim-ui-boilerplate/src/app
4. You can login with default superuser account:<br>
    Username : reslim<br>
    Password : reslim
5. All is done

The concept authentication in reSlim
-----------------

1. Register account first
2. Then You have to login to get the generated new token

The token is always generated new when You relogin and the token is will expired in 7 days as default.<br>
If You logout or change password or delete user, the token will be clear automatically.

For more information about reSlim, you have to visit >> https://github.com/aalfiann/reSlim

Documentation
-----------------
reSlim-ui-boilerplate documentation is available on [Wiki](https://github.com/aalfiann/reslim-ui-boilerplate/wiki).