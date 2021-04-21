# DUDU_VSCode_OpenWRT_Plugin
Plugin for OpenWRT development

# Requirements
## Development Environment
### Host: Windows 10(192.168.0.2)
1. VSCode
### Virtual Machine: VirtualBox(Ubuntu 16.04:192.168.0.3)
1. OpenWRT 18.06 source code
2. 
### Virtual Machine: OpenWRT 18.06 (192.168.0.4)

## Functional Requirements
### Application Debug
1. After build the OpenWRT application, upload the executale file to OpenWRT
2. When triggering the gdb remote debug, run "gdbserver localhost:2333 'executableFile'"
### UCI Debug
1. using sftp to sync uci directory

## Code generation
1. generate Makefile automatically
2. generate service file automatically
