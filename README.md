# labWeb5


    <script>
        alert("Ini adalah contoh penggunaan alert di JavaScript.");
    </script>

untuk menggunakan allert di web
![image](https://github.com/user-attachments/assets/9637e0fc-f0ae-486c-abc9-c772502b6b54)
    
    <script>
        document.write("Hello, ini dari document.write!");
    </script>
documen.write adalah perintah untuk menulis pada halaman
![image](https://github.com/user-attachments/assets/2509c1ac-b235-4921-8c50-4fc5daebe3f9)

    <script>
        console.log("Hello, ini dari console.log!");
    </script>
console.log di gunakan hanya di halaman console di developer tools
![image](https://github.com/user-attachments/assets/06f3fe30-c975-4f13-8453-b09ba5886b79)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <script>
            function bodi(){
                //mengubah tag h3
                const teks = "manipulasi obejek body ketika halaman di load";
                var h3 = document.getElementById('tes');
                h3.innerText = teks;
                h3.style.color = 'white';
    
                //mengubah body
                document.body.style.backgroundColor = 'green';
                console.log('Bodinya telah diubah');
            }
        </script>
    </head>
    <body onload="bodi()">
        <h3 id="tes">Contoh conslode.log</h3>
    </body>
    </html>
    
mengunakan fungsi dan manipulasi obejek dengan javascript
![image](https://github.com/user-attachments/assets/7b520a17-1f9b-4693-9afc-404a4679e816)

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
            <style>
                form {
                    background: #fff;
                    padding: 30px;
                    border-radius: 5px;
                    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                }
                label {
                    display: block;
                    margin-bottom: 5px;
                }
                input[type="text"], input[type="password"] {
                    width: 100%;
                    padding: 10px;
                    border-radius: 3px;
                    border: 1px solid #ccc;
        
                }
                button {
                    margin-top: 10px;
                    padding: 10px 20px;
                    border-radius: 3px;
                    background: #333;
                    color: #fff;
                    border: none;
                    cursor: pointer;
                }
                button:hover {
                    background: #000;
                }
            </style>
        </head>
        <body>
            <form action="submit" method="post">
                <label for="nama">nama:</label>
                <input type="text" name="nama">
                <br>
                <label for="password">password:</label>
                <input type="password" name="password">
                <br>
                <button type="submit">kirim</button>
                
            </form>
            <script>
                //submit form
                document.querySelector('form').addEventListener('submit', function(event) {
                    event.preventDefault();
                    var nama = document.querySelector('input[name="nama"]').value;
                    var password = document.querySelector('input[name="password"]').value;
                    
                    //ini validasi form nya
                    if (nama === 'faisal fajar' && password === 'faisal juga') {
                        alert('nama dan password sesuai');
                    } else {
                        alert('nama atau password salah');
                    }
                    alert('nama :'+ nama + '\npassword :'+ password);
                });
              </script>
          </body>
          </html>
validasi form
![image](https://github.com/user-attachments/assets/9dc1eca6-c4dc-4fbc-81fb-cc9fde673420)


