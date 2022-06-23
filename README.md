# CodeExamples

## Async Await (Fetch)
```
async function showUserInConsole() {
  const response = await fetch("data/user.json");
  const user = await response.json();
  console.log(user);
}
showUserInConsole();

```
