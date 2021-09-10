- 👋 Hi, I’m @Damir-Karomatullaev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---from kivy.app import App 
from kivy.uix.button import Button
from kivy.uix.widget import Widget
from kivy.uix.label import Label
from kivy.uix.boxlayout import BoxLayout

from kivy.uix.gridlayout import GridLayout

from kivy.config import Config

Config.set('graphics', 'resizable', '0')
Config.set('graphics', 'width', '400')
Config.set('graphics', 'height', '500')


class CalculatorApp(App):
    
    def update_label(self):
        self.lbl.text = self.formula

    def add_number(self, instance):
        if(self.formula == "0"):
            self.formula = ""

        self.formula += str(instance.text)
        self.update_label()

    def add_operation(self, instance):
        if (str(instance.text) =="x"):
            self.formula += "*"
        else:
            self.formula += str(instance.text)
        
        self.update_label()
    
    def add_clear(self, operation):
        if operation == "C":
            self.formula += ""
        
     
    def calc_result(self, instance):
        self.lbl.text = str(eval(self.lbl.text))
        self.formula = ""
    def build(self):
        self.formula = ""
        bl = BoxLayout(orientation = 'vertical', padding = 25)
        gl = GridLayout(cols = 5, spacing = 1.5, size_hint = (1, .7))
        
        self.lbl = Label(text = "0", font_size = 40, halign = "right",
         size_hint = (1, .3), text_size = (400 - 50, 500 * .3 - 50,
         ))
        bl.add_widget (self.lbl)

        gl.add_widget (Button(text = "7", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "8", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "9", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "x", on_press = self.add_operation,
            background_color = [0, 1, 0, 1]) )
        gl.add_widget (Button(text = "(", on_press = self.add_operation,
            background_color = [255, 69, 0, .5]) )

        gl.add_widget (Button(text = "4", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "5", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "6", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "-", on_press = self.add_operation,
            background_color = [0, 1, 0, 1]) )
        gl.add_widget (Button(text = ")", on_press = self.add_operation,
            background_color = [255, 69, 0, .5]) )

        gl.add_widget (Button(text = "1", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "2", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "3", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "+", on_press = self.add_operation,
            background_color = [0, 1, 0, 1]) )
        gl.add_widget (Button(text = "%", on_press = self.add_operation,
            background_color = [0, 1, 0, 1]) )

        gl.add_widget (Button(text = ",", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "0", on_press = self.add_number,
            background_color = [0, .55, .88, 5]) )
        gl.add_widget (Button(text = "=", on_press = self.calc_result,
            background_color = [1, .2, 0, 1]) )
        gl.add_widget (Button(text = "/", on_press = self.add_operation,
            background_color = [0, 1, 0, 1]) )
        gl.add_widget (Button(text = "", on_press = self.add_clear,
            background_color = [0, 0, 0, 1]) )

        bl.add_widget (gl)
        return bl



if __name__ == "__main__":
    CalculatorApp().run()
Damir-Karomatullaev/Damir-Karomatullaev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
