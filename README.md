# 自我介绍
## 我叫青砚，我的爱好有
* 阅读
* 游戏
* 电影
* 音乐
* 旅游
# 
## 我喜欢的书籍
1.  哈利波特
2.  全职高手
3.  盗墓笔记 
#  
## 关于回文数
```javascript
/**
 * @param {number} x
 * @return {boolean}
 */
var isPalindrome = function(x) {
 if (x < 0) return false
      var str = '' + x
      strChange = str.split('').reverse().join('')
      return strChange === str
    }
```
