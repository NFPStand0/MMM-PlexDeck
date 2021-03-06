# plexdeck

This is a module for the [MagicMirror²](https://github.com/MichMich/MagicMirror/).

Using this MagicMirror plugin, you can list shows "On Deck" from your Plex Media Server. 

## Using the module

To use this module, add the following configuration block to the modules array in the `config/config.js` file:
```js
var config = {
    modules: [
        {
            module: 'plexdeck',
            header: 'Plex On Deck',
            config: {
                plexURL: 'http://192.168.0.1:32400'
            }
        }
    ]
}
```

## Configuration options

| Option           | Description
|----------------- |-----------
| `plexURL`        | *Required* The URL of your plex server
| `updateInterval`        | *Optional* How often to refresh 'On Deck' <br><br>**Type:** `int`(milliseconds) <br>Default 300,000 milliseconds (5 minutes)

## Contributing

Contributions of all kinds are welcome, not only in the form of code but also bug reports, documentation edits, and suggested improvements.
