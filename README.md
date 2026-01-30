# random-username-generator

Used by [OpenPanel](https://openpanel.com/) to generate a random admin username and password on installation.
inspired by [Moby's Package namesgenerator](https://github.com/moby/moby/blob/master/internal/namesgenerator/names-generator.go)

# Usage

On terminal:
```bash
source <(curl -sSL https://raw.githubusercontent.com/stefanpejcic/random-username-generator/refs/heads/main/generator.sh) && echo "$random_name"
```

Or in your scripts:
```bash
source <(curl -sSL https://raw.githubusercontent.com/stefanpejcic/random-username-generator/refs/heads/main/generator.sh)

# and later where needed use $random_name
SOMETHING="$random_name"
```


