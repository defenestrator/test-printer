Copacetic Test Printer

Rather than see a string of dots and letters, get some darn information as your tests are running. 

![](https://raw.githubusercontent.com/copacetic-co/test-printer/master/assets/images/screenshot.jpg)

## Installation

Install TestResultPrinter class with composer:

	composer require --dev copacetic/test-printer

For automatic installation, include the project in your composer.json (it is only necessary in require-dev):

```json
	{
		"require-dev": {
			"copacetic/test-printer": ">=1.0.1"
		}
	}
```

If you don't use composer, you can download and save `TestResultPrinter.php` wherever you want. 
You should seriously use composer, dork.

## Usage

To use the `TestResultPrinter` class,  specify it in the phpunit element of `phpunit.xml` config file. 

	<phpunit
		colors="true"
		printerClass="Copacetic\TestResultPrinter"
		>
		...
	</phpunit>

