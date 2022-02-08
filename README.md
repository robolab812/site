# site

```c#
BigInteger result = 1;

while (exponent > 0)
{
    if (exponent % 2 == 0)
    {
        @base *= @base;
        exponent /= 2;
    }
    else
    {
        result *= @base;
        exponent--;
    }
}
```

