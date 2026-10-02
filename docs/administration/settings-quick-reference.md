---
title: Settings Quick Reference
sidebar_position: 9
---

# Settings Quick Reference — Where to Find Everything

This page lets you quickly find where any setting is located in the ChurchCRM UI. Organized by the most common tasks.

## 👥 People & Registration

| I want to... | Location | Setting |
|---|---|---|
| Enable visitor self-registration | People → Admin → People Settings → New Members & Greeting | Self-Registration |
| Choose who is emailed about new people and families | People → Admin → People Settings → New Members & Greeting | Notification Recipients |
| Add a greeting to the new-member email | People → Admin → People Settings → New Members & Greeting | Greeter Message 1 / 2 |
| Hide deceased people from exports | People → Admin → People Settings → People | Hide Deceased from Directory |
| Change how names display (format) | People → Admin → People Settings → People | Person name display style |
| Change person avatar initials | People → Admin → People Settings → People | Person initials style |
| Set default country for new families | Admin → Church Info | Default country |
| Set default city | Admin → Church Info | Default city |
| Set default state | Admin → Church Info | Default state |
| Set default ZIP code | Admin → Church Info | Default ZIP code |
| Disable "Friend Date" field | People → Admin → People Settings → People | Hide Friend Date |
| Disable "Wedding Date" field | People → Admin → People Settings → Families | Hide Wedding Date |
| Auto-uppercase ZIP codes | People → Admin → People Settings → Families | Uppercase Zip/Postcodes |
| Choose which family roles are head, spouse and child | People → Admin → People Settings → Families | Head of House / Spouse / Child Role |
| Mark a classification as inactive | People → Admin → Person Classifications | Inactive column |
| Choose which classifications start ticked on the Directory report | People → Admin → Person Classifications | In Directory column |

## 🏛️ Church Information

| I want to... | Location | Setting |
|---|---|---|
| Set church name | Admin → Church Info | Church name |
| Add church address | Admin → Church Info | Address, City, State, ZIP |
| Set church phone/email | Admin → Church Info | Phone, Email |
| Add church website | Admin → Church Info | Website |
| Upload church logo for emails | Admin → Church Info | Logo URL |

## 🗺️ Maps & Location

| I want to... | Location | Setting |
|---|---|---|
| Set initial map zoom level | People → Map → Map Settings | Map default zoom level |
| Set map center point | Admin → Church Info | Latitude/Longitude |
| Hide lat/lon fields from users | People → Map → Map Settings | Hide latitude/longitude |

## 💰 Finance & Donations

| I want to... | Location | Setting |
|---|---|---|
| Enable/disable Finance module | Admin → System Settings → Finance | Enable Finance module |
| Enable/disable Fundraiser module | Admin → System Settings → Finance | Enable Fundraiser module |
| Set fiscal year start month | Admin → System Settings → Finance | Fiscal year start month |
| Set currency symbol | Admin → Localization & Formats | Currency symbol |
| Set currency position ($ before or after) | Admin → Localization & Formats | Currency position |
| Use numbered donation envelopes | Admin → System Settings → Finance | Use donation envelopes |
| Track scanned check images | Admin → System Settings → Finance | Scanned check images |
| Allow non-deductible donations | Admin → System Settings → Finance | Non-deductible donations |

## 🌍 Language & Localization

| I want to... | Location | Setting |
|---|---|---|
| Change application language | Admin → Localization & Formats | Language / I18n |
| Set church time zone | Admin → Localization & Formats | Time zone |
| Change date display format | Admin → Localization & Formats | Date format |
| Set number formats (decimals, thousands) | Admin → Localization & Formats | Decimal separator, Thousands separator |
| Set phone number format | Admin → Localization & Formats | Phone number format |

## 📧 Email Setup

| I want to... | Location | Setting |
|---|---|---|
| Enable/disable email sending | Admin → System Settings → Email | Enable/disable email |
| Configure SMTP server | Admin → System Settings → Email | SMTP host, port |
| Set sender name/address | Admin → System Settings → Email | Sender name, Sender address |
| Set reply-to address | Admin → System Settings → Email | Reply-to address |
| Set default email recipient | Admin → System Settings → Email | Church email address |
| Configure email encryption (TLS/SSL) | Admin → System Settings → Email | TLS/SSL encryption |

## 🔐 Security & Passwords

| I want to... | Location | Setting |
|---|---|---|
| Set minimum password length | Admin → Security & Permissions | Minimum password length |
| Force password changes | Admin → Security & Permissions | Password change requirement |
| Block common passwords | Admin → Security & Permissions | Disallowed passwords |
| Lock account after failed logins | Admin → Security & Permissions | Max failed logins |
| Set session timeout | Admin → Security & Permissions | Session timeout |
| Require two-factor authentication (2FA) | Admin → Security & Permissions | Require 2FA |
| Set 2FA enrollment grace period | Admin → Security & Permissions | 2FA grace period |
| Enable CSP (XSS protection) | Admin → System Settings → Advanced | Enforce CSP |

## 🔔 Notifications

| I want to... | Location | Setting |
|---|---|---|
| Notify someone when new family added | Admin → System Settings | New member notification recipients |
| Include contact details in notifications | Admin → System Settings | Include data in notifications |
| Send birthday greeting emails | Admin → System Settings | Birthday emails |
| Alert on missed background jobs | Admin → System Settings | Background jobs warning |

## 🔍 Search & Discovery

| I want to... | Location | Setting |
|---|---|---|
| Show/hide people in search | Admin → System Settings → Search | Search people |
| Show/hide families in search | Admin → System Settings → Search | Search families |
| Show/hide groups in search | Admin → System Settings → Search | Search groups |
| Show/hide donations in search | Admin → System Settings → Search | Search deposits, Search payments |
| Limit search results | Admin → System Settings → Search | Max results per category |

## 🎨 Display & UI

| I want to... | Location | Setting |
|---|---|---|
| Control PDF handling (save vs open) | Admin → System Settings → Advanced | PDF output type |
| Show fundraiser menu | Admin → System Settings → Finance | Enable Fundraiser module |
| Show Sunday School in menu | Admin → System Settings → Advanced | Enable Sunday School module |
| Show Events in menu | Admin → System Settings → Advanced | Enable Events module |
| Show/hide specific field types | People → Admin → People Settings | Hide Address Without Family, Hide Friend Date, Hide Wedding Date |

## 📊 Reporting & Exports

| I want to... | Location | Setting |
|---|---|---|
| Exclude deceased from printed directory | People → Admin → People Settings → People | Hide Deceased from Directory |
| Hide family newsletter subscription field | People → Admin → People Settings → Families | Hide Newsletter Subscriptions |
| Control page margins/spacing in reports | Admin → System Settings → Reports | Left margin, Line thickness |

## 🛠️ Advanced & Developer

| I want to... | Location | Setting |
|---|---|---|
| Change application log level | Admin → System Settings → Advanced | Log severity level |
| Enable external calendar API | Admin → System Settings → Advanced | Enable external calendar API |
| Set calendar embedding origins | Admin → System Settings → Advanced | Calendar embed origins |
| Allow pre-release upgrades | Admin → System Settings → Advanced | Allow pre-release upgrades |
| Change telemetry sharing level | Admin → System Settings → Advanced | Telemetry level |

---

## Settings by Location

Quick reference of which admin page contains each setting category:

| Location | Contains |
|----------|----------|
| **Admin → Church Info** | Church name, address, contact info, logo |
| **Admin → Localization & Formats** | Language, timezone, date/time/number formats |
| **Admin → Security & Permissions** | Password rules, session timeout, 2FA |
| **Admin → System Settings → Email** | SMTP configuration, sender info, email features |
| **Admin → System Settings → Finance** | Currency, fiscal year, donation options |
| **Admin → System Settings → Search** | Search scope and result limits |
| **Admin → System Settings → Advanced** | Logging, APIs, features, telemetry |
| **People → Admin → People Settings** | Name and initials style, hidden fields, family roles, self-registration, new-member notifications and greeter messages |
| **People → Admin → Person Classifications** | Classification names and order, Inactive and In Directory flags |
| **People → Map → Map Settings** | Map zoom level |

---

## See Also

- **[System Settings & Configuration](./system-settings.md)** — Full descriptions of all settings
- **[Email Setup](./email-setup.md)** — Complete email configuration guide
- **[Localization & Formats](./localization.md)** — Language and format details
- **[Security](./security.md)** — Security policies and user permissions
