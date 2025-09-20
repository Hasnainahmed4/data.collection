# data.collection
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>collection</title>
</head>
<body>
    <h1>collection</h1>
    <script>
       let fruits = ["apple", "mango", "banana"];

       fruits.push("grapes");
       fruits.unshift("orange");
       let del = fruits.pop();
       fruits.shift();

       console.log(fruits);
       console.log(fruits.length);
       let person={
        name : "hasnain",
        age : 18,
        isstudent : true,
        fess : 8650
  };
         console.log(person);
         console.log(person.fee);
            console.log(person.name);
            console.log(person["name", "age" ,"CGPA"]);
            delete person.salary;
            console.log(person);
            let student=[
                {name :"hamza",age  :25,islate : true},
                {name :"rohaan",age :18,islate : true},
                {name :"hassan",age : 21,islate: true},
                {name :"hasnain",age : 22,islate: true},
            ];
            console.log(student);
            console.log(student[1]);
            console.log(student[1].name);

            function sayhello( ){
                console.log("hello hasnain");
                alert("hello fuction is working");
            };

            sayhello();

            //function with parameter
            function greet(name){
                console.log("hello my name is " + name);
            };
            greet("hasnain");
            greet("hamza");
            //function with return value
            function add(a,b){
                return a + b;
            };
            let sum = add(5,10);
            console.log(sum);

            function addition(){
                const aa = 5;
                const bb = 10;
                console.log("sum=", aa + bb);

            };
            addition()

            function welcome(name = "guest"){
                console.log("welcome" + name)
            };
            welcome();
            welcome("hasnain");
        
            function isEven(num) {
                if(num % 2 === 0){
                    return "Even";
                }else{
                    return "Odd";
                }
            }

            console.log(isEven(8));

            </script>
</body>            
</html>
