Build usage and billing surfaces using the existing design system.

Usage dashboard:

- current billing period
- total usage
- estimated cost
- credits remaining
- daily trend
- usage by action
- usage by department
- usage by user
- top consumers
- quota progress
- date and department filters
- downloadable CSV if API supports it

Permissions:

- company_admin: tenant-wide
- billing_admin: tenant-wide billing and usage
- dept_manager: authorized department usage
- member: own usage only if product policy allows
- read_only: view only when explicitly permitted

Billing:

- current plan
- seat count
- credits
- payment status
- invoices
- upgrade/downgrade
- cancellation
- payment-method management through provider-hosted secure flow

Add low-balance and hard-limit banners.

Do not render billing navigation for unauthorized users.
Add responsive and accessibility tests.