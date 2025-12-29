# 思源字体中文 `TTF` 版本

- 方便`Kodi`等只支持`ttf`字体的软件使用
- 使用`github actions`进行自动转换

## 思源字体包含

- [思源黑体](https://github.com/adobe-fonts/source-han-sans)
- [思源宋体](https://github.com/adobe-fonts/source-han-serif)

## 中文包含

- `SourceHanSansSC` 思源黑体-简体中文
- `SourceHanSansTC` 思源黑体-繁体中文
- `SourceHanSerifSC` 思源宋体-简体中文
- `SourceHanSerifTC` 思源宋体-繁体中文

## 转换处理细节

- 使用[fonttools](https://github.com/fonttools/fonttools) 进行转换
- 请注意! 因为转换较为缓慢, 完成思源黑体 + 思源宋体 4 组 28 个字重的字体转换需要比较长的时间, 可能会触发 github 免费版账户 github actions 使用时间限制

## 开源协议

- 本项目采用[MIT协议](https://github.com/unix755/SourceHan-font-ttf/raw/main/LICENSE)
