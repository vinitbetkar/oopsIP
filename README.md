# oopsIP

![bartalom](https://github.com/vinitbetkar/oopsIP/assets/114536926/fee21440-0222-4865-a4f5-41bc6c15fbef)


## Overview
This script provides a convenient way to extract IPv4 addresses associated with a given domain by utilizing multiple DNS resolution tools. The script supports various options for customization and includes the ability to save results to a file.
 


## Features
- Supports DNS resolution using `dig`, `host`, and `nslookup` tools.
- Provides an option to specify the domain for DNS resolution.
- Allows saving the results to a specified output file.
- Removes duplicates and sorts the obtained IPv4 addresses.

## Usage

./oopsIP -d example.com -o output.txt

Installation

1. Clone the repository
  git clone https://github.com/vinitbetkar/oopsIP.git
2. Navigate to the Folder
   cd oopsIP
3. Change Permisssion
  chmod +x *
4. USage
   ./oopsIP -d target.com -o outputfile.txt 
  

   

Dependencies
dig, host, nslookup: DNS resolution tools
awk: Text processing tool

Screen Shots


![image](https://github.com/vinitbetkar/oopsIP/assets/114536926/acb65524-b619-4ecb-82a4-724adb1263f0)
