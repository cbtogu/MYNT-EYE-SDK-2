# 编译 on Linux {#guide_build_linux}

> Ubuntu 16.04, Ubuntu 14.04

## 获取代码

```bash
git clone https://github.com/slightech/MYNT-EYE-SDK-2.git
```

## 准备依赖

```bash
cd mynt-eye-sdk-2/
make init
```

## 编译代码

```bash
make install
```

结果：

![make install](make_install.png)

\latexonly
\includegraphics[width=0.6\textwidth,keepaspectratio]{make_install.png}
\endlatexonly

> CMake 如何引入编译好的库，可参考 `samples/CMakeLists.txt` 里的配置。
