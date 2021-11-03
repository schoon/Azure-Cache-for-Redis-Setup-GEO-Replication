[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fredisgeek%2Facre-terraform-geo-replication-simple%2Fmain%2FARM%2FACRE%2Fcluster.json)

# acre-geo-replication
## Deploy Azure Cache for Redis Enterprise (ACRE) in two separate regions with active geo-replication

Deploy Azure Cache for Redis Enterprise (ACRE)
in two separate regions with active geo-replication

- _Tenant_
  - _Subscription_
    - _Service Principal_
    - **Resource Group**
      - **Storage Account**
        - **Storage Container**
      - **Redis Enterprise Cluster in Region 1**
      - **Redis Enterprise Cluster in Region 2**
      
## | [Getting Started](#getting-started) | [See Also](#see-also)  | [License](#license) |
   
## Getting Started

```bash
  git clone https://github.com/redisgeek/acre-geo-replication
  cd acre-geo-replication
```

## Roadmap

See the [open issues](https://github.com/redisgeek/acre-geo-replication/issues) for a list of proposed features (and known issues).

## Contributing

Pull-requests are welcomed!

## License

Distributed under the MIT License. See `LICENSE` for more information.

[contributors-shield]: https://img.shields.io/github/contributors/redisgeek/acre-terraform-geo-replication.svg?style=for-the-badge
[contributors-url]: https://github.com/redisgeek/acre-terraform-geo-replication/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/redisgeek/acre-terraform-geo-replication.svg?style=for-the-badge
[forks-url]: https://github.com/redisgeek/acre-terraform-geo-replication/network/members
[stars-shield]: https://img.shields.io/github/stars/redisgeek/acre-terraform-geo-replication.svg?style=for-the-badge
[stars-url]: https://github.com/redisgeek/acre-terraform-geo-replication/stargazers
[issues-shield]: https://img.shields.io/github/issues/redisgeek/acre-terraform-geo-replication.svg?style=for-the-badge
[issues-url]: https://github.com/redisgeek/acre-terraform-geo-replication/issues
[license-shield]: https://img.shields.io/github/license/redisgeek/acre-terraform-geo-replication.svg?style=for-the-badge
[license-url]: https://github.com/redisgeek/acre-terraform-geo-replication/blob/master/LICENSE.txt