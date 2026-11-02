# Shashank | Windows Systems & Diagnostics

I work on Windows kernel-development labs, systems debugging, storage diagnostics,
and AI-assisted engineering tools.

My projects connect two interests: understanding what happens inside Windows,
and building tools that make difficult investigations easier to navigate.

**Core technologies:** C, C++, C#, PowerShell, JavaScript, .NET, Windows Driver
Kit, KMDF/WDM, WinDbg, ETW/WPP, and the Model Context Protocol (MCP).

## Selected work

| Area | Project | What it demonstrates |
| --- | --- | --- |
| Kernel development | [Windows driver labs](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/kernel-driver-labs.md) | KMDF/WDM samples, file-system filters, callbacks, layered I/O, DPCs, synchronization, and tracing |
| Performance tooling | [PerformanceAnalyzer](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/performance-analyzer.md) | Windows storage-performance capture, visualization, and guided investigation |
| AI-assisted diagnostics | [LogConsultant](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/log-consultant.md) | Servicing-log investigation and an approval-aware integration prototype |
| Debugger tooling | [WinDbg extensions](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/windbg-tooling.md) | Boot/hang triage and storage-state exploration |
| Virtualization and storage | [RCT tools and lab automation](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/storage-rct-labs.md) | Change-tracking inspection, backup-chain experiments, and repeatable lab setup |
| Network investigation | [NetworkTraceMcpAnalyzer](https://github.com/Shashank231190/Windows-Systems-Portfolio/blob/main/projects/network-trace-mcp.md) | A trace-analysis MCP server and an AI-client starter prototype |

## How I approach engineering

- Start with observable evidence and define what a measurement can actually prove.
- Use controlled labs to explore kernel behavior and reproduce failure scenarios.
- Keep diagnosis separate from actions that change a machine.
- Treat AI as an investigation aid, not a substitute for trace or debugger evidence.

## About this profile

The [Windows Systems Portfolio](https://github.com/Shashank231190/Windows-Systems-Portfolio)
contains public, source-free project summaries. PerformanceAnalyzer and
LogConsultant core implementations remain private; the showcase includes no
source, proprietary algorithms, internal interfaces, customer data, or credentials.

Kernel projects are identified as lab exercises, and prototypes are not presented
as production products. Recent repository-copy commits represent snapshots, not
reconstructed historical coding activity.
