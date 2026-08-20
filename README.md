# PrivacyPolicyEcho (retired)

This repo used to be a separate three page site (home, privacy policy, terms
of service) that existed only so Google OAuth verification had public URLs to
point at. Keeping Echo's legal text in its own repo meant maintaining a second
site that looked nothing like the product it covered.

**The pages now live in the Echo repo**, in `website/`, and are published with
the rest of the site:

- https://echo-website-kswork2001s-projects.vercel.app/
- https://echo-website-kswork2001s-projects.vercel.app/privacy
- https://echo-website-kswork2001s-projects.vercel.app/terms

Everything here is a redirect stub. There is nothing to edit: change the text
in the Echo repo, at `website/privacy.html` and `website/terms.html`.

## Before deleting this repo

The old URLs are still what Google Cloud Console has on file for the OAuth
consent screen. Repoint those to the URLs above first. Once Google is updated
and nothing links here any more, this repo can be archived or deleted.

GitHub Pages cannot issue a real 301, so the stubs redirect with a meta
refresh and declare the new address as `rel="canonical"`.
