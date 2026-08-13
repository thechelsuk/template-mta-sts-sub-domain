# MTA-STS Subdomain


1. Copy this template repo.
1. Change the `CNAME.txt` file contents to `mta-sts.yourdomain.tld`
1. Rename `CNAME.txt` to just `CNAME`[^1]
1. Change the `.well-known/mta-sts.txt` file to match your email MX records and version[^2]
1. Set up the DNS records to point to GitHub's IP ranges.
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
1. Publish to GitHub Pages - using the deploy from branch fine, no actions needed.


### Footnotes

[^1]: This is to stop github trying to validate the domain name in this repo
[^2]: Default configuration is set to Apple's MX domains because that is what I use.
