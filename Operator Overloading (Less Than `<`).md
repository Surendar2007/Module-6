# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
class A : 

def  init (self,a): 

self.a=a 

def  lt (self,o): 

if self.a < o.a : 

return "ob1 is less than ob2" 

else: 

return "ob2 is less than ob1" 

ob1 = A(2) 

ob2 = A(3) 

print(ob1<ob2) 

## Output
![image](https://github.com/user-attachments/assets/e4781f60-fab3-47e3-8531-43bf86e77ba2)

## Result
   Thus, the program has been successfully executed.
