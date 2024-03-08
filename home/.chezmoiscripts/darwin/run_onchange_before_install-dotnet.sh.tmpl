#!/usr/bin/env sh

set -ex

arch="{{ .chezmoi.arch }}"

# Ensure directory exists.
mkdir -p ~/.local/share/dotnet

# Download & install for x86_64
if [ "$arch" = "amd64" ]; then
  curl https://download.visualstudio.microsoft.com/download/pr/85bcc525-4e9c-471e-9c1d-96259aa1a315/930833ef34f66fe9ee2643b0ba21621a/dotnet-sdk-8.0.201-linux-x64.tar.gz | tar -C ~/.local/share/dotnet -xz
  curl https://download.visualstudio.microsoft.com/download/pr/8828b97b-7bfd-4b1b-a646-e55bddc0d7ad/e2f7d168ad273e78fbae72ffb6d215d3/dotnet-sdk-6.0.419-linux-x64.tar.gz | tar -C ~/.local/share/dotnet -xz
  exit
fi

# Download & install for arm64
if [ "$arch" = "arm64" ]; then
  curl https://download.visualstudio.microsoft.com/download/pr/3bebb4ec-8bb7-4854-b0a2-064bf50805eb/38e6972473f83f11963245ffd940b396/dotnet-sdk-8.0.201-linux-arm64.tar.gz | tar -C ~/.local/share/dotnet -xz
  curl https://download.visualstudio.microsoft.com/download/pr/3b18aefa-0e14-4193-a167-35e1de4cfe46/acf2b230ae3ecfbc4d5f4c20cbf97b2d/dotnet-sdk-6.0.419-linux-arm64.tar.gz | tar -C ~/.local/share/dotnet -xz
  exit
fi

echo "Unknown architecture [$arch] when installing .NET"
exit 1
