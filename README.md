# Academic Domains Dataset

This dataset includes domains of academic institutions such as universities, colleges, and research institutes.


### Data Structure

The whole data set is separated into two json files, one containing only the main academic domains and the other includes their subdomains too. General format of json files are as follows:

    [
    	...
    	{
			"domain": "umada.ac.id",
			"country": "Indonesia",
			"country_alpha_2": "ID",
			"subdomains": [
				"elearning.umada.ac.id",
				"ojs.umada.ac.id",
				"www.umada.ac.id"
			]
		},
    	...
    ]

### Process
First a large data set including over 300 million unique domain name was collected. Then academic domain names with the following patterns were separated: `*.edu`, `*.ac.*` and `*.edu.*`.
Finally a post process phase including country identification and subdomain extraction takes place.

![Process Architecture](https://raw.githubusercontent.com/mohsennazari/academic-domains-dataset/master/assets/academic_domains_list_architecture.jpg)

# Todo
There are always alot to do, but this is our near future plans:
- Packages for python, php and etc.
- Get IP
- Check availability  


# Contribution

Please contribute to this project. We always appreciate an extra hand to make project grow bigger.

# License
This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
