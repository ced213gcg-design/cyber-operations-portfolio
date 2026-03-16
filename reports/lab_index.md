# Cyber Lab Index

## Completed Artifacts
- scans/nmap_scan1.txt
- network_scans/host_discovery1.txt

## Notes
- nmap_scan1.txt contains a service/version scan against scanme.nmap.org
- host_discovery1.txt contains a host discovery scan result

## Purpose
This repository documents authorized cybersecurity lab exercises, reconnaissance practice, and defensive skill development.


On Sun, Mar 15, 2026 at 8:06 AM Cedrick Green <ced213g.cg@gmail.com> wrote:
mkdir -p reports
nano reports/lab_index.md


On Sun, Mar 15, 2026 at 8:05 AM Cedrick Green <ced213g.cg@gmail.com> wrote:
nano reports/lab_index.md


On Sun, Mar 15, 2026 at 8:03 AM Cedrick Green <ced213g.cg@gmail.com> wrote:
# Cyber Lab Index

## Completed Artifacts
- scans/nmap_scan1.txt
- network_scans/host_discovery1.txt

## Notes
- `nmap_scan1.txt` contains a service/version scan against scanme.nmap.org
- `host_discovery1.txt` contains a host discovery scan result

## Purpose
This repository documents authorized cybersecurity lab exercises, reconnaissance practice, and defensive skill development.
## HTTP Header Analysis

Tool Used:
curl

Command Executed:
curl -I http://scanme.nmap.org > notes/http_headers_scanme.txt

Purpose:
Capture HTTP response headers from the server to analyze basic web service information and identify exposed server details.

Findings:
- HTTP response headers successfully collected
- Server header revealed Apache httpd
- Connection and content behavior visible
- Useful for reconnaissance and web security review

Skills Demonstrated:
- HTTP header inspection
- Web reconnaissance
- Linux command line workflow
- Security documentation
- SOC Investigation Lab
- Log Analysis Lab — reports/log_analysis_lab.md
- Log Analysis Lab — reports/log_analysis_lab.md




