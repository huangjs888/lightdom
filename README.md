<!--
 * @Author: Huangjs
 * @Date: 2021-05-10 15:55:29
 * @LastEditors: Huangjs
 * @LastEditTime: 2023-07-26 17:53:00
 * @Description: ******
-->
## damping
拖动阻尼算法
### 使用方法
```javascript

import { revokeDamping, performDamping } from '@huangjs888/damping';

const a = performDamping(100, 500);
const b = revokeDamping(a, 500);

  
```
