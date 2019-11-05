# LearnVanillaJS [#100DaysOfCode]
Repo to commit my Vanilla(pure) javascript learning projects from various resources. 

## Day1 
### AJAX
function getData() {
    $.ajax({
        url : 'example.com',
        type: 'GET',
        success : handleData
    })
}

```javascript
function getData() {
    return $.ajax({
        url : 'example.com',
        type: 'GET'
    });
}

function handleData(data /* , textStatus, jqXHR */ ) {
    alert(data);
    //do some stuff
}

getData().done(handleData);
````
