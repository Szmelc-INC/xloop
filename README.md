# xloop
> Simple command looping utility in shell.
```
> Execute:
>  Command [X]
>  [X] times
>  With [X]s delay
```

### Install:
`Just paste the file to valid /bin/ $PATH and reload with source command`

### Usage:
`xloop --help`:
```

__  _| |    ___   ___  _ __  
\ \/ / |   / _ \ / _ \| '_ \ 
 >  <| |__| (_) | (_) | |_) |
/_/\_\_____\___/ \___/| .__/ 
                      |_|   

Usage: xloop [OPTIONS] -c <command>

OPTIONS:
  -q <quantity>   Number of times to run the command (default: 1)
  -d <delay>      Delay in seconds between each command execution (default: 1)
  -c <command>    Command to run in the loop
  --help           Display this help and exit

EXAMPLES:
  xloop -q 5 -d 0.2 -c 'echo bruh'
# Execute 'echo bruh' 5 times with a 0.2s delay
  xloop -c 'date'
# Execute 'date' command once (default settings)

By: Szmelc.INC / sx66
GitHub: https://github.com/orgs/GNU-Szmelc/xloop

```
