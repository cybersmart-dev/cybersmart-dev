
## Welcome 
#### I am cybersmart 
- Software Engineer
- Security Researcher 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        [class*='text-red']{
            color: red;
        }
        [class*='text-blue']{
            color: blue;
        }
        [class*='text-green']{
            color: green;
        }
        
        [class*='text']:hover{
            
            
            transition-duration: 1s;
            transition-timing-function: linear;
            animation-name: toright;
            animation-iteration-count: 1;
            animation-duration: 1s;
            animation-timing-function: linear;
            padding-right: 15px;
        }
        
        @keyframes toright {
            0%{
                transform: translateX(0%);
            }
            100%{
                transform: translateX(50%);
            }
        }
        ul{
            list-style-type: decimal-leading-zero;
        }
    </style>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is my <spam class="text-red">site</spam></p>
    <ul>
        <li class="text-red">This is red color</li>
        <li class="text-blue">This is blue color</li>
        <li class="text-green">This is green color</li>
    </ul>
    
</body>
</html>
