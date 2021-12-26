# Download replays from tv

## Arte

Get application Qarte

```bash
sudo apt install qarte
```

Launch the GUI with:

```bash
qarte
```

## Pluzz

### Installation

```bash
sudo apt-add-repository ppa:melixgaro/dpluzz-dev
sudo apt-get update
sudo apt-get install dpluzz-cli
```

### Example

```bash
dpluzz-cli -f -u https://www.france.tv/france-5/science-grand-format/2834181-la-fabrique-du-temps.html
```

The URL parameter is the one given in the web browser. This will save an mkv file.

[Reference Page](https://doc.ubuntu-fr.org/dpluzz)
