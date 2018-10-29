---
title: If Else Statement
---

# If Else Statement

The If-Else statement executes a block of code depending if your precondition is fullfilled or not.

## Example
```

if(boolean expression)
{
// execute this code block if expression evalutes to true
}
else
{
// always execute this code block when above if expression is false
}


int Price = 30;

If (Price == 30)
{
  Console.WriteLine("Price is equal to 30.");
}

Else 
{
  Console.WriteLine("Price is not equal to 30.");
}
```

Since we already declared our int Price to be 30, this will be the expected output.

There can be multiple conditions, outcomes that are expected and can be executed properly using an if-else statement.  Furthermore, if there is only one line following either the 'if' and/or the 'else' then '{}' are not needed, rather just a tab.

```

int Price = 30;

If (Price == 30)
  Console.WriteLine("Price is equal to 30.");

Else if (Price > 30)
  Console.WriteLine("Price is greater than 30.");

Else
  Console.WriteLine("Price is less than 30.");
```

## Output
```
Price is equal to 30.
```
