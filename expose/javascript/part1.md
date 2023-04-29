1. values added: 20
2. final result: 20
3. values added: 20
4. error, because result is defined with let, which means it is as block scope in the if block, so line 13 cannot access it.
5. error, because result is a const variable, it cannot be change by line 9.
6. error, because there is a type error in line 9, so line 13 would not be access. Even though it can be access, there still an error because result is defined with const, which means it is as block scope in the if block, so line 13 cannot access it.