# philippereira.com — DNS records (set at IONOS) → Vercel

Project: phil-pereira-s-projects / philippereira-site (Vercel)
Live deploy: philippereira-site.vercel.app

Set these at IONOS for philippereira.com:

| Type  | Name | Value                                   |
|-------|------|-----------------------------------------|
| A     | @    | 216.198.79.1                            |
| CNAME | www  | d631ec18a9e6c150.vercel-dns-017.com     |

Apex (philippereira.com) 308-redirects to www.philippereira.com (Vercel default).
Remove any existing IONOS parking A record on @ before adding the A above.
