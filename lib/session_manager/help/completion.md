<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/session-manager-cli/blob/master/lib/session_manager/help/completion.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

Example:

    session-manager completion

Prints words for TAB auto-completion.

Examples:

    session-manager completion
    session-manager completion hello
    session-manager completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(session-manager completion_script)

Auto-completion example usage:

    session-manager [TAB]
    session-manager hello [TAB]
    session-manager hello name [TAB]
    session-manager hello name --[TAB]
