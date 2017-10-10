# vuejs

some common usage of vuejs snippets!

#pass a refrence to the dom element that ccreated the event.

```javascript
div(v-for='t in ths' v-on:mouseover="addextraInfotoHeader)" data-tooltip='', data-position='bottom center')
```
```javascript
<script>
  
  .....vue init...
  
  methods:{
  addextraInfotoHeader:function(event){
  console.log(event.currentTarget); //acesss target
  console.log(event.currentTarget.innerText); //acesss innerText
  console.log(event.currentTarget.setAttribute("data-tooltip","oui"); // set/get attribute  
  }
```
