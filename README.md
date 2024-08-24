# custom-modal
a custom pure html and css made modal


![image](https://github.com/user-attachments/assets/dcdc075e-53a6-4a7f-95ef-a0a42434ef93)


## How to use it?

first in the header part of your html document add the css file and like it to your project. just like the below.
```html
 <link rel="stylesheet" href="./modal.css" >
```

second you need to add the js file to your html document just like this: 

```js
  <script src="./modal.js"></script>
```
I suggest you to add it before the body tag closing.

and then add the code below to your html document 

```html
 <div class="modal-container hide" id="modal">
        <div class="modal w50-p">
            <div class="modal-header">
                <span onclick="closeModal('modal')" class="modal-close-button">X</span>
            </div>
            <div class="modal-body">
                <p>
                    ...
                </p>
            </div>
        </div>
    </div>
```

### lunch the modal
to lunch the modal, lets consider you want to lunch it when the button onclick event fired.

just call ``` localModal({{id-placeholder}}) ``` function with the modal id as a parameter.

like this: 

```html

 <button onclick="loadModal('modal')">
        lunch modal
 </button>

```
