Geo
====
PHP Wrapper for Geoplugin.com API

Usage
-------

	$geo = new Geo();
	
	echo $geo;
	Output: You are located in Waterford and your IP is: 83.90.1.82
	
For more detailed information access the individual properties:
	
	$geo->getCity();
	Output: Waterford
	
	$geo->getIP();
	Output: 83.90.1.82
	
	$geo->getCountryName();
	Output: Ireland
	
	$geo->getCurrencyCode();
	Output: EUR
	
There are 9 methods in total.
	
Requirements
------------
* PHP5