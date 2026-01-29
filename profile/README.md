# MRX - MR Expertise

_Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet._

# Repositories

There are different types of repositories in this organization, listed below.

## Tools
These are all **private** and (currently) published to fly.io:

| repository | url | description |
| ---------- | --- | ----------- |
| [tool_spdg_flio](https://github.com/mrx-org/tool_spdg_flyio) | https://tool-spdg-flyio.fly.dev/ | simulate a sequence using the cutting-edge (WIP) segmented PDG sim |
| [tool_seeloader_flio](https://github.com/mrx-org/tool_seqloader_flyio) | https://tool-seqloader-flyio.fly.dev/ | upload a .seq file and get the parsed sequence back |
| [tool_phantomlib_flio](https://github.com/mrx-org/tool_phantomlib_flyio) | https://tool-phantomlib-flyio.fly.dev/ | retrieve any BrainWeb phantom at any resolution |

## Organization

**public**:
- [.github](https://github.com/mrx-org/.github): Hosts this README.md[Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [mrx-book](https://github.com/mrx-org/mrx-book): Public documentation / advertisement for MRX (WIP): https://mrx-org.github.io/mrx-book/

**private**:
- [mrx-board](https://github.com/mrx-org/mrx-board): For internal documents, hosts the [Discussions](https://github.com/orgs/mrx-org/discussions)

## ToolApi
This is the interface between scripts / AI and the actual tools doing the work. It is currently available for Rust and Python under the AGPL license:
- [toolapi](https://github.com/mrx-org/toolapi): Rust version, `cargo add toolapi`, hosted on [crates.io](https://crates.io/crates/toolapi)
- [toolapi-py](https://github.com/mrx-org/toolapi-py): Python version, `pip install toolapi`, hosted on [PyPI](https://pypi.org/project/toolapi/)

## mrx repo
This repository is outdated. It started for engineering toolapi and writing a couple of tools. This is now separated into multiple, independend repositories. The mrx repo will be deleted if its content is no longer needed as reference.
