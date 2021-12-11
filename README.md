# RouterOS CN IP List

CN ip list script generator for MikroTik RouterOS

[![status](https://img.shields.io/github/workflow/status/smartcatboy/routeros-cnip-cidr/cnip-cidr-gen?color=34d058&label=cnip-cidr-gen&logo=github&logoColor=fff)](https://github.com/smartcatboy/routeros-cnip-cidr/actions/workflows/cnip-cidr-gen.yml)

## To use

```Ros Shell
# CDN, fast
/tool fetch url="https://cdn.jsdelivr.net/gh/smartcatboy/routeros-cnip-cidr/dist/cn_ip_cidr.rsc" dst-path=cn.rsc;

# if CDN does't work, use this
/tool fetch url="https://raw.githubusercontent.com/smartcatboy/routeros-cnip-cidr/master/dist/cn_ip_cidr.rsc" dst-path=cn.rsc;

/import file-name=cn.rsc;
```

## Tanks to

[ispip.clang.cn](https://ispip.clang.cn/)
[ipip.net](https://en.ipip.net/)
