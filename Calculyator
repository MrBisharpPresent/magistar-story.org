print "Starting Program..."
os.clock()
print "Loading Program..."
print "Список функций: * , - , + , / ."
local a
local b
local c
local d
local otvet
local e
local q
local quit
function calt()
print("Калькулятор. MrBisharp")
io.write("Первое число :")
a = io.read()
io.write("Функция :")
b = io.read()
function error()
if b == "+" then
d = b
elseif b == "-" then
d = b
elseif b == "*" then
d = b
elseif b =="/" then
d = b
else
print("Неверное знечение")
e = 1
b = nil
end
end
repeat e = 1 
error()
until
io.write("Второе число :")
c = io.read()
if d == "+" then
print(a .. d .. c .. "=" .. a+c)
otvet = a + c
elseif d == "-" then
print(a .. d .. c .. "=" .. a-c)
otvet = a - c
elseif d == "*" then
print(a .. d .. c .. "=" .. a*c)
otvet = a * c
elseif d == "/" then
print(a .. d .. c .. "=" .. a/c)
otvet = a / c
end
print(otvet)
end
calt()
function rep()
print("Продолжить роботу ?")
print("Y или N")
q = io.read()
if q == "y" then
calt()
elseif q == "n" then
else
rep()
end
end
rep()
