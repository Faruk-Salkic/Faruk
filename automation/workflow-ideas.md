# Automation Notes

## Active Workflows

### Lead Qualification Bot
- Trigger: Form submission
- Flow: Score lead > Clearbit enrich > if score > 70 notify sales in Slack
- Status: Live

### Social Listening Alert
- Trigger: RSS keyword webhook
- Flow: Filter mentions > sentiment check > post to Slack
- Status: Testing

### Monthly Report Generator
- Trigger: 1st of month
- Flow: Pull GA4 data > format > send PDF to client
- Status: In progress

## Ideas Backlog
- [ ] Auto-tag CRM leads by page visits
- [ ] Instagram comment to DM auto-reply
- [ ] Google Ads CTR anomaly alert
- [ ] Competitor price tracker with Slack notify
- [ ] Blog post scheduler from Notion database

## Tips
- Split In Batches node for large lists
- Always wire an Error Workflow for silent failure handling
- HTTP Request: set retry on fail to 3
- Use Set node to clean data before any API call
