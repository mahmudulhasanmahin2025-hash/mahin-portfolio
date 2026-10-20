# Mahmoodul Hasan Mahin — Portfolio

A lightweight, responsive portfolio for Mahmoodul Hasan Mahin. The site content lives in `content/` and can be edited through the `/admin/` content editor after its Netlify authentication services are enabled.

## Content editor setup

The editor uses Decap CMS with Netlify Identity and Git Gateway. In the Netlify project settings:

1. Enable Identity and set registration to invite only.
2. Enable Git Gateway for the connected GitHub repository.
3. Invite the owner as an Identity user and accept the invitation.
4. Open `/admin/` on the published site to edit portfolio details and projects.

Git Gateway is currently marked deprecated in Netlify's documentation. The editor is configured for the standard Netlify/Decap flow, but a different CMS backend may be preferable for a new long-term setup.
