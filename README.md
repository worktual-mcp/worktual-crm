# Worktual CRM

Connect Cursor to Worktual CRM. Staff can look up and update contacts, companies, deals, quotes, and invoices through the signed-in Worktual account.

The server address is `https://crm-mcp-server.worktual.com/mcp`.

## Install

1. Install this plugin from the Cursor Marketplace, or add the server URL in Cursor under **Customize → MCPs**.
2. Turn **worktual-crm** on.
3. Sign in at `https://oauth.worktual.com` with a Worktual staff account.
4. Choose the Worktual organization.

Admin and Agent accounts can use every tool when the token includes the matching permission. Resolver accounts can read only.

No API key or client secret is required. Cursor registers itself and signs in with your Worktual account.
