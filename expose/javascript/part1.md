1. values added: 20
2. final result: 20
3. You should avoid var because it’s function-scoped (not block-scoped), which can cause hidden name collisions and unexpected bugs. Use let or const instead.
4. values added: 20
5. There will be an error because the result isn't defined there. It was declared with let inside the if block.
6. Error occurs because you can't reassign const.
7. Error occurs because result isn't defined outside the if block.