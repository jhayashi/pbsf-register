# pbsf-register

The Piedmont Baseball Softball Foundation registration form, served by GitHub Pages at
**https://register.piedmontbaseball.org/**.

`index.html` is **generated**: it is `frontend/registration.html` from the private
`jhayashi/pbsf-reg` repo, pushed here by that repo's "Publish form" workflow on every
change to `main`. Don't edit it here; the next publish overwrites it.

- The plain address is the live form. Add `?env=test` for Stripe test mode
  (card 4242 4242 4242 4242), and `&now=<ISO time>` to try another price tier.
- Everything the form knows about fees, dates and divisions comes from the backend at
  run time; this file holds no secrets.
