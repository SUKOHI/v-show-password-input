# v-show-password-input
Vue directive that allows you to confirm password.

[Demo](https://demo-laravel52.capilano-fw.com/vue_show_password_input)

# Installation

    npm i v-show-password-input --save

# Usage

## Basic way

    <input type="password" v-show-password-input>
    
## with v-model

You also can use this directive with `v-model` like so.

    <input type="password" v-show-password-input v-model="inputValue">
    <script>
    
        new Vue({
            el: '#app',
            data: {
                inputValue: ''
            }
        })

    </script>
    
# License

This package is licensed under the MIT License.

Copyright 2018 Sukohi Kuhoh