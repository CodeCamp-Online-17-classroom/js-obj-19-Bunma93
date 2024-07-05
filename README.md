# js-lab-65
### Lab65 Object: Guess Result4
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร

```JavaScript
var name = 'Joe';
function makeUser() {
  return {
    name: 'John',
    ref: this
  };
}
let user = makeUser();
console.log(user.ref.name); // * // *this ภายในฟังก์ชันนั้นจะอ้างอิงถึง window object user.ref.name จริงๆแล้วเป็นการอ้างอิงถึง window.name, ซึ่งมีค่าเป็น 'Joe'
```
-ปฏิพงษศกร บุญมา(เจมส์)