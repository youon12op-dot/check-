<header>
    <h1>ระบบเช็คการเข้าบ้าน</h1>
    <p>วิทยาลัยการอาชีพปราสาท</p>
</header>

<div class="container">
    <label>ชื่อผู้เข้าบ้าน:</label>
    <input type="text" id="name" placeholder="กรอกชื่อ">
    <label>ตำแหน่ง:</label>
    <input type="text" id="location" placeholder="กรอกตำแหน่ง">
    <button onclick="checkIn()">เช็คเข้า</button>

    <div class="time-mode">
        <button onclick="setTimeMode('morning')">เช้า</button>
        <button onclick="setTimeMode('noon')">เที่ยง</button>
        <button onclick="setTimeMode('afternoon')">บ่าย</button>
        <button onclick="setTimeMode('evening')">เย็น</button>
        <button onclick="setTimeMode('night')">กลางคืน</button>
    </div>

    <h3>บันทึกข้อมูล</h3>
    <pre id="log" class="log"></pre>
</div>
