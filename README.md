# ビルド方法
ビルドするとsysrootやクロスコンパイラが手に入る

```bash
$ cd /root/buildroot-2025.08.2
# 設定一覧表示
$ make list-defconfigs | grep raspberry
# ビルド設定適応
$ make raspberrypi4_64_defconfig
# ビルド実施
$ make
```
