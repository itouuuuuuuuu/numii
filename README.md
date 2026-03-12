# numii

Interactive wrapper for [numi-cli](https://github.com/nickolaev/numi-cli) smart calculator.

## Install

```bash
brew install itouuuuuuuuu/tap/numii
```

## Usage

### Single expression

```bash
numii "2+3"        # => 5
numii "20% of 150" # => 30
numii "$100 in JPY"
```

### With options

```bash
numii -c "2+3"      # Calculate and copy result to clipboard
numii -p 20 "pi"    # Set precision to 20 digits
```

### Interactive mode

```bash
numii
```

```
Numi Interactive Mode (type 'exit' or Ctrl+D to quit, 'copy' to copy last result)

> 2+3
5
> 20% of 150
30
> copy
Copied: 30
> exit
```

## Options

| Option | Description |
|---|---|
| `-c`, `--copy` | Copy result to clipboard |
| `-p N`, `--precision N` | Set decimal precision |
| `-n`, `--no-cache` | Disable cache |
| `-v`, `--verbose` | Verbose output |
| `-l LOCALE`, `--locale LOCALE` | Set locale |

## Interactive commands

| Command | Description |
|---|---|
| `copy` | Copy last result to clipboard |
| `exit` / `quit` | Exit interactive mode |
| `Ctrl+D` | Exit interactive mode |

## License

MIT
