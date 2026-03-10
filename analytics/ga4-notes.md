# GA4 Setup Notes

> Reference for alooweb.de client onboarding

## Key Events to Track
| Event | Trigger | Priority |
|-------|---------|----------|
| generate_lead | Form submit | High |
| purchase | Thank-you page | High |
| begin_checkout | Cart step | Medium |
| scroll | 90% page depth | Low |
| file_download | Asset click | Medium |
| video_complete | 75% watched | Medium |

## Custom Dimensions
- User type — new vs returning
- Traffic source grouped
- Page category
- CRM lead status via data import

## Standard Looker Studio Report
1. Executive summary
2. Traffic by channel
3. Conversions and funnel
4. SEO tab via Search Console

## Common Setup Issues
- Cross-domain: add all domains under Data Streams
- Referral exclusions: own domain + payment providers
- GA4 uses Engagement Rate, not Bounce Rate
