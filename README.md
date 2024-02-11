> [!NOTE]  
> This is a continuation of Vendetta that fixes problems & updated to support features.

# Argument
A (Vendetta Continuation) mod for Discord's mobile apps.

## Installing
Argument's codebase is platform-agnostic, but you need a platform-specific loader.

### Android
* Non-root - [ArgumentManager](https://github.com/MadeByRedPCat/ArgumentManager/releases/latest)
    - The minimum Android version required is 9. It will not work any lower.

> [!NOTE]
> iOS will be returning in the near future.

## Contributing
1. Install a Argument loader with loader config support (any mentioned in the [Installing](#installing) section).

2. Go to Settings > General and enable Developer Settings.

3. Clone the repo:
    ```
    git clone https://github.com/MadeByRedPCat/Argument
    ```

4. Install dependencies:
    ```
    pnpm i
    ```
    <sup>`npm` or `yarn` should also work.</sup>

5. Build Argument's code:
    ```
    pnpm build
    ```
    <sup>`npm` or `yarn` should also work.</sup>

6. In the newly created `dist` directory, run a HTTP server. I recommend [http-server](https://www.npmjs.com/package/http-server).

7. Go to Settings > Developer enabled earlier). Enable `Load from custom url` and input the IP address and port of the server (e.g.  e.g. `http://192.168.1.236:4040`) in the new input box labelled `VENDETTA URL`.

8. Restart Discord. Upon reload, you should notice that your device will download Argument's bundled code from your server, rather than GitHub.

9. Make your changes, rebuild, reload, go wild!
