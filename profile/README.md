# ChurchCRM

**Get your church organized. Keep control of your data.**

ChurchCRM is free, open-source church management software for churches that want to manage people, families, groups, events, attendance, giving, volunteers, and more without subscription fees or vendor lock-in.

**Free. No subscription. Your data is yours.**

Start by [trying the live demo](https://churchcrm.io/demo.html), or [install ChurchCRM](https://churchcrm.io/install.html) on your own hosting. ChurchCRM currently lists 49 supported locales; translation coverage varies by locale.

[![Latest Release](https://img.shields.io/github/v/release/churchcrm/crm?label=Latest%20Release)](https://github.com/ChurchCRM/CRM/releases/latest)
[![GitHub contributors](https://img.shields.io/github/contributors/churchcrm/crm.svg)](https://github.com/ChurchCRM/CRM/graphs/contributors)
[![Discord](https://img.shields.io/badge/Discord-ChurchCRM-5865F2?logo=discord&logoColor=white)](https://discord.gg/tuWyFzj3Nj)
[![License: MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/ChurchCRM/CRM/blob/master/LICENSE)

---

## See ChurchCRM in action

Explore the real workflows churches use every week:

**People & families → Groups → Events & attendance → Giving & financial tracking → Volunteers → Reports**

→ [Try the live demo](https://churchcrm.io/demo.html) · [Install ChurchCRM](https://churchcrm.io/install.html) · [Read the documentation](https://docs.churchcrm.io/)

ChurchCRM is self-hosted and community-maintained. The repositories below are here for contributors, administrators, and anyone who wants to inspect or improve the project.

## Repositories

### Core Application

| Repo | What it is | Who it's for |
|------|-----------|--------------|
| [**CRM**](https://github.com/ChurchCRM/CRM) | The main ChurchCRM application — PHP/Slim 4 backend, Tabler + Bootstrap 5 UI, Propel ORM, Cypress tests | Developers contributing features, bug fixes, and tests |
| [**Docker**](https://github.com/ChurchCRM/Docker) | Standalone Docker Compose setup for self-hosting ChurchCRM | System admins and self-hosters who want a containerized deployment outside of the main repo |

### Web Presence

| Repo | What it is | Who it's for |
|------|-----------|--------------|
| [**ChurchCRM.io**](https://github.com/ChurchCRM/ChurchCRM.io) | The public marketing website at [churchcrm.io](https://churchcrm.io) | Designers and writers improving the homepage, blog, and landing pages |
| [**docs.churchcrm.io**](https://github.com/ChurchCRM/docs.churchcrm.io) | User and administrator documentation at [docs.churchcrm.io](https://docs.churchcrm.io) — built with TypeScript/Docusaurus | Anyone improving guides, tutorials, admin docs, or developer references |

### Extensions & Integrations

| Repo | What it is | Who it's for |
|------|-----------|--------------|
| [**community-plugin-hello-world**](https://github.com/ChurchCRM/community-plugin-hello-world) | Minimal reference plugin — the starting point for building a ChurchCRM community plugin | Plugin authors learning the plugin API and scaffold |
| [**WordPress-ChurchCRM-Calendar**](https://github.com/ChurchCRM/WordPress-ChurchCRM-Calendar) | WordPress plugin that displays ChurchCRM events on a public-facing church website | Developers extending ChurchCRM into WordPress sites |

---

## How the Repos Relate

```
churchcrm.io          ←  public marketing website (ChurchCRM.io repo)
    │
    └─ "Get Started" → docs.churchcrm.io  ←  user & admin docs (docs.churchcrm.io repo)
                             │
                             └─ "For Developers" → github.com/ChurchCRM/CRM  ←  the app itself
                                                         │
                                                         ├─ core plugins  (src/plugins/core/)
                                                         └─ community plugins  (community-plugin-hello-world as template)

Self-hosting → Docker repo  (standalone Compose setup, separate from dev containers in CRM)
Church website integration → WordPress-ChurchCRM-Calendar repo
```

---

## Where to Start

**Using ChurchCRM:**
→ [docs.churchcrm.io](https://docs.churchcrm.io) — installation, configuration, user guides

**Contributing:**
→ Join [Discord](https://discord.gg/tuWyFzj3Nj) and ask what's a good place to start — maintainers will point you to something concrete
→ See [CONTRIBUTING.md](https://github.com/ChurchCRM/CRM/blob/master/CONTRIBUTING.md) for the full contributor guide
→ No code required — translators, writers, testers, and designers are all welcome

**Reporting a bug:**
→ Use **Support → Report an Issue** inside your ChurchCRM installation (auto-captures system info)
→ Or open a [GitHub issue](https://github.com/ChurchCRM/CRM/issues/new/choose) directly

---

## Community

[![Website](https://img.shields.io/badge/Website-churchcrm.io-blue)](https://churchcrm.io/)
[![Discord](https://img.shields.io/badge/Discord-Chat-5865F2?logo=discord&logoColor=white)](https://discord.gg/tuWyFzj3Nj)
[![X / Twitter](https://img.shields.io/badge/X-@getChurchCRM-black?logo=x)](https://x.com/getChurchCRM)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ChurchCRM-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/company/getchurchcrm/)
[![Facebook](https://img.shields.io/badge/Facebook-getChurchCRM-1877F2?logo=facebook&logoColor=white)](https://www.facebook.com/getChurchCRM)

*ChurchCRM is built by volunteers and exists to serve the Church. Every contribution — code, translation, documentation, or feedback — helps a congregation somewhere run a little better.*
