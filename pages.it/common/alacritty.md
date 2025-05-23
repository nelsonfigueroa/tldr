# alacritty

> Multipiattaforma, GPU-accelerato emulatore di terminale.
> Maggiori informazioni: <https://manned.org/alacritty>.

- Apri un nuovo finestra di Alacritty:

`alacritty`

- Esegui in una directory specifica:

`alacritty --working-directory {{percorso/della/directory}}`

- Esegui un comando in una nuova finestra di Alacritty:

`alacritty -e {{comando}}`

- Specifica un file di configurazione alternativo (predefinito a `$XDG_CONFIG_HOME/alacritty/alacritty.toml`):

`alacritty --config-file {{percorso/di/config.toml}}`

- Esegui con ricaricamento configurazione live (può anche essere acceso in `alacritty.toml`):

`alacritty --live-config-reload --config-file {{percorsi/al/config.toml}}`
