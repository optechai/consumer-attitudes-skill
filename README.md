# Consumer Attitudes Toward AI Customer Support by Lorikeet: Claude Skill

Ask Claude whether customers really want AI support instead of reading the report.

This skill gives Claude the full [Consumer Attitudes Toward AI Customer Support](https://www.lorikeetcx.ai/content/consumer-attitudes-toward-ai-cs-report?utm_source=github&utm_medium=referral&utm_campaign=ai-cs-report-april-2026&utm_content=skill-readme) report by [Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=ai-cs-report-april-2026&utm_content=skill-readme): a survey of 1,083 consumers in 8 countries across the US and Europe, collected April 7, 2026, on when people prefer AI or human customer support.

## What you can ask

- **Get the numbers.** "Do customers actually prefer human support over AI?"
- **Size it for your business.** "We take 40,000 contacts a month and our queue averages 20 minutes. How many customers would choose AI?"
- **Score your setup.** Describe your support setup and ask "Where should we put AI first?" Claude scores it against the report's findings (wait time, sensitive topics, context, complexity, hand-off) and ranks your next 3 steps.
- **Decide what to do.** "Should we keep billing and health questions away from AI?"

Claude answers with the report's figures and its caveats: stated preference vs. the tradeoff question, which figures are combined, and what the data can't tell you.

Once installed, call it directly with `/consumer-attitudes-report`, for example: `/consumer-attitudes-report Where should we put AI first in our support?`

## What's inside

- All three findings: wait time is the lever, privacy is an AI advantage, AI support is brand equity
- Chart data: stated preference vs. actual choice, queue abandonment by wait time, sensitive topics, the value of memory, good-experience and brand impact, why people prefer humans, acceptance by scenario, outcome vs. channel
- Methodology, the SageSure and Eucalyptus customer stories, and the five implications for CX leaders

## Install

### Claude.ai (web, desktop)

1. Download [`consumer-attitudes-report.zip`](https://github.com/optechai/consumer-attitudes-skill/raw/main/consumer-attitudes-report.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/optechai/consumer-attitudes-skill.git /tmp/consumer-attitudes-skill \
  && cp -r /tmp/consumer-attitudes-skill/consumer-attitudes-report ~/.claude/skills/
```

## Methodology

1,083 consumers from Prolific's verified panel, across the US, UK, Germany, France, Netherlands, Ireland, Spain and Italy, collected April 7, 2026. One survey wave with no per-country or demographic breakdowns. Full methodology is in the [report](https://www.lorikeetcx.ai/content/consumer-attitudes-toward-ai-cs-report?utm_source=github&utm_medium=referral&utm_campaign=ai-cs-report-april-2026&utm_content=skill-readme-methodology).

## About Lorikeet

[Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=ai-cs-report-april-2026&utm_content=skill-readme-about) is an AI customer support platform for complex and regulated businesses, with AI agents that work across voice, chat and email.
