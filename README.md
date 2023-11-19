# Free domains for you

For IT enthusiasts who need a temporary domain name or those who can't or don't want to pay for a top level domain 🌍

Available extensions:

- _your-name_**.kiro.pw**
- _your-name_**.other-domain**

> Note that **.pw** are considered global by Google just like **.com**

## How does it work?

1. [Check domain availability](#check-your-domain-availability)
2. [Add your domain to a DNS provider](#add-your-domain-to-a-dns-provider)
3. [Register your domain](#register-a-domain)
4. [Domain renew](#renew-your-domain)

### Important to know

I will make up to 10 subdomains requests for each user, you can use just one DNS record, if you need more, make any donation of 50 cents or more.

### Check your domain availability

Let's say you want the domain **example.kiro.pw**

#### Option 1

Run the following command:

```sh
nslookup -type=ns example.kiro.pw
```

If you see something like **server can't find example.kiro.pw: NXDOMAIN**, your domain is available.

#### Option 2

Check it out at: https://kiro.pw/checker

### Add your domain to a DNS provider

Once you settled on available domain, you need to know which DNS servers to use before you can register it. This is why you need to add it to your DNS provider first.

Here are some DNS providers you can use:

| Provider                                                                     | DNS price | Sign-up bonus                                                              | Where to go (after sign-up)                                                                                            |
| ---------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [Digital Ocean](https://m.do.co/)                              | Free      | [$100](https://m.do.co/)                                     | [Networking > Domains](https://cloud.digitalocean.com/networking/domains)                                              |
| [Linode](https://www.linode.com)  | Free      | [$100](https://www.linode.com/) | [Domains > Create](https://cloud.linode.com/domains/create)                                                            |
| [Vultr](https://www.vultr.com)                                  | Free      | [$100](https://www.vultr.com/)                                 | [DNS > Add domain](https://my.vultr.com/dns/)                                                                          |
| [ClouDNS](https://www.cloudns.net/)                            | Free      | No                                                                         | [DNS Hosting > Create Zone > Master zone](https://www.cloudns.net/main/)                                               |
| [FreeDNS](https://freedns.afraid.org)                                        | Free      | No                                                                         | [Domains > Add A Domain into FreeDNS](https://freedns.afraid.org/domain/add.php)                                       |
| [Hetzner](https://www.hetzner.com/)                                          | Free      | No                                                                         | [DNS > Add zone](https://dns.hetzner.com/add-zone)                                                                     |
| [AWS](https://aws.amazon.com/route53/pricing)                                | Paid      | No                                                                         | [Route 53 > Hosted zones > Create hosted zone](https://console.aws.amazon.com/route53/v2/hostedzones#CreateHostedZone) |
| [Google Cloud](https://cloud.google.com/dns/pricing)                         | Paid      | $300                                                                       | [Cloud DNS > Create a DNS zone](https://console.cloud.google.com/networking/dns/zones/~new)                            |

Unfortunately, you cannot use Cloudflare with these domains because they are in fact subdomains and Cloudflare does not support adding a subdomain as a domain.

### Register a domain

To apply for adding a domain you should [contact via telegram-bot](https://t.me/defaunbot), leaving an application with the domain name, record type (CNAME/A/TXT/other), as well as, if desired, a link to the project or description, or sending screenshots. Such applications are processed with priority.

### Renew your domain

From the account on which the application for the domain was registered - you must send a message with a re-filled application and the text #RENEW


## Abuse

We're trying to make the world a better place, **please don't abuse this system** 🙏

We reserve the right to cancel any domain and ban any user from using this free service if we think the system is being abused for spam, child pornography, illegal activities, racism, bullying, etc.

**If you think a domain is abusing our system, please [contact via telegram-bot](https://t.me/defaunbot)**

