# Cocos

## Log 如何显示打印的具体代码

<img width="1133" alt="image" src="https://user-images.githubusercontent.com/16253834/203248768-a1a33a89-1c73-4c7b-a0d6-7149958d4ce3.png">

因为默认开启了 vconsole 调试 

找到模版文件去掉就可以

路径：  /Applications/CocosCreator/Creator/2.4.9/CocosCreator.app/Contents/Resources/static/preview-templates/index.jade

```
if enableDebugger
  //script(type='text/javascript' charset='utf-8' src='app/node_modules/vconsole/dist/vconsole.min.js')
script(type='text/javascript' charset='utf-8' src='app/engine/bin/' + cocos2d)
```
