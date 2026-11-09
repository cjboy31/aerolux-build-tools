# aerolux-build-tools
Mirror of official toolchain releases (llvm-mingw, Rust, Slang, Python, PyTorch). Tools only; each archive keeps its upstream license.

DXC (Microsoft DirectX Shader Compiler, Linux x86-64) comes from its own manual workflow `fetch-dxc.yml` into `dist/dxc`, with the release asset checked against GitHub's recorded SHA-256.

The DirectX 12 Agility SDK (NuGet `Microsoft.Direct3D.D3D12`, owner: 1.722.0-preview) comes from its own manual workflow `fetch-agility.yml` into `dist/agility/<version>`, checked against NuGet's recorded SHA-512 and Microsoft's package signature. The package is kept unmodified with its licence.
