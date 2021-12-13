# BaBoost6AnkHelloGitHub
Program Boyunca Yaptığım Çalışmalar
----

**N O T**
- tire boşluk liste yapar
- CTRL + A  imlecin bulunduğu tüm sayfayı seçer
- CTRL + C CTRL + V kopyala yapıştır yapar(imlecin bulunduğu satır)
- CTRL + X de kesme yapar
- Shift + Delete imlecin bulunduğu satırı siler
- Ctrl+ Y ileri alır
- shift +Home Tuşu Satırın Başına Gider
- shift+end satır souna kadar gider
- Shift+ yön tuşları aralık seçer (yazıyı seçe seçe ilerler)
- **altgr + noktalivirgül buraya kod yazmamızı sağlar**
- [kodlamastesi](https://try.dot.net)
- ``` 3 tane yapıp ``` ``` buraya kod gelecek ```(3tane altgr noktalı virgül yapıp araya kodu yapıştırırsak alttaki gibi gorunur
-----
```cs
using System;
using System.Collections.Generic;
using System.Linq;

public class Program
{
  public static void Main()
  {
    foreach (var i in Fibonacci().Take(20))
    {
      Console.WriteLine(i);
    }
  }

  private static IEnumerable<int> Fibonacci()
  {
    int current = 1, next = 1;

    while (true) 
    {
      yield return current;
      next = current + (current = next);
    }
  }
}
```



**Markdown CheatSheet :**<---soldaki bold yazı  [CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


4 tane çizgi çizgi satırı oluşturuyor

----
| Tables | Are | Cool | Cool |
| ------------- |:-------------:| -----:| -----:|
| col 3 is | right-aligned | $1600 | $1600 |
| col 2 is | centered | $12 | $12 |
| zebra stripes | are neat | $1 | $1 |

![](https://media.giphy.com/media/QvXe5wq8w94A0/giphy.gif)

![image](https://user-images.githubusercontent.com/95921510/145805693-100f3bf7-e8ca-435d-b3f8-3976fb2d02b0.png)
