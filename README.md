fun numerosDesc(n: int) {
    if (n <= 0)
    {
        return
        }
    printIn(n)
    numerosDesc(n - 1)
    }
fun main ()
{
    val num = 5
    numerosDesc(num)
   }  
