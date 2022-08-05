## Janista Sihirunwong 645162010030

## LAB 5 วิธีการ run ที่ docker desktop

<p>1. clone project จาก repository DPU_CT519_Lab5 ลงมาที่เครื่อง  </p>
<p>>> git clone https://github.com/Janistamail/DPU_CT519_Lab5</p>
<p>2. เปิด terminal และ cd เข้าไปใน DPU_CT519_Lab5/</p>
<p>3. build dockerfile คำสั่ง >> "docker build -t my-golang-app ."</p>
<p>4. run container คำสั่ง  >> "docker run -it --rm --name my-running-app -p 5000:8090 my-golang-app"</p>
<p>5. เปิด browser 127.0.0.1:5000/about เพื่อ test ได้เลย</p>
<img width="300px" height="200px" src="./img/loginAdminer.png">
