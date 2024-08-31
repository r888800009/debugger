# debugger (WIP)
desktop program for debugging
- [ ] multi-window
- [ ] save/load workspace
- [ ] remote allow

## feature (TODO)
- [ ] support lldb
- [ ] memory view
    - [ ] chunks bookmark (ptmalloc)
- [ ] string analysis (preset pattern)
- [ ] patcher (saveable)
- [ ] bookmark (breakpoint)
- [ ] checkpoint tool (snapshot) like fork
- [ ] symbolic execution / taint analysis
- [ ] remote debugging

## Backend
- lldb
    - [foundryzero/llef: LLEF is a plugin for LLDB to make it more useful for RE and VR](https://github.com/foundryzero/llef?tab=readme-ov-file)
- gdb
    - [hugsy/gef: GEF (GDB Enhanced Features) - a modern experience for GDB with advanced debugging capabilities for exploit devs & reverse engineers on Linux](https://github.com/hugsy/gef)
- asm emulator 

## Related Works
- [rohanrhu/gdb-frontend: ☕ GDBFrontend is an easy, flexible and extensible gui debugger. Try it on https://debugme.dev](https://github.com/rohanrhu/gdb-frontend)
