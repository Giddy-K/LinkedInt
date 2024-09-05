<p align="center">
<img src="https://github.com/vysecurity/LinkedInt/blob/master/asset/linkedint.png?raw=true">
</p>

# Sponsor Open Source Tooling

* Feel free to sponsor me for maintaining the tool:
* TODO

# Disclaimer

* The project is to be used for educational and testing purposes only.

# Authors

Gideon Kipamet - https://github.com/Giddy-K

Contributors:

Feel free to contribute and add your socials, github profile or name here.

# Installation
```
git clone https://github.com/Giddy-K/LinkedInt.git
cd LinkedInt
pip install -r requirements.txt
```

# Change Log

Fixes:
* Fixed the authentication flow
* Fixed hunter API demo key - removed

Additions:
* Added better looking missing image value for the profiles with no photo.
* Embedded all images into the HTML file to allow for offline viewing.
* Added credits
* UI Updates
* Constrain to company filters
* Addition of Hunter for e-mail prediction

# Usage

1. Put in LinkedIn credentials in LinkedInt.cfg
2. Put Hunter.io API key in LinkedInt.cfg
3. Run LinkedInt.py and follow instructions (example below).

# Example

Using General Motors as the target as they have a bug bounty program.

```
██╗     ██╗███╗   ██╗██╗  ██╗███████╗██████╗ ██╗███╗   ██╗████████╗
██║     ██║████╗  ██║██║ ██╔╝██╔════╝██╔══██╗██║████╗  ██║╚══██╔══╝
██║     ██║██╔██╗ ██║█████╔╝ █████╗  ██║  ██║██║██╔██╗ ██║   ██║
██║     ██║██║╚██╗██║██╔═██╗ ██╔══╝  ██║  ██║██║██║╚██╗██║   ██║
███████╗██║██║ ╚████║██║  ██╗███████╗██████╔╝██║██║ ╚████║   ██║
╚══════╝╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚══════╝╚═════╝ ╚═╝╚═╝  ╚═══╝   ╚═╝

Providing you with Linkedin Intelligence
Author: Giddy-K
Original version by Vincent Yiu (@vysec, @vysecurity)
[*] Enter search Keywords (use quotes for more precise results)
"General Motors"

[*] Enter filename for output (exclude file extension)
generalmotors

[*] Filter by Company? (Y/N):
Y

[*] Specify a Company ID (Provide ID or leave blank to automate):


[*] Enter e-mail domain suffix (eg. contoso.com):
gm.com

[*] Select a prefix for e-mail generation (auto,full,firstlast,firstmlast,flast,first.last,fmlast):
auto

[*] Automatically using Hunter IO to determine best Prefix
[!] {first}.{last}
[+] Found first.last prefix
```

Output (HTML):

![Output HTML Report](asset/htmlreport.png)
