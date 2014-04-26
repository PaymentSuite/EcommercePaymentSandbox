Ecommerce Sandbox platform
========================

Welcome to the Ecommerce Sandbox platform - a fully-functional Symfony2
application that you can use as the skeleton for your new applications.

This document contains information on how to download, install, and start
using Symfony. For a more detailed explanation, see the [Installation][1]
chapter of the Symfony Documentation.

1) Installing the Ecommerce Sandbox platform
--------------------------------------------

When it comes to installing the Ecommerce Sandbox platform, you have the
following options.

### Use Composer (*recommended*)

As Symfony uses [Composer][2] to manage its dependencies, the recommended way
to create a new project is to use it.

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Ecommerce Sandbox application:

    php composer.phar create-project paymentsuite/ecommerce-sandbox-platform path/to/install

Composer will install Ecommerce Sandbox platform and all its dependencies under the
`path/to/install` directory.


2) Browsing the Demo Application
--------------------------------

Congratulations! You're now ready to use Ecommerce Sandbox platform.

To see a real-live Ecommerce Sandbox page in action, access the following page:

    web/app_dev.php

Enjoy!
