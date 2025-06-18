### code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MEDIA QUERIES</title>
    <link rel="stylesheet" href="media.css">
</head>
<body>
    <div class="container">
        <div class="item item1">
            Header
        </div>
        <div class="item item2">
            This is the Navigation Bar
        </div>
        <div class="item item3">
            Item3
        </div>
        <div class="item item4">
            Item4
        </div>
        <div class="item item5">
            Item5
        </div>
        <div class="item item6">
            Item6
        </div>
    </div>
</body>
</html>
```
### css file
```
.container{
    background-color: #578FCA;
    width:100vw;
    height:100vh;
    display:grid;
    row-gap:26px;
    column-gap:30px;
    grid-template-columns: repeat(3,1fr);

    grid-template-rows: 0.3fr 0.7fr 0.7fr;

    margin:0px;
    padding:56px;
    align-items:center;
    justify-items:center;
}
.item1{
    grid-column-start: 1;
    grid-column-end:4;
}
.item2{
    grid-row-start:2;
    grid-row-end:4;
}
.item{
    display:grid;
    justify-content:center;
    width:100%;
    font-size:2em;
    height:100%;
    background-color:#F5F0CD;
    align-items:center;
    margin:auto;
}
@media (min-width: 319px) and (max-width: 481px) {
  

  .container {
    padding: 20px !important;
    background-color:#8E9775;
  }

  .item {
   
    background-color: #BED7DC;
    color:black ;
  }
}
@media (min-width: 481px) and (max-width: 1200px) {
  

  .container {
    padding: 20px !important;
    background-color:#9EBC8A;
  }

  .item {
   
    background-color: #537D5D;
    color: #FDFAF6;
  }
}

```
