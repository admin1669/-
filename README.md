# -
存放python爬虫的代码
class A:
    def h(self):
        print('我是父类的方法')
class B(A):
    
    def h(self):
        
        print('我是子类的方法')
        super().h()

b=B()
