<p align="center"><img src="https://image.flaticon.com/icons/svg/1066/1066419.svg" width="175"></p>
<h1 align="center">Accept multiple request at once</h1>

Well I recently wanted to follow everyone everyone whom my friend follows. But it was quite boring to go through the list and click on follow button. So I decided to something like this.

### Follow multiple GitHub users at once 

- Go to `Inspect` in your browser 
- Go to followers page
- Run this command on console 

```javascript
var temp = document.getElementsByClassName('btn-sm');
for(let i = 0; i<temp.length; i+=2) {
    temp[i].click();
}
```

![Github Follow](./src/github.png)

### Accepting Multiple Connections on Linkedin 
- Go to `Inspect` in your browser 
- Go to your connection's page
- Run this command on console

```javascript
var temp = document.getElementsByClassName('artdeco-button--secondary');
for(let i = 0; i<temp.length; i++) {
    temp[i].click();
}
```

![Linkedin Connections](./src/linkedin.png)

## Thanks for reading 😄

## Author
[Aman Raj](https://github.com/amanraj1608)

[<img src="https://image.flaticon.com/icons/svg/174/174857.svg" width="35" padding="30">](https://linkedin.com/in/amanraj1608)
[<img src="https://image.flaticon.com/icons/svg/174/174855.svg" width="35" padding="30">](https://www.instagram.com/amanraj1608/)
[<img src="https://image.flaticon.com/icons/svg/733/733579.svg" width="35" padding="30">](https://twitter.com/amanraj1608)
