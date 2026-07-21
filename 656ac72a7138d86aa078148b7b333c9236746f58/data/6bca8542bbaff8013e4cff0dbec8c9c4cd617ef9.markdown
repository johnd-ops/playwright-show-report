# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: suite/e2e/dashboard/member-detail.journey.spec.ts >> Settings — team member detail >> "Back to Members" returns to the members list
- Location: suite/e2e/dashboard/member-detail.journey.spec.ts:40:7

# Error details

```
Test timeout of 90000ms exceeded.
```

```
Error: expect(locator).toBeVisible() failed

Locator: getByTestId('member-detail-page')
Expected: visible
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for getByTestId('member-detail-page')

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - generic [ref=e2]:
    - generic [ref=e3]:
      - generic [ref=e5]:
        - img "PlaySpace Logo" [ref=e7]
        - generic [ref=e8]: PlaySpace
      - generic [ref=e10]:
        - link "Home" [ref=e12] [cursor=pointer]:
          - /url: /dashboard/home
          - generic [ref=e14]:
            - img [ref=e15]
            - generic [ref=e18]: Home
        - generic [ref=e19]:
          - generic [ref=e20]: Session Prep
          - link "Video Session" [ref=e21] [cursor=pointer]:
            - /url: /dashboard/session
            - generic [ref=e23]:
              - img [ref=e24]
              - generic [ref=e27]: Video Session
          - link "In-Person Tools" [ref=e28] [cursor=pointer]:
            - /url: /dashboard/in-person-session
            - generic [ref=e30]:
              - img [ref=e31]
              - generic [ref=e34]: In-Person Tools
          - link "Creative Suite" [ref=e35] [cursor=pointer]:
            - /url: /dashboard/creative-suite
            - generic [ref=e37]:
              - img [ref=e38]
              - generic [ref=e44]: Creative Suite
        - generic [ref=e45]:
          - generic [ref=e46]: Your Practice
          - link "Calendar" [ref=e47] [cursor=pointer]:
            - /url: /dashboard/appointments
            - generic [ref=e49]:
              - img [ref=e50]
              - generic [ref=e52]: Calendar
          - link "Clients" [ref=e53] [cursor=pointer]:
            - /url: /dashboard/clients
            - generic [ref=e55]:
              - img [ref=e56]
              - generic [ref=e60]: Clients
          - link "Clinical Notes" [ref=e61] [cursor=pointer]:
            - /url: /dashboard/clinical-notes
            - generic [ref=e63]:
              - img [ref=e64]
              - generic [ref=e66]: Clinical Notes
          - link "Forms" [ref=e67] [cursor=pointer]:
            - /url: /dashboard/forms
            - generic [ref=e69]:
              - img [ref=e70]
              - generic [ref=e73]: Forms
        - generic [ref=e74]:
          - generic [ref=e75]: Discover
          - link "Community" [ref=e76] [cursor=pointer]:
            - /url: /dashboard/community
            - generic [ref=e78]:
              - img [ref=e79]
              - generic [ref=e83]: Community
      - generic [ref=e84]:
        - button "What's new — version 0.16.0" [ref=e85] [cursor=pointer]:
          - generic [ref=e87]: v0.16.0
          - generic [ref=e88]: What's new
        - link "Settings" [ref=e89] [cursor=pointer]:
          - /url: /dashboard/settings
          - generic [ref=e90]:
            - img [ref=e91]
            - generic [ref=e94]: Settings
    - generic [ref=e95]:
      - banner [ref=e96]:
        - generic [ref=e97]:
          - button "Collapse sidebar" [ref=e98] [cursor=pointer]:
            - img [ref=e99]
          - navigation "Breadcrumb" [ref=e103]:
            - link "Settings" [ref=e104] [cursor=pointer]:
              - /url: /dashboard/settings
            - img [ref=e105]
            - generic [ref=e107]: Profile
        - button "SE Shard 2 E2E" [ref=e109] [cursor=pointer]:
          - generic [ref=e111]: SE
          - generic [ref=e112]: Shard 2 E2E
          - img [ref=e113]
      - main [ref=e115]:
        - generic [ref=e116]:
          - complementary [ref=e117]:
            - navigation [ref=e119]:
              - generic [ref=e120]:
                - heading "Account & Billing" [level=3] [ref=e121]
                - navigation [ref=e122]:
                  - link "My Profile" [ref=e123] [cursor=pointer]:
                    - /url: /dashboard/settings/profile
                  - link "Subscription" [ref=e124] [cursor=pointer]:
                    - /url: /dashboard/settings/subscription
              - generic [ref=e125]:
                - heading "Your Practice" [level=3] [ref=e126]
                - navigation [ref=e127]:
                  - link "Appointment Settings" [ref=e128] [cursor=pointer]:
                    - /url: /dashboard/settings/appointments
                  - link "Client Onboarding" [ref=e129] [cursor=pointer]:
                    - /url: /dashboard/settings/client-onboarding
                  - link "Invoices & Payments" [ref=e130] [cursor=pointer]:
                    - /url: /dashboard/settings/invoices
                  - link "Clinical Note Templates" [ref=e131] [cursor=pointer]:
                    - /url: /dashboard/settings/note-templates
          - main [ref=e132]:
            - generic [ref=e134]:
              - heading "My Profile" [level=1] [ref=e135]
              - generic [ref=e136]:
                - generic [ref=e137]:
                  - generic [ref=e139]: Basics
                  - generic [ref=e141]:
                    - generic [ref=e142]:
                      - text: First Name
                      - paragraph [ref=e143]: Shard 2
                    - generic [ref=e144]:
                      - text: Last Name
                      - paragraph [ref=e145]: E2E
                    - generic [ref=e146]:
                      - text: Email
                      - paragraph [ref=e147]: johnd+shard2@playspace.health
                    - generic [ref=e148]:
                      - text: Phone Number
                      - paragraph [ref=e149]: "+639292957085"
                - generic [ref=e150]:
                  - generic [ref=e152]: Address
                  - generic [ref=e154]:
                    - generic [ref=e155]:
                      - text: Street Address
                      - paragraph [ref=e156]: Not provided
                    - generic [ref=e157]:
                      - text: Apartment, Suite, Box Number, etc.
                      - paragraph [ref=e158]: Not provided
                    - generic [ref=e159]:
                      - text: City/Town
                      - paragraph [ref=e160]: Not provided
                    - generic [ref=e161]:
                      - text: Country
                      - paragraph [ref=e162]: Albania
                    - generic [ref=e163]:
                      - text: State/Province/Region
                      - paragraph [ref=e164]: Not provided
                    - generic [ref=e165]:
                      - text: Timezone
                      - paragraph [ref=e166]: Asia/Manila
                    - generic [ref=e167]:
                      - text: Postal Code
                      - paragraph [ref=e168]: M5V3A8
                - generic [ref=e169]:
                  - generic [ref=e170]:
                    - generic [ref=e171]: Password
                    - generic [ref=e172]: Change your account password
                  - generic [ref=e174]:
                    - paragraph [ref=e175]: "********"
                    - button "Change Password" [ref=e176] [cursor=pointer]
              - button "Edit" [ref=e178] [cursor=pointer]
  - region "Notifications (F8)":
    - list
  - region "Notifications alt+T"
  - alert [ref=e179]
  - iframe [ref=e180]:
    
  - button "Open Intercom Messenger" [ref=e181] [cursor=pointer]:
    - img [ref=e183]
    - generic:
      - img
```

# Test source

```ts
  1  | import { test, expect } from '@playwright/test';
  2  | import { MemberDetailPage } from '../../../pages/MemberDetailPage';
  3  | 
  4  | // QA journey — team Member Detail (/dashboard/settings/members/<memberId>).
  5  | //
  6  | // Closes a zero-coverage gap: the members LIST is covered, but the per-member
  7  | // DETAIL page had no spec. Read-only view of a clinic team member.
  8  | //
  9  | // Grounded live (staging 2026-07-01): member ids come from GET /api/clinic
  10 | // (practitioners[].id); the page fetches GET /api/clinic/members/<id> and
  11 | // renders Basics + Address; an invalid id shows the error state; "Back to
  12 | // Members" routes to /dashboard/settings/members.
  13 | //
  14 | // Artifacts disabled file-wide — the page shows a team member's personal
  15 | // details (name/email/phone/address).
  16 | //
  17 | // No snapshot assertion: data-driven personal details.
  18 | 
  19 | test.use({ screenshot: 'off', video: 'off', trace: 'off' });
  20 | 
  21 | test.describe('Settings — team member detail', () => {
  22 |   // Settings pages are slow to hydrate on shared staging and the POM's
  23 |   // navigation reload-retry needs headroom beyond the 30s suite default.
  24 |   test.describe.configure({ timeout: 90_000 });
  25 | 
  26 |   test('renders a member’s details (Basics + Address)', async ({ page, request }) => {
  27 |     const memberId = await MemberDetailPage.firstMemberId(request);
  28 |     const md = new MemberDetailPage(page);
  29 |     await md.goto(memberId);
  30 | 
  31 |     await expect(md.detailPage).toBeVisible({ timeout: 30_000 });
  32 |     await expect(md.nameDisplay).toBeVisible();
  33 |     await expect(md.basicsSection).toBeVisible();
  34 |     await expect(md.emailDisplay).toBeVisible();
  35 |     await expect(md.roleDisplay).toBeVisible();
  36 |     await expect(md.statusDisplay).toBeVisible();
  37 |     await expect(md.addressSection).toBeVisible();
  38 |   });
  39 | 
  40 |   test('"Back to Members" returns to the members list', async ({ page, request }) => {
  41 |     const memberId = await MemberDetailPage.firstMemberId(request);
  42 |     const md = new MemberDetailPage(page);
  43 |     await md.goto(memberId);
> 44 |     await expect(md.detailPage).toBeVisible({ timeout: 30_000 });
     |                                 ^ Error: expect(locator).toBeVisible() failed
  45 | 
  46 |     await md.backButton.click();
  47 |     await expect(page).toHaveURL(/\/dashboard\/settings\/members\/?$/, { timeout: 30_000 });
  48 |   });
  49 | 
  50 |   test('an invalid member id shows the error state (not the detail)', async ({ page }) => {
  51 |     const md = new MemberDetailPage(page);
  52 |     await md.goto('00000000-0000-0000-0000-000000000000');
  53 | 
  54 |     await expect(
  55 |       md.errorState,
  56 |       'an unknown member id must surface the error state',
  57 |     ).toBeVisible({ timeout: 30_000 });
  58 |     await expect(md.detailPage).toHaveCount(0);
  59 |   });
  60 | });
  61 | 
```