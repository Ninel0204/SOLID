# SOLID
  1. Магическое число. В классе Purchase в переменной protected Purchase[] purchases = new Purchase[4] заменила 4 на Main.products.size().Для этого в классе Main я вынесла в статический метод 
  HashMap<String, Integer> products = new HashMap<>();
  
  2. Принцип инверсии зависимостей. В классе Main в  HashMap<String, Integer> products я заменила на  Map<String, Integer> products.
  
  3. Подсказала IDEA. В классе Purchase в методе sum заменила цыкл for на foreach.
  
  4. Подсказала IDEA. В классе Purchase в методе sum  в строке  sum +=purchase.count * prices.get(purchase.title); добавила после = (long).
