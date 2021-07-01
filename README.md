# kivyPython_FormLayout
# In The Name Of God
# Python
# Kivy
# Buttons of Calculator

from kivy.app import App
from kivy.uix.button import Button
from kivy.uix.label import Label
from kivy.base import runTouchApp
from kivy.uix.widget import Widget
from kivy.lang import Builder
from kivy.uix.floatlayout import FloatLayout

class Buttonsapp(App):
    def build(self):
        f1=FloatLayout()
        btn1=Button(text="1" , font_size=20 , pos_hint={'x':.0  , 'y':.7} , size_hint=(.2, .2) , background_color=(.6 ,.7 ,.9 ,.9) ,)
        f1.add_widget(btn1)

        btn2 = Button(text="2", font_size=20, pos_hint={'x': .2, 'y': .7}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn2)

        btn3 = Button(text="3", font_size=20, pos_hint={'x': .4, 'y': .7}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn3)

        btn4 = Button(text="4", font_size=20, pos_hint={'x': .0, 'y': .5}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn4)

        btn5 = Button(text="5", font_size=20, pos_hint={'x': .2, 'y': .5}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn5)

        btn6 = Button(text="6", font_size=20, pos_hint={'x': .4, 'y': .5}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn6)

        btn7 = Button(text="7", font_size=20, pos_hint={'x': .0, 'y': .3}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn7)

        btn8 = Button(text="8", font_size=20, pos_hint={'x': .2, 'y': .3}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn8)

        btn9 = Button(text="9", font_size=20, pos_hint={'x': .4, 'y': .3}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn9)

        btn10 = Button(text="0", font_size=20, pos_hint={'x': .2, 'y': .1}, size_hint=(.2, .2),
                      background_color=(.6, .7, .9, .9), )
        f1.add_widget(btn10)




        return f1
        return f2
        return f3
        return f4
        return f5
        return f6
        return f7
        return f8
        return f9
        return f10

if __name__=='__main__':
    Buttonsapp().run()



