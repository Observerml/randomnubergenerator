let i = 0;
let d = 0;
let t = Math.random(1234234); // рандомное число
prompt('Enter number:', function (d) {
while (i < d) { 
    i = i + 1;
    i = i * 2;
    // console.log(i) //debug tool
    i = i + 2;
    i = i * 3;
    i = i + 3;
    i = i * 4;
    i = i + 4;
    i = i * 5;
    i = i * t;
    
 // console.log(i) //debug tool
}
console.log(i)
process.exit();
});

// функция для ввода пользователя (не очень сложная нашел угадайте где? на стаковерфлоу)
function prompt(question, callback) {
    var stdin = process.stdin,
        stdout = process.stdout;
    stdin.resume();
    stdout.write(question);
    stdin.once('data', function (data) {
        callback(data.toString().trim());
    });
}
