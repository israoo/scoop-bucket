# Scoop bucket

## Description

This is a custom Scoop bucket that hosts application manifests for Windows. It provides easy installation and management of applications developed by israoo through the Scoop package manager.

## Featured project

- **[TerraX](https://github.com/israoo/terrax)** - The interactive TUI executor for Terragrunt stacks

## Installation

### 1. Add the bucket

First, add this custom bucket to your Scoop installation:

```powershell
scoop bucket add israoo https://github.com/israoo/scoop-bucket
```

### 2. Install TerraX

Once the bucket is added, you can install TerraX:

```powershell
scoop install israoo/terrax
```

## Usage

After installation, you can use TerraX directly from the terminal:

```powershell
terrax
```

For more information on how to use TerraX, check out the [project documentation](https://github.com/israoo/terrax).

## Updating

To update TerraX to the latest version:

```powershell
scoop update terrax
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions to improve the manifests, please:

1. Open an [issue](https://github.com/israoo/scoop-bucket/issues)
2. Submit a pull request with your improvements

## License

This bucket is licensed under the [MIT License](LICENSE).

**Note:** Individual projects may have their own licenses. For example, TerraX is licensed under Apache 2.0. Please refer to each project's repository for details.

## Support

If you have questions or need help with any of the tools:

- Check the specific project's documentation
- Open an issue in the corresponding repository
- Contact the maintainer: [@israoo](https://github.com/israoo)

---

**Maintained by** [israoo](https://github.com/israoo)
Scoop Bucket for installing command-line tools developed by israoo.
