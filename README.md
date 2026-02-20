# bug_bounty_methodology



WildCard [Limited] Scop Targets:

collect the subdomains that's have a wildcard from https://crt.sh/ and put them in txt file, then run this command 

`subfinder -dL wildcard_subdomains_Form_crt.txt -all -recursive -o subfinder.txt`

subfinder -d domain.com | alterx | dnsx -o subfinder1.txt


bbot -t evilcorp.com fiscloudservices.com -p subdomain-enum code-enum email-enum spider web-basic --allow-deadly -o bbot.xt


subfinder -d target.com -all -recursive -o subfinder2.txt

### get the ASN 
1- > dig +short Microsoft.com  => this will get the ips for Microsoft.com
2- > whois -h whois.cymru.com " -v ip" => this will get the ASN number for Microsoft
3- > asnmap -a ASnmber -o asnip.txt
4- cat asnip.txt | httpx 

### To Get subdomains using IP range or ASN => you can collect the ASNs from here bgp.he.net  and put them in one file and run this command, 
> prips {ASN IP RANGE} | hakrevdns
> prips 173.0.84.0/24 | hakrevdns
> prips 173.0.84.0/24 | hakip2host


echo "target.com" | subdog --parallel --output domain_subs


sublist3r -d <target.com> -o sublist3r_domains.txt


assetfinder --subs-only example.com > assetfinder.txt

amass enum -passive -d targert.com -o amass.txt 

subfinder -d target.com -silent | httpx -favicon

