---
title: System Settings & Configuration
sidebar_position: 8
---

# System Settings & Configuration

ChurchCRM's settings are spread across multiple locations for intuitive access. This page is your comprehensive guide to finding and configuring every system setting.

:::tip Quick Navigation
Use this guide to find where any setting is configured:
- **Church Information** — Admin → Church Info
- **People Settings** — People → Admin → People Settings
- **Map Settings** — People → Map → Map Settings button
- **Localization & Formats** — Admin → Localization & Formats
- **Email Configuration** — Admin → System Settings → Email tab
- **Security** — Admin → Security & Permissions
- **Advanced Settings** — Admin → System Settings
:::

---

## Church Information

**Location:** Admin → Church Info

Configure basic church details that appear throughout ChurchCRM.

| Setting | Description | Required |
|---------|-------------|----------|
| **Church name** | Displayed in headers, emails, PDF reports | ✅ Yes |
| **Address** | Street address for geocoding and mail |  |
| **City, State, ZIP** | Used for church location on maps |  |
| **Country** | Church location country |  |
| **Phone** | Shown on contact pages and auto-emails |  |
| **Email** | Primary contact email |  |
| **Website** | Church website URL |  |
| **Logo URL** | HTTPS URL for logo in emails (3.5:1 aspect ratio recommended) |  |

:::note
Church name is **required** and will be requested on first setup. Many features require this to be configured.
:::

---

## People Settings

**Location:** People → Admin → People Settings (admin-only). The same **People Settings** button is in the header of the People Dashboard and of every People admin page.

The page opens with shortcuts to the People lists and editors (Person Classifications, Person Properties, Person Custom Fields, Family Roles, Family Properties, Family Custom Fields, Volunteer Opportunities), followed by three groups of settings.

:::tip Changes save automatically
There is no Save button. Each setting saves as soon as you change it and a "Settings saved successfully" message confirms it. Text boxes save when you click out of them.
:::

### People

| Setting | Description | Default |
|---------|-------------|---------|
| **Person name display style** | How names are written (for example FirstName MiddleName LastName, or LastName, Title FirstName) | FirstName MiddleName LastName |
| **Person initials style** | Avatar initials: one character from first and last name, or two from the first name | First + Last |
| **Hide Address Without Family** | Hide the address field for people who are not in a family | On |
| **Hide Friend Date** | Hide the Friend Date field in the Person Editor | Off |
| **Hide Deceased from Directory** | Leave deceased members out of printed directories and CSV exports | On |

### Families

| Setting | Description | Default |
|---------|-------------|---------|
| **Head of House Role** | The family role that counts as head of household | Head of Household |
| **Spouse Role** | The family role that counts as spouse | Spouse |
| **Child Role** | The family role that counts as a child | Child |
| **Hide Wedding Date** | Hide the Wedding Date field in the Family Editor | Off |
| **Hide Newsletter Subscriptions** | Hide newsletter subscription management in the Family Editor | Off |
| **Uppercase Zip/Postcodes** | Save zip and postal codes in UPPERCASE | Off |

### New Members & Greeting

| Setting | Description | Default |
|---------|-------------|---------|
| **Self-Registration** | Allow visitors to register their own family. When enabled, a link appears on the login page. | Off |
| **Notification Recipients** | The people who get an email when a new person or family is added. Search and pick them by name. | None |
| **Include Details in Notifications** | Add contact and demographic details to that email | Off |
| **Greeter Message 1 / 2** | Up to 255 characters each, shown near the end of the notification email. Line breaks are kept. | Empty |

### Settings that live on the classification list

Two settings are columns on the **Person Classifications** editor (People → Admin → Person Classifications), not on this page. See [Classifications](../user-guide/classifications.md).

- **Inactive**: people in this classification are treated as inactive
- **In Directory**: this classification starts ticked on the Directory report

---

## Default Location and Map Fields

| Setting | Where | Description |
|---------|-------|-------------|
| **Default country, city, state, ZIP code** | Admin → Church Info | Pre-fill the address fields on new person and family forms |
| **Hide latitude/longitude** | People → Map → Map Settings | Hide the manual geocoding fields (background geocoding still runs) |

---

## Map Settings

**Location:** People → Map → Click **"Map Settings"** button (admin-only)

ChurchCRM uses **Leaflet + Nominatim (OpenStreetMap)** — no API key required.

| Setting | Description | Default |
|---------|-------------|---------|
| **Map default zoom level** | Starting zoom when opening maps (Continent → Street) | City (10) |

For full mapping configuration, see [Maps & Geocoding](./maps-and-geocoding.md).

---

## Localization & Formats

**Location:** Admin → Localization & Formats

:::info
See the dedicated [Localization & Formats](./localization.md) guide for complete details.
:::

| Setting | Description |
|---------|-------------|
| **Language / I18n** | Application language (English, Spanish, French, German, etc.) |
| **Time zone** | Church time zone for events and scheduling |
| **Date format** | How dates display (MM/DD/YYYY, DD/MM/YYYY, etc.) |
| **Date picker format** | Date format in picker widgets |
| **Currency symbol** | $ € £ etc. |
| **Currency position** | Symbol before or after amount |
| **Thousands separator** | , or . |
| **Decimal separator** | . or , |
| **Phone number format** | (999) 999-9999 or other format |

---

## Email Configuration

**Location:** Admin → System Settings → Email tab

See [Email Setup](./email-setup.md) for detailed configuration instructions.

| Setting | Description |
|---------|-------------|
| **Enable/disable email** | Turn email sending on or off |
| **SMTP host** | Your outbound mail server (mail.example.com:25) |
| **SMTP port** | Default 25, 465 (SSL), or 587 (TLS) |
| **SMTP authentication** | Enable if server requires username/password |
| **SMTP username** | Login for authenticated SMTP |
| **SMTP password** | Password for authenticated SMTP |
| **Sender name** | "From:" display name in outbound emails |
| **Sender address** | "From:" email address |
| **Reply-to address** | Optional separate reply-to address |
| **TLS/SSL encryption** | Connection encryption mode |
| **Church email address** | Auto-added as removable recipient in Email Composer |
| **Email preheader** | Short text shown in email previews (optional) |

---

## Finance & Donations

**Location:** Admin → System Settings → Finance tab

| Setting | Description | Default |
|---------|-------------|---------|
| **Enable Finance module** | Show/hide Finance in sidebar | On |
| **Enable Fundraiser module** | Show/hide Fundraiser in sidebar | On |
| **Fiscal year start month** | Month your financial year begins (Jan-Dec) | January |
| **Currency symbol** | $ € £ CHF etc. | $ |
| **Currency position** | Before or after amount | Before |
| **Use donation envelopes** | Track contributions via numbered envelopes | Off |
| **Checks per deposit slip** | How many check line items per deposit form | 14 |
| **Scanned check images** | Allow attaching scanned check images | Off |
| **Non-deductible donations** | Allow recording non-tax-deductible gifts | Off |

---

## Security Settings

**Location:** Admin → Security & Permissions

For comprehensive security guidance, see [Security](./security.md).

| Setting | Description | Default |
|---------|-------------|---------|
| **Minimum password length** | Characters required in user passwords | 8 |
| **Password change difference** | # of characters that must change | 4 |
| **Disallowed passwords** | Passwords that can never be used | password, god, jesus, church, christian |
| **Max failed logins** | Attempts before account locks | 5 |
| **Session timeout** | Minutes before idle logout | 60 |
| **Require 2FA** | Mandate two-factor authentication | Off |
| **2FA grace period** | Days to enroll before 2FA enforcement | 7 days |
| **2FA app name** | Name shown in authenticator apps | ChurchCRM |
| **Enforce CSP** | Content Security Policy (XSS protection) | Report only |

---

## Search & Discovery

**Location:** Admin → System Settings → Search tab

Control what appears in the global search.

| Setting | Description | Default |
|---------|-------------|---------|
| **Search people** | Include people in search results | On |
| **Search families** | Include families in search | On |
| **Search family head of house names** | Show family HOH names | On |
| **Search groups** | Include groups | On |
| **Search deposits** | Include financial deposits | On |
| **Search payments** | Include donation payments | On |
| **Search addresses** | Include address records | On |
| **Search calendar events** | Include events | On |
| **Max results per category** | Limit search results (15, 5, etc.) | Varies by type |

---

## Notifications & Automation

**Location:** Admin → System Settings

| Setting | Description | Default |
|---------|-------------|---------|
| **New member notification** | An email goes to the Notification Recipients when a family or person is added (set under [People Settings](#new-members--greeting)) | Off until recipients are chosen |
| **Birthday emails** | Auto-send birthday greeting emails (Admin → Feature Toggles) | Off |
| **Background jobs warning** | Alert admin if scheduled tasks haven't run (hours) | 26 |
| **Background jobs interval** | Minimum minutes between timer job runs | 15 |

---

## Advanced & Expert Settings

**Location:** Admin → System Settings → Advanced tab

These settings are for advanced users and developers.

| Setting | Description | Default |
|---------|-------------|---------|
| **Log severity level** | App log level (DEBUG, INFO, WARNING, ERROR) | INFO |
| **PDF output type** | Save dialog vs open in browser | Save dialog |
| **Event log queries** | Query IDs requiring finance permissions |  |
| **Telemetry level** | Anonymous diagnostic data sharing | None |
| **Enforce CSP** | Enforce Content Security Policy headers | Report-only |
| **Enable external calendar API** | Allow public calendar embedding | Off |
| **Calendar embed origins** | Origins allowed to embed calendar (CSP) | * (any) |
| **Allow pre-release upgrades** | Update to pre-release versions | Off |
| **Display distance in** | Miles or kilometers | Miles |

---

## Related Pages

- [Localization & Formats](./localization.md) — Language, timezone, date/number formats
- [Email Setup](./email-setup.md) — Complete email configuration guide
- [Maps & Geocoding](./maps-and-geocoding.md) — Church location and mapping
- [Security](./security.md) — Security policies and user permissions
- [Users](./users.md) — User account management
- [Plugins](./plugins/index.md) — Community plugins and integrations
