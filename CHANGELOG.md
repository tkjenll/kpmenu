# Changelog
## 1.4.0 (2021/08/07)
* Added OTP support
* Updated go modules

## 1.3.0 (2021/04/12)
* Added support for wofi
* Added custom executables, now you can configure the executable for every prompt and clipboard action
* `-r`/`--rofi` option is not used anymore, use `-m rofi`/`--menu=rofi` instead
* Typo in logging
* Updated libraries
* Updated to go 1.16

## 1.2.1 (2019/10/14)
* Updated libraries
* Improved makefile
* Updated to go 1.13

## 1.2.0 (2019/04/16)
*   Added daemon mode (option `--daemon`)
*   Updated viper and gokeepasslib libraries

## 1.1.1 (2019/03/27)
*   Added credentials log message to debug better
*   Fixed some code typos

## 1.1.0 (2019/03/25)
*   Added support for `wl-clipboard`
*   New option `--clipboardTool` to choose which clipboard manager to use
*   Changed option `--clipboard` to `--clipboardTimeout`
*   Fixed some typos
