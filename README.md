# COVID-19 CLI

<img src="https://badges.frapsoft.com/os/v1/open-source.png?v=103"> <a href="LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/dmahajan980/covid19"></a>

A command-line interface to check the current statistics of COVID-19 of the world or a particular country.

## TABLE OF CONTENTS
1. [Getting Started](#getting-started)
2. [Usage](#usage)
3. [Contributing](#contributing)
5. [License](#license)

## GETTING STARTED

1. Clone or download the repository.

2. Install all the dependencies using the following command

   ```bash
   npm install
   ```
   
3. Create a symlink of the repository in the global folder

   ```bash
   sudo npm link
   ```

## USAGE

The CLI will return the latest global statistics about COVID-19 in a tabular format.

   ```bash
   covid19 stats
   ```

The CLI can also return the COVID-19 statistics of a country, if specified, using one of the following commands.

   ```bash
   covid19 stats --country <countryName>
   ```

   ```bash
   covid19 stats -c <countryName>
   ```

The supported formats for `countryName` are ISO2, ISO3 or a single-word name.

## CONTRIBUTING

Open an [issue](https://github.com/dmahajan980/covid19/issues) first to discuss potential changes/additions.

## LICENSE

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](https://github.com/dmahajan980/covid19-cli/blob/master/LICENSE) file for details.
