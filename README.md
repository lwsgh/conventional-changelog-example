# conventional-changelog-example

```bash
# 生成 Changelog
conventional-changelog -p angular -i CHANGELOG.md -s
# 生成所有发布的 Changelog
conventional-changelog -p angular -i CHANGELOG.md -s -r 0
# 在命令行中生成log，并不生成文件
conventional-changelog -p angular -i CHANGELOG.md -w
```

注意:
需要手动修改 package.json 中的版本号
