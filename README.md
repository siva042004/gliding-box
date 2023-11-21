# Exp-10-Create-a-Gliding-box-using-CSS-Animation
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gliding Box Animation</title>
  <style>
    body {
        margin: 0;
        padding: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #f4f4f4;
      }
      
      .gliding-box {
        width: 100px;
        height: 100px;
        background-color: #000000;
        animation: glide 2s linear infinite;
      }
      
      @keyframes glide {
        0% {
          transform: translateX(0);
        }
        50% {
          transform: translateX(200px);
        }
        100% {
          transform: translateX(0);
        }
      }
      
  </style>
</head>
<body>
    <h1>Gliding Box Animation</h1>
  <div class="gliding-box"></div>
</body>
</html>

```

# output
![Screenshot (85)](https://github.com/21002624/Exp-10-Create-a-Gliding-box-using-CSS-Animation/assets/113762183/feebf223-42b1-47c3-a333-97bfc2314efa)
