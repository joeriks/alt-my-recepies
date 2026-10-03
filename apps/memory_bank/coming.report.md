---
label: Coming 30 days
from: { type: dated_entry }
where: { date: { from: today, to: today+30d } }
sort: date
group: date:week
---
# Kommande 30 dagar

{{#each}}
- {{date}}{{#if time}} {{time}}{{/if}}: [{{title}}]({{@link}}) · {{@collection}}
{{/each}}
