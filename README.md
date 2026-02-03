# Iran Clean CDN IP Lists

![CDN](https://img.shields.io/badge/CDN-Cloudflare%20%7C%20Fastly%20%7C%20Gcore-blue)
![ISP](https://img.shields.io/badge/ISP-Mokhaberat%20%7C%20Respina%20%7C%20Irancell%20%7C%20Shatel%20Mobile-lightgrey)
![Status](https://img.shields.io/badge/Status-Curated%20Lists-success)

A curated collection of **clean, working CDN IPs for Iran**, prepared for easy use.

This repository shares verified IP lists from:
- **Cloudflare**
- **Fastly**
- **Gcore**

Tested manually across some major Iranian ISPs:
- Mokhaberat
- Respina
- Irancell (MTN)
- Shatel Mobile

## Which File Should I Use?

| Your ISP | Recommended File |
|--------|------------------|
| Mokhaberat | `Cloudflare/cf-mkh-ipv4.txt` |
| Irancell (MTN) | `Cloudflare/cf-mtn-ipv4.txt` |
| Respina | `Cloudflare/cf-rsp-ipv4.txt` |
| Shatel Mobile | `Cloudflare/cf-shm-ipv4.txt` |
| Not sure / multiple ISPs | `Fastly/f-aio.txt` or `Gcore/gc-aio.txt` |

**Tip:**  
Cloudflare files are ISP-specific because i use them more.  
Fastly and Gcore are mixed and more general.

## How to Use?

If your config useses these CDNs and stops working, or it's too slow, you might be able to revive them by replacing the address value with one of these IPs.

## File Format

- Plain text (`.txt`)
- One IP per line
- 10 IPs per file
- No comments or metadata

## Update Policy

- Updated when **I** need new clean results
- No fixed schedule - since I scan these IPs for personal use, might as well share them so others can benefit too.

## Disclaimer

- Google.com is your friend if you don't know something, learn to use it
- Results depend on routing and filtering and location
- IPs may stop working at any time
- for educational purpose only
- No guarantees provided
- Use at your own risk

## Contributions / Issues

Don't need / Can't help. It's just a private repo made public.

## License

Public data shared for accessibility.  
No warranty, no liability.
