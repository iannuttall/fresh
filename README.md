> [!TIP]
> To get up and running quickly, clone this repo and run `bash install.sh` in your cloned directory.

# what is fresh?

fresh is a very simple starter kit using Laravel Folio, Livewire Volt and Laravel Luvi UI. This is a fork of [Fission](https://github.com/joshcirre/fission) by [Josh Cirre](https://x.com/joshcirre) because I wanted to be able to do demos which you can follow along with without having to purchase Livewire Flux UI.

btw I love Flux, but let's keep it free when we're just starting out!

## installation

this project includes a custom installation script that streamlines the setup process. here's what the `install.sh` script does in a nutshell:

- installs required Composer packages
- runs the custom `fresh:install` Artisan command
- sets up environment (.env file)
- installs NPM dependencies
- generates application key
- offers to run database migrations
- configures project name and URL
- offers to remove installation files
- provides instructions to start local development server

to install, simply run:

`bash install.sh`

## license

the fresh starter kit is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
