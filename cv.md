## Yury Matusevich
****
Email vfnectdbx78@gmail.com
Telegramm @JerzyMatusiewicz
Phone number 995 551.170.143
****
Experienced in project automation at a large international company. Currently focused on Front-End development and seeking opportunities to enhance web development skills, contribute to a collaborative team, and achieve professional growth.
****
Skills
Languages: JavaScript, TypeScript (learning), HTML5, CSS3
Frameworks / Libraries: Angular (learning), Vue (learning)
Tools & Runtimes: Node.js (basic backend scripting, simple APIs), Deno (TypeScript runtime, scripting, deployment), npm (package management), Slack CLI, Google Apps Script
Version Control: Git, GitHub
Other: Google Sheets API, SQL (learning), WordPress/cPanel (site support & customization)
****
Code Examples
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
****
Work Experience

Junior Developer / Automation Engineer
Docuscetch (script unit) — (2025)

Web Application (Vue + MariaDB): Developed a Vue.js application connected to MariaDB; implemented form-based data queries, processing logic, and visualization through interactive charts.

Slack Bots for Automation: Built multiple Slack bots with Deno and Slack CLI for workflow automation and team communication.

Gamification Project in Slack: Designed and implemented gamified Slack bots styled as NPS characters; bots assigned tasks to teams, facilitated a card game, and rewarded participants.

Merch Store Website (WordPress + PHP): Updated and customized the company’s internal merchandise store for a new season, including UI/UX adjustments and backend tweaks.
****
Education
RSSchool JavaScript/Front-end 2023Q4
****
English Language (B2)