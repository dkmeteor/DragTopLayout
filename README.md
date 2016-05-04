针对个人需求做2个修改:

- 修改onlayout,初始状态为open时不会闪烁 
- 修改onViewReleased方法,yvel=0时不触发响应,防止嵌套SwipeRefreshlayout时,因为事件被拦截,错误触发open/close动画. 


没特别需求请使用原作者的工程 [chenupt/DragTopLayout](https://github.com/chenupt/DragTopLayout)