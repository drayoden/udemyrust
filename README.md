### rust - udemy :: rust fundamentals by Lyubomir Gavadinov
- memory safe with no garbage collection
- no nulls
- no exceptions
- modern package manager -> cargo like npm
- 'if it compiles; no data races'

### 11 - explore memory with GDB
- `gdb ./trace/debug/<app>` - starts the debugger installed pwndbg; will take over once gdb starts
- when in the debugger:
  - see listing of whole file `l -` - places the source code in the top pane
  - to prevent numerous wierd python errors: `set language c`
  - set breakpoints: `b <function name>`
  - `r` - run
