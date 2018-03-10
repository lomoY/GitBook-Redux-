# Context

在一些场景中，你希望把数据一层层传递到不同的组件层，但是你又不想要显示的去在每一个组件里去对参数进行声明（比如某个参数只有在第10层组件才会用到，你就得在前9层都去获得这个值），那你就可以使用context API。

但暂不推荐使用该API，因为它并不稳定，为了实现类似Context的效果，可以使用React-redux库

### API:getChildContext

当state或者props改变的时候这个方法会被调用，但这个API有问题，**React官方不建议使用**
