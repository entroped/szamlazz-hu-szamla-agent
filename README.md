# szamlazz-hu-szamla-agent

SzamlaAgent is an invoice manager API proviced by [https://szamlazz.hu](https://szamlazz.hu/).

The latest version can be downloaded directly from: [https://docs.szamlazz.hu/#php-api](https://docs.szamlazz.hu/#php-api)

Current applied version: **2.10.28**

This repository is using the original implementation uploaded to [packagist.org](https://packagist.org/) in order to use **SzamlazzAgent** with various PHP frameworks and applications.

## Getting Started

Follow these steps to quickly set up your  project.

### Requirements

Before you begin, ensure you have the following installed on your system:

- PHP (version 7.x or higher)
- Composer (version 2.6.6 or higher)

### Installation

Install via Composer:

```bash
composer require entroped/szamlazz-hu-szamla-agent
```

### Configuration

Use your own API key received from szamlazz.hu to use the ageng
```php

use Entroped\SzamlazzHuSzamlaAgent;


$agent = SzamlaAgentAPI::create('YOUR_API_KEY');

```

## Support

For any questions or assistance, feel free to create a Github Issue for this project.

## License

This GitHub Repository is licensed under MIT License to Entroped (C), but the SzamlaAgent implementation itself has a **proprietary license to szamlazz.hu**.
