# ClawPanel Release Files

此目录存储从 [maynorai-clawpanel](https://github.com/xianyu110/maynorai-clawpanel) 自动同步的发布文件。

## 文件说明

### macOS
- `maynoraiclawpanel_*_aarch64.dmg` - Apple Silicon (M1/M2/M3/M4)
- `maynoraiclawpanel_*_x64.dmg` - Intel

### Windows
- `maynoraiclawpanel_*_x64-setup.exe` - EXE 安装器（推荐）
- `maynoraiclawpanel_*_x64_en-US.msi` - MSI 安装器

### Linux
- `maynoraiclawpanel_*_amd64.AppImage` - AppImage（免安装）
- `maynoraiclawpanel_*_amd64.deb` - DEB（Debian/Ubuntu）
- `maynoraiclawpanel-*.x86_64.rpm` - RPM（Fedora/RHEL）

## 同���机制

这些文件由 GitHub Actions 自动同步，每当 maynorai-clawpanel 发布新版本时，会自动下载并复制到此目录。
