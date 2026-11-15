# Web：CSS 选择器速记

```css
div { }              /* 元素选择器 */
.box { }            /* 类选择器 */
#header { }         /* ID 选择器 */
div p { }           /* 后代选择器（div 里的 p） */
div > p { }         /* 子选择器（直接子元素） */
a:hover { }         /* 伪类：鼠标悬停 */
input[type="text"] { }  /* 属性选择器 */
```

- 优先级：ID > 类 > 元素，`!important` 最高但别滥用。
- 选不中元素时，先确认选择器有没有写错层级，再怀疑优先级。
- 类名用 kebab-case（`nav-item`），别用驼峰，团队好统一。
