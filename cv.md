## Yury Matusevich
****
__Email:__ vfnectdbx78@gmail.com \
__Discord__ madest78 \
__Telegramm:__ @JerzyMatusiewicz \
__Phone number:__ 995 551.170.143
****
<p style="text-indent: 1em;">
Experienced in project automation at a large international company. Currently focused on Front-End development and seeking opportunities to enhance web development skills, contribute to a collaborative team, and achieve professional growth.
</p>

****
### Skills 
<p style="text-indent: 1em;">
Languages
</p>

  * JavaScript
  * TypeScript (learning)
  * HTML5
  * CSS3 

<p style="text-indent: 1em;">
Frameworks / Libraries:
</p>

 * Angular (learning)
 * Vue (learning) 

<p style="text-indent: 1em;">
Tools & Runtimes:
</p>

 * Node.js (basic backend scripting, simple APIs)
 * Deno (TypeScript runtime, scripting, deployment)
 * npm (package management)
 * Slack CLI
 * Google Apps Script

<p style="text-indent: 1em;">
Version Control:
</p>

 * Git
 * GitHub

<p style="text-indent: 1em;">
Other:
</p>

 * Google Sheets API
 * SQL (learning)
 * WordPress/cPanel (site support & customization)

****

### Code Examples

```JS
function scheduleDefaultChoices() {
  // delete old triggers sendDefaultChoices
  const triggers = ScriptApp.getProjectTriggers();
  triggers.forEach(t => {
    if (t.getHandlerFunction() === 'sendDefaultChoices') {
      ScriptApp.deleteTrigger(t);
    }
  });

  // add new 24h trigger
  ScriptApp.newTrigger('sendDefaultChoices')
    .timeBased()
    .after(24 * 60 * 60 * 1000) // 24h
    // .after(1 * 60 * 1000) // 1m from test
    .create();
}
```
****

### Work Experience
<p style="text-indent: 1em;">
Junior Developer / Automation Engineer
Docuscetch (script unit) — (2025)
</p>
<p style="text-indent: 1em;">
We Application (Vue + MariaDB): Developed a Vue.js application connected to MariaDB; implemented form-based data queries, processing logic, and visualization through interactive charts.
</p>
<p style="text-indent: 1em;">
Slack Bots for Automation: Built multiple Slack bots with Deno and Slack CLI for workflow automation and team communication.
</p>
<p style="text-indent: 1em;">
Gamification Project in Slack: Designed and implemented gamified Slack bots styled as NPS characters; bots assigned tasks to teams, facilitated a card game, and rewarded participants.
</p>
<p style="text-indent: 1em;">
Merch Store Website (WordPress + PHP): Updated and customized the company’s internal merchandise store for a new season, including UI/UX adjustments and backend tweaks.
</p>

****
### Education
RSSchool: JavaScript/Front-end 2023Q4
****
English Language (B2)