# Vuejs Style Guide



## Vuejs component script style

```javascript
export default {
    // props can be array and all the javascript style guide apply here
    props: ['wow', 'wowStyle', 'newVar'],
    
    // props can be object
    props: {
        wow: {
            type: String,
            default: 'wow',
        },
        wowStyle: String,
        newVar: {
            type: Boolean,
            default: false,
        },
        extraVar: {
            type: Object,
            required: true,
		},
    },
    
    // data structure
    data() {
        return {
            wow: 'Wow',
            newVar: false,
            arr1: ['wow', 'wowStyle', 'newVar'],
        }
    },
    
    // mounted function
    mounted() {
    	//   
    },
    
    // before destroy function
    beforeDestroy() {
        //
    },
    
    // methods obj
    methods: {
    	// functions inside methods
        functionName() {
            
        },
        functionNameWithParams(param1, param2) {
            
        },
    },
}
```

