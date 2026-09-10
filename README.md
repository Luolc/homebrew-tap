# homebrew-tap

[Homebrew](https://brew.sh/) tap，放 [Luolc](https://github.com/Luolc) 自己那几个工具的 formula。

## 用法

```sh
brew install luolc/tap/limae
```

或者先 tap 再装：

```sh
brew tap luolc/tap
brew install limae
```

macOS 与 Linuxbrew 都可以。

## 这里有什么

| Formula | 是什么 | 上游 |
| --- | --- | --- |
| `limae` | Markdown linter，从中文技术写作的排版规则起步 | [Luolc/limae](https://github.com/Luolc/limae) |

## 这个仓不手工改

`Formula/` 下的文件由上游仓库的发布流程在打 tag 时自动更新 —— 版本号与 sha256 都取自那次
发布真正产出的 GitHub Release 资产。**手工改会在下一次发布时被覆盖**；
要改 formula 的形状，改上游那份模板。

formula 指向的是上游 Release 里的预编译二进制，`brew install` 不会在本机编译。
