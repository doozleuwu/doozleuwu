```py
class Programmer:

    def __init__(self, name: str):
        self.name = name
    
    def print_name(self):
        print(self.name)

if __name__ == '__main__':
    doozle = Programmer(name = 'doozle#4585')
    doozle.print_name()
