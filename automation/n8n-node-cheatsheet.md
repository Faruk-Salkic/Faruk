# n8n Node Quick Reference

## Trigger Nodes
| Node | Use for |
|------|---------|
| Schedule Trigger | Run at fixed times |
| Webhook | Receive data from external apps |
| Email Trigger | Trigger on new email |
| Form Trigger | Collect form submissions |

## Data Nodes
| Node | Use for |
|------|---------|
| Set | Create or overwrite fields |
| Code | Custom JavaScript |
| If | Branch on condition |
| Switch | Multiple branches |
| Merge | Combine two streams |
| Split In Batches | Process large lists safely |

## Key Integrations
| Node | Use for |
|------|---------|
| HTTP Request | Call any API |
| Google Sheets | Read and write spreadsheets |
| Gmail | Send emails |
| Slack | Post messages |
| Notion | Manage databases |
| GitHub | Commit files, create issues |

## Expression Cheatsheet
- Current field: {{ $json.fieldName }}
- Named node: {{ $("NodeName").item.json.field }}
- Current time: {{ $now.toFormat("yyyy-MM-dd") }}
- Item count: {{ $items().length }}

## Error Handling Tips
- Set Continue on Error on nodes that might fail
- Add Error Trigger workflow for failure notifications
- Use IF node to validate API response before processing