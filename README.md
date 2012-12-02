Generation to PDF for use with Symfony 2.1
==============================

Uses FPDF 1.7

Setup
-----

Add the following lines to your 'composer.json' file:
    "require": {
            "php": ">=5.3.3",
            "symfony/symfony": "2.1.*",
            .......
            "fpdf": "*"
     },
	"repositories": [
            {
                "type": "package",
                "package": {
                    "name": "fpdf",
                    "version": "master",
                    "source": {
                        "url": "git@github.com:startupjob/fpdf.git",
                        "type": "git",
                        "reference": "master"
                    }
                }
            }
        ],


Now run `php composer.phar  update` or `php composer.phar install`.

Usage
--------

        $pdf = new \PDF;
Sources
---------

        [FPDF](http://www.fpdf.org/)

developed by
---------

        [StartupJob](http://www.startupjob.com.br/)