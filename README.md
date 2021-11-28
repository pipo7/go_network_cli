# go_network_cli
network cli based on urfave/cli package available on Github here: https://github.com/urfave/cli

Working for ip, cname and mx. Use --help for more info

NAME:
   Website Lookup CLI - Let's you query IPs, CNAMEs, MX records and Name Servers!

USAGE:
   cli [global options] command [command options] [arguments...]

COMMANDS:
   ns       Looks Up the NameServers for a Particular Host
   ip       Looks up the IP addresses for a particular host
   cname    Looks up the CNAME for a particular host
   mx       Looks up the MX records for a particular host
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --help, -h  show help
