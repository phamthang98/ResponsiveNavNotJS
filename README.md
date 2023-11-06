# ResponsiveNavNotJS

## Đây là template mẫu responsive navbar không dùng Javascript

Sử dụng thuộc tích checked của thẻ input đối với thẻ label để dùng được tính năng khi thẻ input được checked thì những css trong thẻ label được kích hoạt

**Đây là đoạn code ở file html mẫu 
                   <label for="nav-mobile-input" class="nav__mobile-icon">
                    <svg class="nav__mobile-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"/></svg>
                </label>
            </ul>
        </nav>
        <input type="checkbox" name="" class="nav__input" id="nav-mobile-input">
        <label for="nav-mobile-input" class="overplay-backgroud"></label>
        <label class="nav__mobile">
            <label for="nav-mobile-input" class="nav__mobile-close">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Pro 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M342.6 150.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0L192 210.7 86.6 105.4c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L146.7 256 41.4 361.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L192 301.3 297.4 406.6c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L237.3 256 342.6 150.6z"/></svg>
            </label>

Trong đó ta đặt id của thẻ input là nav-mobile-input
Sau đó để các thẻ label có thể check được thẻ input thì ta cần thêm attribute for="id" vào thẻ label như đoạn dưới đây
`<label for="nav-mobile-input" class="overplay-backgroud"></label>`