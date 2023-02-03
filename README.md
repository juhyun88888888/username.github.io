# juhyun88888888.github.io
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .inline-grid{
        font-size: 0;
    }
.inline-grid > *{
    display: inline-block;
    vertical-align: top;
    font-size: 1rem;
}
body{
    margin: 0;
}
section{
    border: 10px solid red;
    height: 500px;
}
section > div{
    width:calc(100% / 7);
    height:50%;
    background: #000;
    display: inline-block;
    color:white;
    font-weight:bold;
    text-align:center;
}
section>div:nth-child(2n){background-color: rgba(83, 74, 74, 0.87);}
</style>
<body>
<section class="inline-grid">
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
    <div>텍스트</div>
</section>
