# Typefold for Cursor

Render invoices, reports, tickets and other PDFs from your [Typefold](https://typefold.dev)
templates, and build visual templates, by asking Cursor's agent.

Ask, for example:

- "Render the Invoice template for order 2041 as a test."
- "Make a packing slip template for this order JSON."
- "Move the logo to the right and make the totals bold."

## Connect

1. Install the plugin from the Cursor Marketplace.
2. In **Cursor Settings → MCP**, choose **Needs login** next to Typefold.
3. Sign in to Typefold in the browser, pick the workspace Cursor may use, and choose **Connect**.

Cursor acts as you, never with more access than your role in that workspace. You can disconnect
it at any time in Typefold under **Account security → Connected apps**.

You need a Typefold account: [sign up free](https://app.typefold.dev). Test renders are free and
carry a "TEST" watermark; real renders count against your plan.

## Tools

| Tool                       | What it does                                                     |
| -------------------------- | ---------------------------------------------------------------- |
| `list_templates`           | Lists the workspace's templates and whether each is published.   |
| `get_template_data_schema` | Returns the shape of the data a published template takes.        |
| `render_report`            | Renders a published template to PDF or an image.                 |
| `start_render`             | Starts a background render, for large files.                     |
| `get_render_status`        | Returns a render's state and download link.                      |
| `create_visual_template`   | Creates a visual template from example data or a tree of blocks. |
| `edit_visual_template`     | Changes a visual template's blocks and theme.                    |
| `preview_visual_template`  | Draws the pages as images and lists problems.                    |

The full list and setup for other assistants: [Use with AI assistants](https://docs.typefold.dev/clients/ai-assistants/).

## Self-hosted Typefold

Change the URL in `mcp.json` to your installation's address followed by `/mcp`, such as
`https://pdf.example.com/mcp`.

## Support and privacy

- Support: [support@typefold.dev](mailto:support@typefold.dev)
- Privacy policy: [docs.typefold.dev/legal/privacy](https://docs.typefold.dev/legal/privacy/)
