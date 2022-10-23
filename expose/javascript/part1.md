### Answers:
1. 20
2. 20
3. 20
4. The code returns a reference error because result is not defined at the scope in line 13 because `let` uses **block scope**
5. The code returns a TypeError because you can not assign a `const` varaible a value after the first assign, because of this, the error happens at line 7 and thus line 9 does not execute.
6. The code returns a TypeError because you can not assign a `const` varaible a value after the first assign, because of this, the error happens at line 7 and thus line 13 does not execute. If line 13 did execute then it would also be an error because `result` is not defined in the scope for line 13.