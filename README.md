# Google Pay and Wallet Developer Managed MCP Extension

> **Preview:** This product is subject to the "Pre-GA Offerings Terms" in the
> General Service Terms section of the
> [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1).
> Pre-GA products and features are available "as is" and might have limited
> support. For more information, see the
> [launch stage descriptions](https://cloud.google.com/products#product-launch-stages).

The Google Pay and Wallet Developer managed MCP extension gives Gemini CLI the
ability to access your Google Pay and Google Wallet developer data, search
official documentation, and manage your integrations.

## Why use the Google Pay and Wallet Developer managed MCP server?

Google and Google Cloud
[managed MCP servers](https://docs.cloud.google.com/mcp/overview) can be used in
your AI applications with enterprise-ready governance, security, and access
control.

## Before you begin

1.  In the Google Cloud console, on the
    [project selector page](https://console.cloud.google.com/projectselector2/home/dashboard),
    select or create a Google Cloud project.

    > **Note**: If you don't plan to keep the resources that you create in this
    > procedure, create a project instead of selecting an existing project.
    > After you finish these steps, you can delete the project, removing all
    > resources associated with the project.

2.  Get your administrator to grant you the
    [MCP Tool User role](https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser)
    (`roles/mcp.toolUser`) on the Google Cloud project. If you created a new
    project, then you already have the required permissions.

3.  Ensure your administrator has enabled the
    [Google Pay and Wallet Developer API](https://console.cloud.google.com/marketplace/product/google/paydeveloper.googleapis.com)
    on the Google Cloud project.

## Configure authentication

Follow the instructions in the Pay and Wallet Developer MCP server [user guide](https://developers.google.com/pay/api/web/guides/use-pay-wallet-mcp#oauth-client-setup) to create a `clientId` and `clientSecret` for Gemini CLI.

During the installation of the extension, you will be prompted to type in your `clientId` and `clientSecret`.

## Available tools

To see a complete list of available tools and their schemas, see the
[Google Pay Developer MCP reference](https://developers.google.com/pay/api/web/reference/mcp)
and
[Google Wallet Developer MCP reference](https://developers.google.com/wallet/reference/mcp).

## Sample use cases

The following are sample prompts for the Pay and Wallet Developer MCP server:

-   List my Google Pay merchant accounts.
-   What is the status of all my Google Pay integrations?
-   What is the best way to integrate Google Pay with react?
-   Show me the Google Pay error metrics over the last 30 days.
-   List all my Google Wallet pass classes.

## Optional security and safety configurations

MCP introduces new security risks and considerations due to the wide variety of
actions that you can take with MCP tools. To minimize and manage these risks,
Google Cloud offers defaults and customizable policies to control the use of MCP
tools in your Google Cloud organization or project.

For more information about MCP security and governance, see
[AI security and safety](https://docs.cloud.google.com/mcp/ai-security-safety).

## Quotas and limits

The Google Pay and Wallet Developer MCP server doesn't have its own quotas.
There is no limit on the number of call that can be made to the MCP server. You
are still subject to the quotas enforced by the APIs called by the MCP server
tools.

## Reference and resources

*   Check the Google Pay and Wallet Developer MCP Server [user guide](https://developers.google.com/pay/api/web/guides/use-pay-wallet-mcp#oauth-client-setup)
*   Explore the
    [Google Pay Developer remote MCP reference documentation](https://developers.google.com/pay/api/web/reference/mcp)
    and
    [Google Wallet Developer remote MCP reference documentation](https://developers.google.com/wallet/reference/mcp),
    which include lists of all available tools, and the full input and output
    schema for each tool.
*   See the [Google Pay developer overview](https://developers.google.com/pay)
    and
    [Google Wallet developer overview](https://developers.google.com/wallet).
*   Learn about
    [MCP security and governance](https://docs.cloud.google.com/mcp/ai-security-safety).
