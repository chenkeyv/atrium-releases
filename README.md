# Atrium Releases

Atrium 的发布包。Atrium 是一个原生 macOS app，用 ACP（Agent Client Protocol）把多个 coding agent 收进同一个工作台。

这个仓库只放发布文件，不含源码，也不接收 issue。

## 下载

从 [Releases](https://github.com/chenkeyv/atrium-releases/releases) 下载 `Atrium-<版本>-macos-arm64.zip`。需要 macOS 27 和 Apple 芯片。

目前是 ad-hoc 签名、未公证。解压后执行下面的命令，或者右键选择"打开"：

```sh
xattr -dr com.apple.quarantine Atrium.app
```

每个 zip 都有一个同名的 `.sha256` 校验文件。
