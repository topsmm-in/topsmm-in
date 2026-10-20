# TopSMM — India's Affordable SMM Panel & Reseller API

![Website](https://img.shields.io/badge/Website-topsmm.in-FF6B35?style=flat-square) ![YouTube](https://img.shields.io/badge/YouTube-%40topsmm__in-FF0000?style=flat-square) ![Telegram](https://img.shields.io/badge/Telegram-topsmm__in-229ED9?style=flat-square) ![Support](https://img.shields.io/badge/Support-24%2F7-00B67A?style=flat-square)

Wholesale social media marketing services for creators, agencies and resellers — Instagram, YouTube, Facebook, Telegram, TikTok and Spotify. Auto start, instant delivery, refill guarantee and a full developer API.

**Website:** https://topsmm.in  **Mirror:** https://masterofsmmpanel.in

## What is an SMM panel?

An SMM panel is a self-serve dashboard where creators, marketing agencies and resellers buy social media marketing services at wholesale rates — followers, likes, views, subscribers, comments and shares — and track every order in real time.

TopSMM is an Indian SMM panel founded in 2019 and operated from Hinjewadi, Pune. It serves customers in India and worldwide, and powers hundreds of smaller reseller panels through its API.

## Services

| Platform | Services available |
| --- | --- |
| Instagram | Followers, Likes, Reel Views, Story Views, Comments, Saves, Live Viewers |
| YouTube | Views, Subscribers, Likes, Watch Time, Shares, Live Stream Viewers |
| Facebook | Page Likes, Followers, Post Likes, Comments, Video Views |
| Telegram | Channel Members, Post Views, Reactions, Votes |
| TikTok | Followers, Likes, Views, Shares, Comments |
| Spotify | Plays, Followers, Monthly Listeners, Playlist Saves |
| Other | Twitter/X, LinkedIn, Threads, Discord, Website Traffic |

## Why resellers choose TopSMM

| Feature | What it means for you |
| --- | --- |
| Auto start | Orders begin processing immediately — no manual approval queue |
| Instant delivery | Most services start within seconds of the order being placed |
| Refill guarantee | Eligible services are refilled free if counts drop inside the guarantee window |
| Mass Order | Submit hundreds of orders in a single paste — built for agencies |
| Drip Feed | Spread delivery over hours or days so growth looks natural |
| Live tracking | Start count, current count and status visible on every order |
| Reseller API | Run your own panel on top of the TopSMM catalogue |
| 24/7 support | WhatsApp, Telegram and an in-dashboard ticket system |

## Reseller API

Every TopSMM account gets an API key from the dashboard. The API is form-encoded over HTTPS and follows the common SMM panel API format, so most existing panel scripts and WordPress plugins work without changes.

Endpoint: `https://topsmm.in/api/v2`

| Action | Parameters |
| --- | --- |
| services | key, action=services |
| balance | key, action=balance |
| add | key, action=add, service, link, quantity |
| status | key, action=status, order |
| refill | key, action=refill, order |

Example request:

```bash
curl -X POST https://topsmm.in/api/v2 \
  -d key=YOUR_API_KEY \
  -d action=add \
  -d service=101 \
  -d link=https://instagram.com/yourprofile \
  -d quantity=1000
```

Full API documentation is available inside the dashboard at https://topsmm.in/api

## Free Hindi tutorials

We publish step-by-step panel tutorials in Hindi on YouTube — account setup, adding funds, placing a first order, Mass Order, Drip Feed and API integration.

YouTube: https://www.youtube.com/@topsmm_in

## Who TopSMM is for

| You are | How TopSMM helps |
| --- | --- |
| A creator | Kick-start reach on a new reel, video or post at a few rupees per thousand |
| A small business | Build social proof on your page before running paid ads |
| A marketing agency | Mass Order and Drip Feed for dozens of client accounts at once |
| A panel owner | Resell the full catalogue through the API with your own pricing |

## Payments

UPI, BharatPe QR, bank transfer, Binance and other crypto options. Funds reflect in the dashboard balance and can be spent across any service.

## Links

| | |
| --- | --- |
| Website | https://topsmm.in |
| Mirror domain | https://masterofsmmpanel.in |
| YouTube | https://www.youtube.com/@topsmm_in |
| Instagram | https://www.instagram.com/grow_with_topsmm/ |
| Facebook | https://www.facebook.com/topsmmin |
| Telegram | https://t.me/topsmm_in |
| Reviews | https://www.trustpilot.com/review/topsmm.in |
| Crunchbase | https://www.crunchbase.com/organization/topsmm |

## Contact

TopSMM, Hinjewadi, Pune, Maharashtra 411057, India

WhatsApp and calls: +91 9455194264  Email: topsmm.in@gmail.com

Support runs 24/7 — WhatsApp, Telegram and the ticket system inside your dashboard.
