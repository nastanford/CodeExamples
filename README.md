# CodeExamples

## Async Await (Fetch)
[Fetch API in JavaScript for AJAX Developers](https://www.youtube.com/watch?v=ZTQcJWixB1k)
[Using Asysnc/Await with the Fetch API](https://www.youtube.com/watch?v=Yp9KIcSKTNo)
```
async function showUserInConsole() {
  const response = await fetch("data/user.json");
  const user = await response.json();
  console.log(user);
}
showUserInConsole();
```

