# CN/OS Lab Environment

A simple repository providing a **pre-configured Ubuntu environment** for Computer Networks & Operating Systems labs. This avoids the hassle of installing older Ubuntu versions and manually configuring **ns-2, nam, and xgraph**.

## What This Repo Contains

* Preconfigured VM with:

  * Ubuntu (older stable version)
  * NS-2
  * NAM
* Sample CN lab program

## How to Use

1. Download the VM from the **Releases** section.
2. Import it into VMware/VirtualBox.
3. Open the terminal and run:

```bash
ns sample.tcl
nam sample.nam
```

## Structure

```
vm-image/   # VM files or download links
README.md
```

## Notes

Use Issues or Pull Requests for suggestions or fixes.
