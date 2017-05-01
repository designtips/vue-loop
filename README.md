<img width="1253" alt="screen shot 2017-04-30 at 9 19 04 pm" src="https://cloud.githubusercontent.com/assets/3231370/25569753/b46b9db4-2dea-11e7-9064-c71a6b450f3e.png">

# Vue Loop
We've had a lot of people compliment us on the infinite content loop we did over at [Look Studios](http://lookstudios.xyz). We decided to build a simple .vue file for all you vue fans to use.

[Live Demo](https://cdn.rawgit.com/lookstudios/vue-loop/ea086525/Examples/public/index.html)

## Installation
`npm install vue-loop --save`

### Usage 
```javascript
import VueLoop from 'vue-loop'

new Vue({
    el: '#app',

    components: {
        VueLoop
    }
})
```

```html
<vue-loop :full="true" :horizontal="false">
    <div class="item">
        1
    </div>
    <div class="item">
        2
    </div>
    <div class="item">
        3
    </div>
    <div class="item">
        4
    </div>
</vue-loop>
```

## Optional Props
| Prop          | Type          | Default       |
| ------------- |:-------------:|:-------------:|
| full          | Boolean       | true          |
| horizontal    | Boolean       | false         |

## Features
- Full page content looping
- Contained content loop
- Horizontal & Vertical options

## Support
- [joe@lookstudios.co](mailto:joe@lookstudios.co)
- [@lookstudiosco](http://twitter.com/lookstudiosco)

## License
MIT
