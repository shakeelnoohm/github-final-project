# Simple Interest Calculator

A Bash script that calculates simple interest given principal, annual rate of interest, and time period in years.

## Usage

```bash
bash simple-interest.sh
```

The script will prompt for:

## Input

| Variable | Description |
|----------|-------------|
| `p` | Principal amount |
| `r` | Annual rate of interest (%) |
| `t` | Time period in years |

## Output

```
simple interest = (p * t * r) / 100
```

## Example

```
Enter the principal:
1000
Enter rate of interest per year:
5
Enter time period in years:
3
The simple interest is:
150
```

## Requirements

- Bash shell
- `bc` (basic calculator utility) — available by default on most Linux/macOS systems

## License

[Apache License 2.0](LICENSE)

