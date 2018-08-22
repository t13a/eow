# Eijiro on the WEB

CLI client for [Eijiro on the WEB (英辞郎 on the WEB)](https://eow.alc.co.jp/).

## Features

- Hightlight keyword
- Navigate multiple pages
- Output to a file

## Prerequisites

- bash
- curl
- w3m

## Getting started

### Search keyword

```sh
$ ./eow keyword
```

### Search multiple keywords with highlight

```sh
$ ./eow -c multi keyword search
```

### Output search result to a file

```sh
$ ./eow -o path/to/file keyword
```
