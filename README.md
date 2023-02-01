# SOLID
  1. Нарушение: В классе Purchase в переменной protected Purchase[] purchases = new Purchase[4] использовалось число 4 напрямую в коде. Исправление: заменила 4 на Main.products.size(). Для этого в классе Main я вынесла в статический метод HashMap<String, Integer> products = new HashMap<>();
  
  2. Подсказала IDEA. Нарушение: В классе Purchase в методе sum используется цыкл for, который делает код менее читабельным. Исправление: заменила цыкл for на foreach.
  
  3. Подсказала IDEA. Нарушение: В классе Purchase в методе sum  в строке  sum +=purchase.count * prices.get(purchase.title); переменная была типа int, а число в переменной sum может быть больше, чем способен хранить тип int.Исправление:  добавила после = (long).
