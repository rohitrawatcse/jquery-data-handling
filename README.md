# jquery-data-handling


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

``` <script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").remove(".g");
  });
});

https://www.w3schools.com/jquery/jquery_dom_remove.asp
https://stackoverflow.com/questions/47824/how-do-you-remove-all-the-options-of-a-select-box-and-then-add-one-option-and-se


function(json) {
    var options = [];
    $('#org_category').html('');  // Set the Dropdown as Blank before new Data
    options.push('<option>-- Select Category --</option>');
    $.each(JSON.parse(json), function(i, item) {
        options.push($('<option/>',
        {
           value: item.org_name, text: item.org_name
        }));
    });
    $('#org_category').append(options);  // Set the Values to Dropdown
}


</script> 

```






Ref: https://www.tutorialsteacher.com/jquery/jquery-dom-manipulation
 1. https://stackoverflow.com/questions/170986/what-is-the-best-way-to-add-options-to-a-select-from-a-javascript-object-with-jq
 2. github : https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
 3. https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks
