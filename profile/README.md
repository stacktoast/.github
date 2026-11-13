<div align="center">

# Stack Toast: the Laravel SaaS starter kit

### Build the part people pay you for.

Auth, subscription billing, teams and an admin panel, already connected.<br>
Pick Livewire, React, Vue or API, install with one command and start on your product.

**[Get Stack Toast](https://stacktoast.com/#pricing)** &nbsp;·&nbsp; [Tour the features](https://stacktoast.com/features/) &nbsp;·&nbsp; [How building and updating works](https://stacktoast.com/build-and-update/)

<a href="https://stacktoast.com/"><img src="https://stacktoast.com/screenshots/livewire--admin-dashboard-demo.png" alt="Stack Toast admin dashboard: MRR, ARR, churn and subscription metrics in a Laravel SaaS boilerplate" width="860"></a>

| 200+ | 4 | 22 | 21 |
| :---: | :---: | :---: | :---: |
| features in every edition | payment processors behind one interface | business metrics in the admin panel | screens already built |

</div>

## A Laravel SaaS boilerplate that covers the whole business

Your first customer needs more than your best feature. They need to sign in,
pay, invite a teammate and manage their account, and you need to run the
business behind it. Stack Toast is a Laravel SaaS boilerplate with full source
code that connects both sides, so your first week goes into your product
instead of into webhooks.

### Subscription billing with Stripe, Paddle, Lemon Squeezy and Coinbase Commerce

From first checkout to the next renewal, already wired together.

- Recurring subscriptions, one-time payments and trials
- Cancel, pause and resume, with cancellation grace periods
- Coupons, multi-currency payments, invoice PDFs and VAT number capture
- Signed webhooks with duplicate-event protection
- Unfinished checkout recovery, so a customer has a way back to pay
- Your own payment processor through a documented interface

<img src="https://stacktoast.com/screenshots/livewire--billing.png" alt="Laravel subscription billing screen with plans, invoices and payment method" width="860">

### Authentication that is easy to sign in to and hard to take over

- Email and password, social login, magic links and email PIN sign-in
- Two-factor authentication by TOTP, SMS or email, with recovery codes
- Roles, granular permissions and scoped API tokens
- reCAPTCHA, hCaptcha or Turnstile, rate limits and security headers
- Activity logging, session controls and user data exports

### An admin panel you can run a SaaS from

Follow revenue, investigate a customer issue and manage subscriptions from the
same place: 22 business metrics across 11 admin areas.

- MRR, ARR, ARPU, lifetime value and churn
- Users, plans, coupons, subscriptions, transactions and refunds
- Date ranges, currency filters and period comparisons
- Time-limited user impersonation with protected actions

<img src="https://stacktoast.com/screenshots/livewire--admin-subscriptions.png" alt="Laravel admin panel for managing SaaS subscriptions" width="860">

### Teams and seat billing, ready for "Can I invite my team?"

Sell to individuals today and teams tomorrow. Invitations, team roles, seat
limits, ownership transfer and team-based billing share the same foundation,
and teams can be switched off until your product needs them.

## Livewire, React, Vue or API: choose how you build

Four editions from one codebase. Every edition has the same SaaS features, the
Sanctum API with an OpenAPI specification, and the complete admin panel.

| Edition | Stack | You build with |
| --- | --- | --- |
| **Livewire** | PHP · Blade · Alpine | Interactive screens in PHP, using familiar Laravel patterns |
| **React** | React · Inertia | Your interface in React, connected to Laravel's routes and controllers |
| **Vue** | Vue · Inertia | Your interface in Vue, with the same core services underneath |
| **API** | Sanctum · OpenAPI | Your own web or mobile client on the shipped endpoints |

## Built for Claude Code, Cursor and Codex

You can build a SaaS with AI. Spend the tokens on your idea.

A generated checkout is only the beginning: duplicate webhooks, failed
payments, team permissions and account recovery still have to work together.
Stack Toast gives your coding agent that foundation, and the rules for
building on it.

- Agent rules for your exact edition: where your code belongs, which files to leave alone, how to extend each feature
- `ARCHITECTURE.md`, Laravel Boost guidance and `llms.txt` for context beyond the next prompt
- Documented extension points, so changes do not mean editing the foundation

> "Build the client-reporting feature. Use the existing accounts, teams and subscriptions."

## Customize everything and still take the next release

Most starter kits are a one-way door: once you change the code, updates stop.
Your Stack Toast project is your own Git repository with Stack Toast connected
as a second remote, so a new release arrives as a merge you check first.

```bash
php artisan stacktoast:upgrade           # report: version gap, conflicts from a real trial merge, missing settings
php artisan stacktoast:upgrade --merge   # merge the release onto its own upgrade branch
```

Your code lives in the usual Laravel locations. Stack Toast's core stays in
its own directory, `app/StackToast/`, beneath your app.

## One command starts a new SaaS

```bash
composer global require stacktoast/installer
stacktoast check          # is this machine ready?
stacktoast new my-app     # clones your edition, connects the update remote, starts the setup wizard
```

The [installer](https://packagist.org/packages/stacktoast/installer) is public.
Check your machine before you buy.

## One payment, unlimited projects

- **Paid once.** No subscription and no per-project fee.
- Unlimited commercial projects, including client work.
- Full source code in a private GitHub repository, with lifetime updates.
- 30-day money-back guarantee.

Want every edition? The bundle has all four, plus **AI Cocktail**: a Laravel
package that chains AI operations across 20 providers, among them OpenAI,
Anthropic, Google Gemini, Stability AI and ElevenLabs.

<div align="center">

### [Get Stack Toast at stacktoast.com](https://stacktoast.com/#pricing)

</div>

## We build our own products on it

Stack Toast is the foundation under our own SaaS products. They start from
the same code you get, so every part of it is used, tested and improved in
production.

## Already a customer?

The repositories in this organisation are private. Connect your GitHub account
in the [member portal](https://stacktoast.com/portal) to receive your
repository invitations, then run `stacktoast new my-app`.

<sub>Payment capabilities vary by processor. Requires PHP 8.4 or newer. Runs on MySQL, MariaDB, PostgreSQL and SQLite.</sub>
