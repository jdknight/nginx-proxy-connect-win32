# nginx-proxy-connect-win32

## Overview

This package can be used to build [nginx][nginx] for Windows which includes
the [ngx_http_proxy_connect_module][ngx_http_proxy_connect_module] module.

## Build Requirements

* Microsoft Visual C compiler
* [MSYS][msys] or [MSYS2][msys2]
* [Mercurial][hg]
* Perl (e.g. [ActivePerl][activeperl] or [Strawberry Perl][strawberryperl])
* [releng-tool][releng-tool]

## Performing a build

- Open a Visual Studio developer command prompt
  (e.g. "Developer Command Prompt for VS 2019").
- Ensure MSYS/MSYS2 is included on the system path.
- Invoke a build:

  ```shell
  releng-tool
  ```

The resulting build should be stored in the `output/images` folder.


[activeperl]: https://www.activestate.com/products/perl/
[hg]: https://www.mercurial-scm.org/
[msys2]: https://www.msys2.org/
[msys]: https://sourceforge.net/projects/mingw/files/MSYS/
[releng-tool]: https://releng.io/
[strawberryperl]: https://strawberryperl.com/
[nginx]: https://nginx.org/
[ngx_http_proxy_connect_module]: https://github.com/chobits/ngx_http_proxy_connect_module
