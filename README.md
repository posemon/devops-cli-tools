# Best CLI tools for DevOps / SRE
These are set of additional `Command Line Interface (CLI) tools` I have being using and observed/learned from my co-workers 😃 Each tool has a number of GitHub stars, last release date, description and screenshot. All tools are Open Source.

## Contents

- [Best CLI tools for DevOps / SRE](#best-cli-tools-for-devops--sre)
  - [Contents](#contents)
  - [⚙️ System](#️-system)
  - [👨‍💻👩‍💻 Development](#-development)
  - [💎 Containers](#-containers)
  - [🌎 Network](#-network)
<br><br>

## ⚙️ System
_System CLI tools for quick troubleshooting and system diagnostics_

<details><summary><b><a href="https://github.com/aristocratos/btop">btop</a></b> - resource monitor that shows usage and stats for processor, memory, disks, network and processes</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/aristocratos/btop?style=for-the-badge)](https://github.com/aristocratos/btop/stargazers)
[![Release Date](https://img.shields.io/github/release-date/aristocratos/btop?label=last%20release%20date&style=for-the-badge)](https://github.com/aristocratos/btop/releases/latest)
[![Release](https://img.shields.io/github/release/aristocratos/btop.svg?style=for-the-badge)](https://github.com/aristocratos/btop/releases/latest)
<br>
<p>Easy to use, with a game inspired menu system. Full mouse support, all buttons with a highlighted key is clickable and mouse scroll works in process list and menu boxes.
 Function for showing detailed stats for selected process. Ability to filter processes. Easy switching between sorting options. Tree view of processes. Send any signal to selected process.</p>
<img width="600" alt="btop resource monitor that shows usage and stats for processor, memory, disks, network and processes" src="assets/images/system/btop_1.png" />
<br><br>
<img width="600" alt="btop resource monitor that shows usage and stats for processor, memory, disks, network and processes" src="assets/images/system/btop_2.png" />
<br><br>
<img width="600" alt="btop resource monitor that shows usage and stats for processor, memory, disks, network and processes" src="assets/images/system/btop_3.png" />
</details>

<details><summary><b><a href="https://github.com/muesli/duf">duf</a></b> - disk usage/free utility (Linux, BSD, macOS & Windows)</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/muesli/duf?style=for-the-badge)](https://github.com/muesli/duf/stargazers)
[![Release Date](https://img.shields.io/github/release-date/muesli/duf?label=last%20release%20date&style=for-the-badge)](https://github.com/muesli/duf/releases/latest)
[![Release](https://img.shields.io/github/release/muesli/duf.svg?style=for-the-badge)](https://github.com/muesli/duf/releases/latest)
<br>
<img width="600" alt="duf is a Disk Usage/Free Utility (Linux, BSD, macOS & Windows)" src="assets/images/system/duf.png" />
</details>

<details><summary><b><a href="https://github.com/dundee/gdu">gdu</a></b> - pretty fast disk usage analyzer written in Go</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/dundee/gdu?style=for-the-badge)](https://github.com/dundee/gdu/stargazers)
[![Release Date](https://img.shields.io/github/release-date/dundee/gdu?label=last%20release%20date&style=for-the-badge)](https://github.com/dundee/gdu/releases/latest)
[![Release](https://img.shields.io/github/release/dundee/gdu.svg?style=for-the-badge)](https://github.com/dundee/gdu/releases/latest)
<br>
<p>go DiskUsage() - Pretty fast disk usage analyzer written in Go. Gdu is intended primarily for SSD disks where it can fully utilize parallel processing. However HDDs work as well, but the performance gain is not so huge.</p>
<img width="600" alt="gdu pretty fast disk usage analyzer written in Go" src="assets/images/system/gdu_1.png" />
<br><br>
<img width="600" alt="gdu pretty fast disk usage analyzer written in Go" src="assets/images/system/gdu_2.png" />
</details>

<details><summary><b><a href="https://github.com/ogham/exa">exa</a></b> - modern replacement for ls</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/ogham/exa?style=for-the-badge)](https://github.com/ogham/exa/stargazers)
[![Release Date](https://img.shields.io/github/release-date/ogham/exa?label=last%20release%20date&style=for-the-badge)](https://github.com/ogham/exa/releases/latest)
[![Release](https://img.shields.io/github/release/ogham/exa.svg?style=for-the-badge)](https://github.com/ogham/exa/releases/latest)
<br>
<p>exa is a modern replacement for the venerable file-listing command-line program ls that ships with Unix and Linux operating systems, giving it more features and better defaults. It uses colours to distinguish file types and metadata. It knows about symlinks, extended attributes, and Git. And it’s small, fast, and just one single binary.</p>
<p>By deliberately making some decisions differently, exa attempts to be a more featureful, more user-friendly version of ls. For more information, see exa’s website.</p>
<img width="600" alt="exa is a modern replacement for ls" src="assets/images/system/exa.png" />
</details>

<details><summary><b><a href="https://github.com/sharkdp/fd">fd</a></b> - program to find entries in your filesystem</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/sharkdp/fd?style=for-the-badge)](https://github.com/sharkdp/fd/stargazers)
[![Release Date](https://img.shields.io/github/release-date/sharkdp/fd?label=last%20release%20date&style=for-the-badge)](https://github.com/sharkdp/fd/releases/latest)
[![Release](https://img.shields.io/github/release/sharkdp/fd.svg?style=for-the-badge)](https://github.com/sharkdp/fd/releases/latest)
<br>
<p>It is a simple, fast and user-friendly alternative to find. While it does not aim to support all of find's powerful functionality, it provides sensible (opinionated) defaults for a majority of use cases.</p>
<img width="600" alt="fd is a program to find entries in your filesystem" src="assets/images/system/fd.svg" />
</details>

<details><summary><b><a href="https://github.com/httpie/httpie">httpie</a></b> - human-friendly CLI HTTP client for the API era</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/httpie/httpie?style=for-the-badge)](https://github.com/httpie/httpie/stargazers)
[![Release Date](https://img.shields.io/github/release-date/httpie/httpie?label=last%20release%20date&style=for-the-badge)](https://github.com/httpie/httpie/releases/latest)
[![Release](https://img.shields.io/github/release/httpie/httpie.svg?style=for-the-badge)](https://github.com/httpie/httpie/releases/latest)
<br>
<p>HTTPie (pronounced aitch-tee-tee-pie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers. The http & https commands allow for creating and sending arbitrary HTTP requests. They use simple and natural syntax and provide formatted and colorized output.</p>
<img width="600" alt="httpie human-friendly CLI HTTP client for the API era" src="assets/images/system/httpie.gif" />
</details>
<br>

## 👨‍💻👩‍💻 Development
_CLI Tools and Utilities For Network Management in Linux_

<details><summary><b><a href="https://github.com/gnachman/iTerm2">iTerm2</a></b> - terminal emulator for macOS that does amazing things</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/gnachman/iTerm2?style=for-the-badge)](https://github.com/gnachman/iTerm2/stargazers)
<br>
<p>iTerm2 brings the terminal into the modern age with features you never knew you always wanted. iTerm2 has a lot of features: Split Panes, Hotkey Window, Search, Autocomplete, Copy Mode, Paste History, Configurability, 24-bit Color, Notification Center Support, Readability, Tagged Profiles, Multi-Lingual, Smart Selection, Shell Integration, Inline Images etc.</p>
<img width="600" alt="k9s kubernetes CLI To Manage Your Clusters In Style" src="assets/images/development/iterm2.webp" />
</details>

<details><summary><b><a href="https://github.com/sharkdp/bat">bat</a></b> - cat clone with syntax highlighting and Git integration.</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/sharkdp/bat?style=for-the-badge)](https://github.com/sharkdp/bat/stargazers)
[![Release Date](https://img.shields.io/github/release-date/sharkdp/bat?label=last%20release%20date&style=for-the-badge)](https://github.com/sharkdp/bat/releases/latest)
[![Release](https://img.shields.io/github/release/sharkdp/bat.svg?style=for-the-badge)](https://github.com/sharkdp/bat/releases/latest)
<br>
<p>bat supports syntax highlighting for a large number of programming and markup languages. bat communicates with git to show modifications with respect to the index (see left side bar). You can use the -A/--show-all option to show and highlight non-printable characters.</p>
<img width="600" alt="bat cat clone with syntax highlighting and Git integration" src="assets/images/development/bat/bat_1.png" />
<br>
<img width="600" alt="bat cat clone with syntax highlighting and Git integration" src="assets/images/development/bat/bat_2.png" />
<br>
<img width="600" alt="bat cat clone with syntax highlighting and Git integration" src="assets/images/development/bat/bat_3.png" />
</details>

<details><summary><b><a href="https://github.com/Bhupesh-V/ugit">ugit</a></b> - undo your last oopsie 🙈️ in git.</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/Bhupesh-V/ugit?style=for-the-badge)](https://github.com/Bhupesh-V/ugit/stargazers)
[![Release Date](https://img.shields.io/github/release-date/Bhupesh-V/ugit?label=last%20release%20date&style=for-the-badge)](https://github.com/Bhupesh-V/ugit/releases/latest)
[![Release](https://img.shields.io/github/release/Bhupesh-V/ugit.svg?style=for-the-badge)](https://github.com/Bhupesh-V/ugit/releases/latest)
<br>
<p>You ran an accidental git command you didn't want to. You don't want to waste your time searching on how to undo ... Because you want to focus on problems at hand and not on Git (You don't like context switching). Because ugit is cool 😃</p>
<img width="600" alt="ugit undo your last oopsie in git" src="assets/images/development/ugit.gif" />
</details>
<br>

## 💎 Containers
_CLI tools to make it easier to work with containerized applications_

<details><summary><b><a href="https://github.com/bcicen/ctop">ctop</a></b> - top-like interface for container metrics</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/bcicen/ctop?style=for-the-badge)](https://github.com/bcicen/ctop/stargazers)
[![Release Date](https://img.shields.io/github/release-date/bcicen/ctop?label=last%20release%20date&style=for-the-badge)](https://github.com/bcicen/ctop/releases/latest)
[![Release](https://img.shields.io/github/release/bcicen/ctop.svg?style=for-the-badge)](https://github.com/bcicen/ctop/releases/latest)
<br>
<p>ctop provides a concise and condensed overview of real-time metrics for multiple containers, as well as a single container view for inspecting a specific container. ctop comes with built-in support for Docker and runC.</p>
<img width="600" alt="ctop top-like interface for container metrics" src="assets/images/containers/ctop/ctop_1.gif" />
<br><br>
<img width="600" alt="ctop top-like interface for container metrics" src="assets/images/containers/ctop/ctop_2.gif" />
</details>

<details><summary><b><a href="https://github.com/moncho/dry">dry</a></b> - terminal application to manage Docker and Docker Swarm</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/moncho/dry?style=for-the-badge)](https://github.com/moncho/dry/stargazers)
[![Release Date](https://img.shields.io/github/release-date/moncho/dry?label=last%20release%20date&style=for-the-badge)](https://github.com/moncho/dry/releases/latest)
[![Release](https://img.shields.io/github/release/moncho/dry.svg?style=for-the-badge)](https://github.com/moncho/dry/releases/latest)
<br>
<p>It shows information about Containers, Images and Networks, and, if running a Swarm cluster, it shows information about Nodes, Service, Stacks and the rest of Swarm constructs. It can be used with both local or remote Docker daemons.</p>
<img width="600" alt="dry is a terminal application to manage Docker and Docker Swarm" src="assets/images/containers/dry.png" />
</details>

<details><summary><b><a href="https://github.com/wagoodman/dive">dive</a></b> - exploring a docker image, layer contents and indicate what's changed in each layer</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/wagoodman/dive?style=for-the-badge)](https://github.com/wagoodman/dive/stargazers)
[![Release Date](https://img.shields.io/github/release-date/wagoodman/dive?label=last%20release%20date&style=for-the-badge)](https://github.com/wagoodman/dive/releases/latest)
[![Release](https://img.shields.io/github/release/wagoodman/dive.svg?style=for-the-badge)](https://github.com/wagoodman/dive/releases/latest)
<br>
<p>A tool for exploring a docker image, layer contents, and discovering ways to shrink the size of your Docker/OCI image. Show Docker image contents broken down by layer, estimate "image efficiency", quick build/analysis cycles and CI Integration.</p>
<img width="600" alt="dive exploring a docker image, layer contents and indicate what's changed in each layer" src="assets/images/containers/dive.gif" />
</details>

<details><summary><b><a href="https://github.com/lensapp/lens">lens</a></b> - the way the world runs Kubernetes</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/lensapp/lens?style=for-the-badge)](https://github.com/lensapp/lens/stargazers)
[![Release Date](https://img.shields.io/github/release-date/lensapp/lens?label=last%20release%20date&style=for-the-badge)](https://github.com/lensapp/lens/releases/latest)
[![Release](https://img.shields.io/github/release/lensapp/lens.svg?style=for-the-badge)](https://github.com/lensapp/lens/releases/latest)
<br>
<p>Lens IDE provides the full situational awareness for everything that runs in Kubernetes. It's lowering the barrier of entry for people just getting started and radically improving productivity for people with more experience.</p>
<img width="600" alt="lens the way the world runs Kubernetes" src="assets/images/containers/lens.png" />
</details>

<details><summary><b><a href="https://github.com/derailed/k9s">k9s</a></b> - kubernetes CLI To Manage Your Clusters In Style</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/derailed/k9s?style=for-the-badge)](https://github.com/derailed/k9s/stargazers)
[![Release Date](https://img.shields.io/github/release-date/derailed/k9s?label=last%20release%20date&style=for-the-badge)](https://github.com/derailed/k9s/releases/latest)
[![Release](https://img.shields.io/github/release/derailed/k9s.svg?style=for-the-badge)](https://github.com/derailed/k9s/releases/latest)
<br>
<p>K9s provides a terminal UI to interact with your Kubernetes clusters. The aim of this project is to make it easier to navigate, observe and manage your applications in the wild. K9s continually watches Kubernetes for changes and offers subsequent commands to interact with your observed resources.</p>
<img width="600" alt="k9s kubernetes CLI To Manage Your Clusters In Style" src="assets/images/containers/k9s/k9s_1.png" />
<br>
<img width="600" alt="k9s kubernetes CLI To Manage Your Clusters In Style" src="assets/images/containers/k9s/k9s_2.png" />
<br>
<img width="600" alt="k9s kubernetes CLI To Manage Your Clusters In Style" src="assets/images/containers/k9s/k9s_3.png" />
</details>
<br>

## 🌎 Network
_Command-Line Tools and Utilities For Network Management_

<details><summary><b><a href="https://github.com/ogham/dog">dog</a></b> - command-line DNS client</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/ogham/dog?style=for-the-badge)](https://github.com/ogham/dog/stargazers)
[![Release Date](https://img.shields.io/github/release-date/ogham/dog?label=last%20release%20date&style=for-the-badge)](https://github.com/ogham/dog/releases/latest)
[![Release](https://img.shields.io/github/release/ogham/dog.svg?style=for-the-badge)](https://github.com/ogham/dog/releases/latest)
<br>
<p>dog is a command-line DNS client, like dig. It has colourful output, understands normal command-line argument syntax, supports the DNS-over-TLS and DNS-over-HTTPS protocols, and can emit JSON.</p>
<img width="600" alt="dog command-line DNS client" src="assets/images/network/dog.png" />
</details>

<details><summary><b><a href="https://github.com/imsnif/bandwhich">bandwhich</a></b> - utility for displaying current network utilization by process, connection and remote IP/hostname</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/imsnif/bandwhich?style=for-the-badge)](https://github.com/imsnif/bandwhich/stargazers)
[![Release Date](https://img.shields.io/github/release-date/imsnif/bandwhich?label=last%20release%20date&style=for-the-badge)](https://github.com/imsnif/bandwhich/releases/latest)
[![Release](https://img.shields.io/github/release/imsnif/bandwhich.svg?style=for-the-badge)](https://github.com/imsnif/bandwhich/releases/latest)
<br>
<p>bandwhich sniffs a given network interface and records IP packet size, cross referencing it with the /proc filesystem on linux, lsof on macOS, or using WinApi on windows. It is responsive to the terminal window size, displaying less info if there is no room for it. It will also attempt to resolve ips to their host name in the background using reverse DNS on a best effort basis.</p>
<img width="600" alt="bandwhich utility for displaying current network utilization by process, connection and remote IP/hostname" src="assets/images/network/bandwhich.gif" />
</details>

<details><summary><b><a href="https://github.com/nitefood/asn">asn</a></b> - lookup tool and traceroute server</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/nitefood/asn?style=for-the-badge)](https://github.com/nitefood/asn/stargazers)
[![Release Date](https://img.shields.io/github/release-date/nitefood/asn?label=last%20release%20date&style=for-the-badge)](https://github.com/nitefood/asn/releases/latest)
[![Release](https://img.shields.io/github/release/nitefood/asn.svg?style=for-the-badge)](https://github.com/nitefood/asn/releases/latest)
<br>
<p>ASN / RPKI validity / BGP stats / IPv4v6 / Prefix / ASPath / Organization / IP reputation / IP geolocation / IP fingerprinting / Network recon / lookup tool / Web traceroute server.</p>
➡️ IPv4 lookup with IP type detection (Anycast, Hosting/DC) and classification as known good
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_1.png" />
<br><br>

➡️ IPv4 lookup (bad reputation IP) with threat analysis/scoring, CPE/CVE identification and open ports reporting
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_2.png" />
<br><br>

➡️ IP fingerprinting with advanced datacenter+region identification, known vulnerabilities affecting the target and honeypot identification according to Shodan data
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_3.png" />
<br><br>

➡️ Autonomous system number lookup with BGP stats, peering and prefix informations
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_4.png" />
<br><br>

➡️ Hostname/URL lookup<br>
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_5.png" />
<br><br>

➡️ ASPath trace to www.github.com
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_6.png" />
<br><br>

➡️ Performing bulk extraction, geolocation and stats for IPs from a logfile
<img width="600" alt="asn lookup tool and traceroute server" src="assets/images/network/asn/asn_7.png" />
<br><br>
</details>

<details><summary><b><a href="https://github.com/drwetter/testssl.sh">testssl.sh</a></b> - command line tool which checks a server's service on any port for the support of TLS/SSL ciphers</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/drwetter/testssl.sh?style=for-the-badge)](https://github.com/drwetter/testssl.sh/stargazers)
[![Release Date](https://img.shields.io/github/release-date/drwetter/testssl.sh?label=last%20release%20date&style=for-the-badge)](https://github.com/drwetter/testssl.sh/releases/latest)
[![Release](https://img.shields.io/github/release/drwetter/testssl.sh.svg?style=for-the-badge)](https://github.com/drwetter/testssl.sh/releases/latest)
<br>
<p>testssl.sh is a free command line tool which checks a server's service on any port for the support of TLS/SSL ciphers, protocols as well as recent cryptographic flaws and more.</p>
<img width="600" alt="testssl.sh command line tool which checks a server's service on any port for the support of TLS/SSL ciphers" src="assets/images/network/testssl/testssl_1.png" />
<img width="600" alt="testssl.sh command line tool which checks a server's service on any port for the support of TLS/SSL ciphers" src="assets/images/network/testssl/testssl_2.png" />
<img width="600" alt="testssl.sh command line tool which checks a server's service on any port for the support of TLS/SSL ciphers" src="assets/images/network/testssl/testssl_3.png" />
</details>

<details><summary><b><a href="https://github.com/esnet/iperf">iperf3</a></b> - a TCP, UDP, and SCTP network bandwidth measurement tool</summary>
<br>

[![Repo stars](https://img.shields.io/github/stars/esnet/iperf?style=for-the-badge)](https://github.com/esnet/iperf/stargazers)
[![Latest tag](https://img.shields.io/github/v/tag/esnet/iperf?style=for-the-badge)](https://github.com/esnet/iperf/tags)
<br>
<p>iperf is a tool for active measurements of the maximum achievable bandwidth on IP networks. It supports tuning of various parameters related to timing, protocols, and buffers. For each test it reports the measured throughput / bitrate, loss, and other parameters.</p>
<img width="600" alt="iperf3 a TCP, UDP, and SCTP network bandwidth measurement tool" src="assets/images/network/iperf3.webp" />
</details>