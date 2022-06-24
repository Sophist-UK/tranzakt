# The `app` Directory
The `core/app` directory contains the core code of Tranzakt runtime.
A matching `admin/app` directory holds the core code of Tranzakt Development environment.

This directory is namespaced under `TrzktRun`,
and is autoloaded by Composer using the PSR-4 autoloading standard.

The `app` directory contains a variety of additional directories
such as `Console`, `Http`, and `Providers`.
The `Console` directory contains all of your Artisan commands,
while the `Http` directory contains your controllers, middleware, and requests.

Many of the classes in the `app` directory can be generated by Artisan via commands.
To review the available commands, run the `php artisan list make` command in your terminal.