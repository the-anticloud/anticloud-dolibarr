# DOLIBARR

> Anticloud offline package — upstream: Dolibarr/dolibarr @ `develop`.

## What This Project Does

Dolibarr ERP CRM is a modern software package to manage your company or foundation's activity (contacts, suppliers, invoices, orders, stocks, agenda, accounting, ...). it's an open source Web application (written in PHP) designed for businesses of any sizes, foundations and freelancers.

**Topics:** accounting, agenda, crm, erp, hacktoberfest, human-resource-managment, invoice, invoices, invoicing, mysql, orders, php, postgresql, proposal, purchase, quotations, sales, stock, stocks, suppliers

## Upstream README

# DOLIBARR ERP & CRM

![Downloads per day](https://img.shields.io/sourceforge/dw/dolibarr.svg)
![Docker hub pulls](https://img.shields.io/docker/pulls/dolibarr/dolibarr.svg)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg?style=flat-square)](https://php.net/)
[![GitHub release](https://img.shields.io/github/v/release/Dolibarr/dolibarr)](https://github.com/Dolibarr/dolibarr)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5521/badge)](https://bestpractices.coreinfrastructure.org/projects/5521)

Dolibarr ERP & CRM is a modern software package that helps manage your organization's activities (contacts, quotes, invoices, orders, stocks, agenda, human resources, ecm, manufacturing…).

It's an Open-Source Software suite (written in PHP with JavaScript enhancements) designed for small, medium or large companies, foundations and freelancers.

You can freely use, study, modify or distribute it according to its license.

You can use it as a standalone application or as a web application to access it from the Internet or from a LAN.

Dolibarr has a large community ready to help you, free forums and [preferred partners ready to offer commercial support should you need it](https://partners.dolibarr.org)

![ScreenShot](https://www.dolibarr.org/medias/dolibarr_screenshot1_1920x1080.jpg)


## LICENSE

Dolibarr is released under the terms of the GNU General Public License as published by the Free Software Foundation; either Version 3 of the License, or (at your option) any later version (GPL-3+).

See the [COPYING](https://github.com/Dolibarr/dolibarr/blob/develop/COPYING) file for a full copy of the license.

Other licenses apply for some included dependencies. See [COPYRIGHT](https://github.com/Dolibarr/dolibarr/blob/develop/COPYRIGHT) for a full list.


## INSTALLING

There is a lot of different solutions to install Dolibarr.

### Using packages 

If you have low technical skills and you're looking to install Dolibarr ERP/CRM with just a few clicks, you can use one of the packaged versions (see next chapter if you have IT knowledge):

- [DoliWamp for Windows](https://wiki.dolibarr.org/index.php/Dolibarr_for_Windows_(DoliWamp))
- [DoliDeb for Debian, Ubuntu](https://wiki.dolibarr.org/index.php/Dolibarr_for_Ubuntu_or_Debian)
- DoliRpm for Red Hat, Fedora, openSUSE, Mandriva or Mageia
- The Docker image (see chapter "Using Docker")

Releases can be downloaded from [official website](https://www.dolibarr.org/).

### Using the generic step by step setup (recommended for IT users)

You can use any web server supporting PHP (Apache, Nginx, ...) and a supported database (MariaDB, MySQL or PostgreSQL) to install the standard version:

- Verify that your installed PHP version is supported [see PHP support](https://wiki.dolibarr.org/index.php/Releases).

- Uncompress the downloaded .zip archive to copy the `dolibarr/htdocs` directory and all its files inside your web server root or get the files directly from 

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
