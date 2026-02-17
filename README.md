# MiguelRodo's Scoop Bucket

This repository is a [Scoop](https://scoop.sh/) bucket for installing my personal tools and scripts on Windows.

## Included Packages

* **repos** - A CLI tool to manage, clone, and setup git repositories.

## Installation

### 1. Prerequisites
If you don't have Scoop installed, run this in PowerShell:

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
```

### 2. Add this Bucket

Add this repository to your list of Scoop buckets:

```powershell
scoop bucket add miguelrodo [https://github.com/MiguelRodo/scoop-bucket](https://github.com/MiguelRodo/scoop-bucket)
```

### 3. Install Tools

You can now install the tools directly:

```powershell
scoop install repos
```

## Updating

To get the latest versions of the tools, simply run:

```powershell
scoop update repos
```

## Issues & Contributing

If you encounter issues with the installation, please open an issue in this repository.
For issues with the specific tools (like `repos`), please open an issue in the [repos](https://github.com/MiguelRodo/repos).

