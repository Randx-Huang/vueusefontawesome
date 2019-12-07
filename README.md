# vueusefontawesome

載入 Vue - fontawesome 專案

## 效果顯示

![Effect](public/effect.png)

### 效果內容說明

* size
* Fixed width
* Flip horizontally, vertically, or both
* spin, pulse
* Border
* Pull left or right
* Power Transforms
* Masking

#### 額外的載入方式

* 使用html tag i
    main.js

    ```javascript
    import { dom } from "@fortawesome/fontawesome-svg-core";
    dom.watch();
    ```

    Template

    ```HTML
    <i class="fas fa-coffee"></i>
    ```

* 載入多個icon
  
    ```javascript
    import {
    faAppleAlt,
    faSpinner,
    faEdit,
    faCoffee,
    faCircle,
    faCheck
    } from "@fortawesome/free-solid-svg-icons";

    library.add(
    faAppleAlt,
    faApple,
    faSpinner,
    faEdit,
    faCoffee,
    faCircle,
    faCheck
    );
    ```
