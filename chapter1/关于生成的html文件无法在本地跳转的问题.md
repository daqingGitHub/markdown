##解决_book文件夹下html文件无法在本地跳转的问题

1.  找到_book/gitbook/theme.js文件
2. 在文件中搜索```if(m)for(n.handler&&```
3. 将```if(m)```改成```if(false)```