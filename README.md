# AFK Command Line Utility

Use this utility to notify you on Telegram when your long running command finishes running.

## How to use

1. Copy the `afk` file into your bin path (eg. `/usr/local/bin`)

    ```
    cp afk /usr/local/bin/
    ```

2. Get a Telegram bot and set the following environment variables:

    ```bash
    AFK_BOT_TOKEN=<the Telegram bot token from the @botfather>
    RECIPIENT_ID=<chat_id of recipient - either a person or a group>
    ```
3. Prepend `afk` to your command:

    ```bash
    afk <command>
    ```

    Example:

    ```bash
    afk which docker
    ```

## Dependency

- cURL (in the command line)

## License

MIT
