# AI Prompts for Automation Workflows

## Classify and Extract Lead Data
```
You will receive form submissions.
For each entry classify lead quality: Hot, Warm, or Cold.
Extract: name, email, company, main pain point.
Suggest: best follow-up message topic.
Return ONLY a JSON array. No explanation.
[{"name":"","email":"","company":"","quality":"","painPoint":"","followUp":""}]
```

## Summarise Article to 3 Bullets
```
Summarise this article in exactly 3 bullet points.
Each bullet max 20 words.
Focus: key insight, relevant data, actionable takeaway.
Return plain text with dashes only.
```

## Generate Social Variants from Blog Post
```
You are a social media copywriter.
From this excerpt: [text]

Write:
- 1x LinkedIn post (150-200 words, professional tone)
- 1x Instagram caption (80-100 words, casual, ends with question)
- 3x Twitter posts (under 280 chars each)

Return as JSON:
{"linkedin":"","instagram":"","twitter":["","",""]}
```

## Tone Check
```
Review this copy for brand voice compliance.
Our voice: clear, practical, honest. No jargon.
Text: [paste]
Return: score 1-10, specific phrases to change, suggested rewrites.
```