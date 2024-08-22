# crt.sh ✨🌐

![crt.sh](https://github.com/xonoxitron/crt.sh/blob/main/banner.png?raw=true)

## Description

`crt.sh` is a simple Bash script that fetches and filters subdomains from the https://crt.sh website. This script allows you to easily retrieve registered subdomains for a given target domain.

## Features

- Fetches subdomains from crt.sh
- Filters and sorts results for clarity
- Outputs results to a specified text file

## Requirements

- `curl`: To fetch the data from crt.sh
- `grep`: For filtering and searching through the data
- `sort`: To sort the list of subdomains
- `uniq`: To remove duplicate entries
- A Bash shell environment

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/xonoxitron/crt.sh.git
   cd crt.sh

   ```

2. Make the script executable:

   ```bash
   chmod +x crt.sh

   ```

3. Run the script:

   ```bash
   ./crt.sh <target_domain> <output_filename>
   ```

4. Check results (example below).

![crt.sh](https://github.com/xonoxitron/crt.sh/blob/main/example.png?raw=true)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
