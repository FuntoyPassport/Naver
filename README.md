# Naver
该库是为了支持SPM而建立的，库源为韩国的[NaverLogin](https://github.com/naver/naveridlogin-sdk-ios)，由于原库Package文件错误，故设立该库

## 二、接入步骤如下：

    1.通过脚本passport_config_unity_project.rb挂载该库。

    2.info.plist -> Queried URL Schemes -> 添加➕naversearchapp、naversearchthirdlogin两个item。

    3.URL Types添加naver的URL Schemes为funtoytest。【如需绑定包名，请naver后台保持一致】
