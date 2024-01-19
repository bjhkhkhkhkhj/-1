class Widget():
    def __init__ (self,text,x,y):
        self.text=text
        self.x=x
        self.y=y
    def print_info (self):
        print(f"Напис:{self.text}")
        print(f"Напис:{self.x} {self.x}")
class Button(Widget):
    def __init__(self, text, x, y):
        super().__init__(text, x, y)
        self.is_clicker = False
    def click (self):
        self.is_clicker = True
        print("Ви зареєстровані")
q = Button("Брати участь", 100,100)
q.print_info()
qwestion = input("Хочете зареєструватись? (так/ні):").lower()
if qwestion=="так":
    q.click()
else:
    print("А Шкода")