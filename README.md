# Actions-"D"penWrt

Build OpenWrt using GitHub Actions

#仓库介绍：

  本仓库基于P3TERX大佬的Actions-OpenWrt,用编译地皮定制的固件，现成固件请到Actions下载，现在还处于测试阶段，欢迎fork！
  
#本仓库逻辑介绍：
  
  #[切换到diy-1分支查看地皮定制的所有.config文件~](https://github.com/DefiedParty/Actions-DpenWrt/tree/diy-1)
  #[work分支用于生成固件](https://github.com/DefiedParty/Actions-DpenWrt/tree/work)
  #[那么master就是P3TERX大佬的原版](https://github.com/DefiedParty/Actions-DpenWrt/)

#如何使用：
  1.先fork到你的库，或者点使用模板
  2.从diy-1提交一个.config到work分支
  3.在Actions里面就可以看到啦！
  
  
## 原版说明如下

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository, and the build starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Acknowledgments

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE) © P3TERX
