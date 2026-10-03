---
label: Responsibilities
from: responsibilities
sort: header
---
# Ansvarsområden

{{#each}}
## [{{header}}]({{@link}})

{{#if description}}
{{description}}

{{/if}}
{{#children under_areas}}
- **{{title}}**{{#if description}}: {{description}}{{/if}}
{{/children}}

{{#children responsibility_logs}}
- {{date}}: {{title}}{{#if note}} – {{note}}{{/if}}
{{/children}}
{{/each}}
