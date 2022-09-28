#codingapple_homework

코딩애플 html/css 강좌 숙제

##9/28 email box

가끔 css가 js보다 어렵다는 생각이 든다..

어렵다기보다는 복잡하고 번거롭다.

```html
<div class="e_background">
    <div class="e_box">
        <form>
            <div class="e_title_box">
                <h3>Contact us</h3>
                <p>Your Email</p>
                <input type="text" class="e_input" placeholder="email@example.com">
            </div>
        </form>
    </div>
</div>
```

```css
.e_background {
  background-color: rgb(39, 39, 39);
  padding: 30px;
}

.e_box {
  padding: 30px;
  width: 80%;
  max-width: 600px;
  background-color: white;
  margin: auto;
}

.e_title_box {
  width: 80%;
}

.e_input {
  width: 100%;
  height: 40px;
  border-radius: 5px;
  font-size: 20px;
  padding: 0px 20px;
  border: 2px solid lightgray;
  outline: none;
}
```

js에서 변수,함수이름 짓는거랑 class 네임 짓는게 제일 힘들었음.
